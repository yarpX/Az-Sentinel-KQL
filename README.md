# Az-Sentinel-KQL

A collection of KQL queries I've put together while working within Sentinel.

  
  

| Name | Description |
| ---- | ---- |
| [PIMRoleActivationsViaScript.kql](./KQL/PIMRoleActivationsViaScript.kql) | Find users who have activated their PIM roles via script. This detects 5 or more PIM role activations within a 5 minute sliding window.  |
| [InteractiveServiceAccounts.kql](./KQL/InteractiveServiceAccounts.kql) | Find service accounts that are logging in interactively. This may need to be adjusted to fit your environment (OU location or service account naming scheme). |
| [GetSizeOfTableFilteredByColumns.kql](./KQL/GetSizeOfTableFilteredByColumns.kql) | Take a table and filter it. Then determine the size of all items scoped by that filter in MB. Useful for cost adjustment. |
| [GetAnomalousDataIngestion.kql](./KQL/GetAnomalousDataIngestion.kql) | Look back 60 days and build a baseline for data ingestion volume, then show anomalies using series_decompose_anomalies |
| [GetIngestionLag.kql](./KQL/GetIngestionLag.kql) | Take the last 8 hours and display the 90th percentile of difference between ingestion time and TimeGenerated. |