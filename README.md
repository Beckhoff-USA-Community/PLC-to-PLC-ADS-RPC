# About This Repository

Example contains:
1. A "provider" PLC on port 851, with a PLC function block method exposed to RPC calls via ADS.
2. A Caller PLC on port 851, with a example PLC function block to call the PLC function block method on port 851.

The "FB_InvokeRpcMethod" is generic and can be used on any PLC method exposed via the attribute ["{attribute 'hide_all_locals'}"] (https://infosys.beckhoff.com/content/1033/tc3_plc_intro/7145472907.html?id=6105454089919227750)

![image](https://user-images.githubusercontent.com/19829308/175129449-5372aa6f-0dbd-4113-8aaf-6c37382e4035.png)


This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

# How to get support

Should you have any questions regarding the provided sample code, please contact your local Beckhoff support team. Contact information can be found on the official Beckhoff website at https://www.beckhoff.com/en-us/support/.


## Requirements

The following components must be installed to run sample code:
- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher

