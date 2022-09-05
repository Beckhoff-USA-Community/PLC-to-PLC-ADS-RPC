# Introduction

## First pass
This is just an OO refactor/wrap of some of the core FBs to make them friendlier / more flexible for that approach. 

## Roadmap
* Create a handle manager. ST_SymbolHandles can get stored there, so when requests are made by client code, they don't require awareness of handle condition.
* Create a MessagePool colleciton, such that client code can make multiple calls per scan, not considering/caring about managing specific instances. As long as there are free calls in the pool.
* Develop command pattern for fall back of above (i.e. if no current caller available, add to command queue.)
  * Always return an I_Executable, regardless of concrete or command queue. This communicates state to client code.
* Create a global/static finaliser, disposing of active handles in 