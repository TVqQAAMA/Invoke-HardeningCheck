A fork from Invoke-HardeningKitty.

Included a Rationale column for 'finding_list_cis_microsoft_windows_server_2019_1809_1.1.0_machine.csv', that will be included when the -Report parameter is used. Useful for copy and pasting into the report. Rationale does not appear for Passed.

Usage:

```
Import-Module Invoke-HardeningCheck.ps1
Invoke-HardeningCheck -FileFindingList .\rationale\finding_list_cis_microsoft_windows_server_2019_1809_1.1.0_machine.csv -Report
```
