# Az-Sentinel-KQL

A collection of KQL queries I've put together while working within Sentinel.

  
  

| Name | Description |
| ---- | ---- |
| [PIMRoleActivationsViaScript.kql](./KQL/PIMRoleActivationsViaScript.kql) | Find users who have activated their PIM roles via script. This uses a sliding window to detect 5 or more PIM role activations within a 5 minute window.  |
| [InteractiveServiceAccounts.kql](./KQL/InteractiveServiceAccounts.kql) | Find service accounts that are logging in interactively. This may need to be adjusted to fit your environment (OU location or service account naming scheme). |
