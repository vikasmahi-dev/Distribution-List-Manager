# Distribution List Manager

**Interactive PowerShell script to add or remove members from an Exchange Online distribution group.**

---

## Prerequisites

- PowerShell 5.1 or later  
- ExchangeOnlineManagement module  

```powershell
Install-Module ExchangeOnlineManagement -Scope CurrentUser
```
---

Quick Start

    Open PowerShell as Administrator and navigate to the script folder.

    Run:

    .\DLManager.ps1

    Follow the prompts:

        1 to Add or 2 to Remove members

        Enter the distribution group name

        Enter one UPN per line (blank line to finish)

All operations and errors are logged to:
DL_Operations_YYYYMMDD-HHMMSS.log

---

👨‍💻 Author

Vikas Mahi – Infrastructure Architect & Technical Lead | AWS • Azure • VMware • Automation

---

📜 License

MIT © Vikas Mahi
