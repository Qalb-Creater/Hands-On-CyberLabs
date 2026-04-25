# Project 2: Windows Security Log Investigation & Analysis

## 🎯 Purpose
This project demonstrates how to monitor and investigate security events on a Windows system. I simulated common attack vectors (Brute Force and Reconnaissance) to understand how they appear in system logs.

## 🛠️ Skills Demonstrated
- **Log Management:** Configuring Local Security Policies for success/failure auditing.
- **Incident Detection:** Identifying Event ID 4625 (Logon Failure) and 4688 (Process Creation).
- **Forensic Analysis:** Extracting target usernames and command-line arguments from raw log data.

## 📊 Investigation Highlights
- **Credential Access:** Successfully detected a brute-force attempt targeting a "FakeUser" account.
- **Discovery:** Tracked the execution of system tools (`whoami.exe`) used for reconnaissance.

## 📂 Project Files
- [Windows_Log_Investigation_Report.pdf](./Windows_Log_Investigation_Report.pdf) - Full Technical Report.
