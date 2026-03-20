# Crowdstrike Playbook




**Enabled:** False

**Version:** 0

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|CrowdStrikeFalcon_Execute Command_1|Execute commands on the hosts in Crowdstrike Falcon. Supported entities: IP Address and Hostname.|CrowdStrikeFalcon|Execute Command|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|CrowdStrikeFalcon_Run Script_1|Execute a powershell script on the endpoints in Crowdstrike. Supported entities: IP Address, Hostname. Note: Action is running as async, please adjust script timeout value in Google SecOps IDE for the action, as needed.|CrowdStrikeFalcon|Run Script|

