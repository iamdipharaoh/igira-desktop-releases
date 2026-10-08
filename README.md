# Igira Provisoire Desktop — Official Releases

Official Windows binary distribution repository for the **Igira Provisoire** desktop applications:
- **Igira Student Client** — High-speed, offline-ready driving theory practice & exam simulator for driving school computer labs.
- **Igira School Management** — Centralized school dashboard for managing licenses, student seats, exam records, and offline sync.

---

## Downloads

Always download the latest version from the [Releases page](https://github.com/iamdipharaoh/igira-desktop-releases/releases/latest).

| Application | Installer (.exe) | Description |
| :--- | :--- | :--- |
| **Student Client** | `igira-student-setup.exe` | For student examination and practice PCs in computer labs. |
| **School Management** | `igira-management-setup.exe` | For school administration, instructor devices, and license management. |

---

## System Requirements

- **Operating System:** Windows 10 / Windows 11 (64-bit)
- **Runtime:** Microsoft Edge WebView2 Evergreen Runtime *(pre-installed on Windows 10/11; automatically downloaded by installer if missing)*
- **Architecture:** x86_64 / x64

---

## Installation & Setup

1. Go to the [Latest Releases](https://github.com/iamdipharaoh/igira-desktop-releases/releases/latest).
2. Download the installer for your intended application (`igira-student-setup.exe` or `igira-management-setup.exe`).
3. Run the installer and follow the on-screen steps.
4. Launch the application:
   - **Student Client:** Enter your school device activation key or student pass code.
   - **School Management:** Log in with your school administrator credentials.

---

## Automatic Updates

Both desktop applications include secure background update checking:
- **Management Client:** Notifies administrators when a new update is ready with a one-click restart.
- **Student Client:** Updates silently in the background between sessions without interrupting active tests.

All update manifests (`latest-student.json`, `latest-management.json`) and executables are cryptographically signed with Minisign before publication.

---

## About & Support

- **Platform:** [igiraprovisoire.rw](https://igiraprovisoire.rw)
- **Publisher:** Igira Creatives
- **Developer:** Didier INEZA
- **Issues & Feedback:** Contact support via the official web portal or WhatsApp channel.

---

*Note: This repository contains only compiled public binary releases, signed installers, and updater manifests. Source code is maintained privately by Igira Creatives.*
