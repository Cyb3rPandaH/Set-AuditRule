# Set-AuditRule

![Open_Threat_Research Community](https://img.shields.io/badge/Open_Threat_Research-Community-brightgreen.svg)

A repository of useful access control entries (ACE) on system access control list (SACL) of securable objects to find potential adversarial activity.
These entries are categorized by specific securable objects such as files, registry keys and ad objects.
In addition, this project comes with a PowerShell script that will help you to set the audit rules in a programmatic way at scale.
The script also leverages PowerShell dynamic parameters to provide auto-complete capabilities and provide the values needed for each flag directly from the access control and directory service classes.

# Goals

* Document useful audit rules to detect potential adversaries
* Expedite development and deployment of audit rules in networks
* Test audit rules volume and share findings with the community
* Map audit rules to adversarial tooling 
* Learn about System Access Control Lists (SACL)
* Learn about PowerShell Dynamic Parameters
* Learn about Microsoft Security Access Control classes

# References

* [Access Control Namespace](https://docs.microsoft.com/en-us/dotnet/api/system.security.accesscontrol?view=netframework-4.8)
* [Registry Access Control Rights](https://docs.microsoft.com/en-us/dotnet/api/system.security.accesscontrol.registryrights?view=dotnet-plat-ext-3.1#fields)
* [Files Access Control Rights](https://docs.microsoft.com/en-us/dotnet/api/system.security.accesscontrol.filesystemrights?view=netframework-4.8)

# Authors

* Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)

# Contributing

If you have an audit rule that you believe are useful in your environment to detect potential adversarial activity and would like share it with the community, feel free to open a PR!

# License: GPL-3.0

[ Set-AuditRule's GNU General Public License](https://github.com/Cyb3rWard0g/Set-AuditRule/blob/master/LICENSE)