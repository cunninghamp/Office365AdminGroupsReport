# Office 365 Admin Groups Report

### A PowerShell script to generate a report of Office 365 admin role/group membership.

This script produces a report of the membership of Office 365 admin role groups. The report is output to CSV file.

## Usage

This script relies on the AzureAD PowerShell module, which you can [install from the PowerShell Gallery](https://docs.microsoft.com/en-us/powershell/azure/install-adv2?view=azureadps-2.0).

1. Download the latest release from the [TechNet Script Gallery](https://gallery.technet.microsoft.com/office/Office-365-Role-Groups-b1eb6c6a).
2. Run the script using the usage examples below. You will be prompted to authenticate to Azure AD if you are not already connected.

### Parameters

- **ReportFile** - You can provide a custom output file name. The file name you specify will be modified with the current date, for example MyReportFileName.csv will become MyReportFileName-ddMMyyyy.csv. If a file of the same name exists, a unique character string will also be appended to the file name.

- **Overwrite** - Overwrites an existing report file of the same name, instead of appending a unique character string.

### Examples

```
.\Get-O365AdminGroupsReport.ps1
```

```
.\Get-O365AdminGroupsReport.ps1 -ReportFile MyReportFileName.csv -Overwrite
```

```
.\Get-O365AdminGroupsReport.ps1 -Verbose
```

## Credits

Written by: Paul Cunningham

Find me on:

* My Blog:	http://paulcunningham.me
* Twitter:	https://twitter.com/paulcunningham
* LinkedIn:	http://au.linkedin.com/in/cunninghamp/
* Github:	https://github.com/cunninghamp

For more Office 365 tips, tricks and news check out [Practical 365](http://practical365.com).

* Website:	https://practical365.com
* Twitter:	http://twitter.com/practical365
* Facebook: https://www.facebook.com/Practical365

