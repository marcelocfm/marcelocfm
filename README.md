![Marcelo C., enterprise IT automation](banner.png)

# Hi, I'm Marcelo

Enterprise IT and Windows systems specialist: Active Directory, Citrix Virtual Apps and Desktops, SCCM and infrastructure automation. I build tools that turn repetitive admin work (provisioning, decommissioning, health checks, ticket triage) into single-click workflows that read their settings from a config file and log every change they make.

## Stack

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D6?style=flat&logo=windows&logoColor=white)
![Citrix](https://img.shields.io/badge/Citrix-452170?style=flat&logo=citrix&logoColor=white)
![SCCM](https://img.shields.io/badge/SCCM-0078D6?style=flat&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![WPF/WinForms](https://img.shields.io/badge/WPF%2FWinForms-512BD4?style=flat&logo=dotnet&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## diagtool

[diagtool](https://github.com/marcelocfm/diagtool) is a portable PowerShell GUI for Service Desk remote sessions. One run collects the evidence a ticket usually needs:

- critical and error events from the System log, driver failures (Event ID 219) and unexpected reboots (Event ID 41)
- SFC and CHKDSK results
- `ipconfig /all` and a DNS reachability test
- OS, hardware and disk inventory

Everything is saved as CSV and text files in one folder, ready to attach to the ticket. It runs on Windows 10, 11 and Server 2016+ with PowerShell 5.1.

## How I build

- **Config-driven.** Server names, OUs and mail settings live in a config file, so a tool written for one environment moves to the next without a rewrite.
- **Auditable.** Anything that changes state logs what happened, who did it and to what.
- **No secrets in code.** Credentials are asked for at run time or kept as Windows-encrypted (DPAPI) strings, never written into scripts or config files.

## Contact

[LinkedIn: in/marcelocfm](https://www.linkedin.com/in/marcelocfm/)
