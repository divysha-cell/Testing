# ATP Sanity




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
|Siemplify_Case Comment_2|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|MicrosoftDefenderATP_Get User Related Alerts_1|Use the Get User Related Alerts action to list alerts associated with specific users in Microsoft Defender for Endpoint. Supported Entities: User.|MicrosoftDefenderATP|Get User Related Alerts|
|MicrosoftDefenderATP_Get User Related Alerts_4|Use the Get User Related Alerts action to list alerts associated with specific users in Microsoft Defender for Endpoint. Supported Entities: User.|MicrosoftDefenderATP|Get User Related Alerts|
|MicrosoftDefenderATP_Get Machine Recommendations_3|Use the Get Machine Recommendations action to retrieve a list of security recommendations for specific machines in Microsoft Defender for Endpoint.Supported Entities: IP Address, Hostname.|MicrosoftDefenderATP|Get Machine Recommendations|
|MicrosoftDefenderATP_Get Machine Recommendations_2|Use the Get Machine Recommendations action to retrieve a list of security recommendations for specific machines in Microsoft Defender for Endpoint.Supported Entities: IP Address, Hostname.|MicrosoftDefenderATP|Get Machine Recommendations|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|MicrosoftDefenderATP_Get Machine Recommendations_1|Use the Get Machine Recommendations action to retrieve a list of security recommendations for specific machines in Microsoft Defender for Endpoint.Supported Entities: IP Address, Hostname.|MicrosoftDefenderATP|Get Machine Recommendations|
|MicrosoftDefenderATP_Get User Related Alerts_3|Use the Get User Related Alerts action to list alerts associated with specific users in Microsoft Defender for Endpoint. Supported Entities: User.|MicrosoftDefenderATP|Get User Related Alerts|
|MicrosoftDefenderATP_Get User Related Alerts_2|Use the Get User Related Alerts action to list alerts associated with specific users in Microsoft Defender for Endpoint. Supported Entities: User.|MicrosoftDefenderATP|Get User Related Alerts|
|MicrosoftDefenderATP_Get Machine Recommendations_4|Use the Get Machine Recommendations action to retrieve a list of security recommendations for specific machines in Microsoft Defender for Endpoint.Supported Entities: IP Address, Hostname.|MicrosoftDefenderATP|Get Machine Recommendations|

