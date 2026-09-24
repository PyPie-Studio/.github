<div align="center">

<img src="https://raw.githubusercontent.com/PyPie-Studio/.github/main/profile/banner.jpg" alt="PyPie Studio" width="100%" />

<br />
<br />

### Self-contained .NET tools for sysadmins and network engineers. Native binaries, local-only data, no cloud dependencies.

<br />

<p align="center">
  <a href="https://github.com/PyPie-Studio"><img src="https://img.shields.io/badge/GitHub-PyPie--Studio-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <a href="https://www.instagram.com/pypiestudio"><img src="https://img.shields.io/badge/Instagram-@pypiestudio-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="mailto:pypiestudio@gmail.com"><img src="https://img.shields.io/badge/Email-pypiestudio%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linktr.ee/pypiestudio"><img src="https://img.shields.io/badge/Linktree-PyPie--Studio-39E09B?style=for-the-badge&logo=linktree&logoColor=white" alt="Linktree" /></a>
</p>

</div>

---

## About

**PyPie Studio** is a small software engineering studio building self-contained tools for system administrators, network engineers and IT departments. The stack runs on **.NET 10** — NativeAOT desktop apps, ASP.NET Core backends and Avalonia cross-platform UIs.

Everything ships as a single binary or installer. No cloud accounts, no telemetry, no runtime prerequisites. Data stays on the machine it was created on, encrypted at rest with AES-256.

---

## Open Source

### [NodeRadar Pro](https://github.com/PyPie-Studio/NodeRadar-Pro)

> Desktop network monitoring and host discovery for Windows

[![C#](https://img.shields.io/badge/C%23-.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://github.com/PyPie-Studio/NodeRadar-Pro)
[![Avalonia UI](https://img.shields.io/badge/Avalonia_UI-12.1-8B44AC?style=flat-square)](https://github.com/PyPie-Studio/NodeRadar-Pro)
[![NativeAOT](https://img.shields.io/badge/NativeAOT-Compiled-00C853?style=flat-square)](https://github.com/PyPie-Studio/NodeRadar-Pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://github.com/PyPie-Studio/NodeRadar-Pro)
[![Latest Release](https://img.shields.io/github/v/release/PyPie-Studio/NodeRadar-Pro?style=flat-square&color=2563eb&label=Release)](https://github.com/PyPie-Studio/NodeRadar-Pro/releases/latest)

Discovers every device on your LAN using multi-threaded ARP and ICMP sweeps. Tracks per-host latency and jitter over time and alerts when an unrecognized MAC address appears on the network. Ships as a NativeAOT binary — no .NET runtime install required.

- **Subnet scanning** — Concurrent ARP + ICMP discovery with OS fingerprinting via MAC OUI, mDNS, SSDP and open port probes
- **Live monitoring** — Interactive radar-style topology view showing device states and real-time ICMP latency
- **Rogue device alerts** — Background watchdog that flags unrecognized MAC addresses as they connect
- **Latency tracking** — Jitter analysis, packet loss history and uptime graphs per host
- **Local-only storage** — LiteDB with AES-256 encryption; nothing leaves the machine

[**Download Latest Release**](https://github.com/PyPie-Studio/NodeRadar-Pro/releases/latest) · [**Source**](https://github.com/PyPie-Studio/NodeRadar-Pro) · [**Changelog**](https://github.com/PyPie-Studio/NodeRadar-Pro/releases)

---

### [unslop-windows](https://github.com/PyPie-Studio/unslop-windows)

> Standalone PowerShell debloater for Windows 10 and 11

[![PowerShell](https://img.shields.io/badge/PowerShell-5.1_&_7+-5391FE?style=flat-square&logo=powershell&logoColor=white)](https://github.com/PyPie-Studio/unslop-windows)
[![Windows 11](https://img.shields.io/badge/Windows_11-25H2_|_24H2_|_23H2-0078D4?style=flat-square&logo=windows11&logoColor=white)](https://github.com/PyPie-Studio/unslop-windows)
[![Windows 10](https://img.shields.io/badge/Windows_10-22H2_|_LTSC-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/PyPie-Studio/unslop-windows)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://github.com/PyPie-Studio/unslop-windows/blob/main/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/PyPie-Studio/unslop-windows?style=flat-square&color=3DA639&label=Release)](https://github.com/PyPie-Studio/unslop-windows/releases/latest)
[![CI](https://img.shields.io/github/actions/workflow/status/PyPie-Studio/unslop-windows/lint.yml?style=flat-square&label=CI)](https://github.com/PyPie-Studio/unslop-windows/actions)

Disables telemetry, removes pre-installed bloatware, blocks Recall and Copilot, and cleans up background services — without breaking Windows Update or the Microsoft Store. 18 modules, each with a matching `-Undo` flag that reverts every registry key, service and scheduled task change.

- **Presets** — Full debloat, Gamer (keeps Xbox/gaming services), Productivity (keeps OneDrive/To-Do), or interactive per-module toggles
- **Dry-run mode** — Preview every change without admin rights or modifying anything
- **Full undo** — Single `-Undo` flag reverts all tweaks to Windows defaults
- **Pure script** — PowerShell + Batch only. No compiled binaries, no downloads, no network calls

[**Download Latest Release**](https://github.com/PyPie-Studio/unslop-windows/releases/latest) · [**Source**](https://github.com/PyPie-Studio/unslop-windows) · [**Changelog**](https://github.com/PyPie-Studio/unslop-windows/blob/main/CHANGELOG.md)

---

## What We Work On

Beyond the public repos, PyPie Studio builds commercial and internal tools in these areas:

| Domain | What it covers |
| :--- | :--- |
| **Network and infrastructure** | Subnet discovery, real-time device monitoring, topology mapping, port scanning |
| **Enterprise management** | Task management, team dashboards, real-time sync via SignalR, mobile PWA companions |
| **Education platforms** | Student records, attendance, timetable generation, exam grading, Telegram-based notifications |
| **System hardening** | OS debloating, telemetry removal, encrypted local backups |

---

## Stack

<div align="center">

#### Languages
![C#](https://img.shields.io/badge/C%23_14-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)

#### Frameworks and Runtimes
![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Avalonia UI](https://img.shields.io/badge/Avalonia_UI-8B44AC?style=for-the-badge)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-0078D4?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor_PWA-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![WinForms](https://img.shields.io/badge/Windows_Forms-0078D4?style=for-the-badge&logo=windows&logoColor=white)

#### Data and Storage
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![LiteDB](https://img.shields.io/badge/LiteDB-AES_256-2D333B?style=for-the-badge)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-0078D4?style=for-the-badge)

#### Testing and Compilation
![xUnit](https://img.shields.io/badge/xUnit_v3-512BD4?style=for-the-badge)
![Pester](https://img.shields.io/badge/Pester_5%2F6-5391FE?style=for-the-badge)
![NativeAOT](https://img.shields.io/badge/NativeAOT-00C853?style=for-the-badge)

</div>

---

<div align="center">

<br />

<sub>© 2026 PyPie Studio</sub>

</div>
