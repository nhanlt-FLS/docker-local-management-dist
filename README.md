# Docker Local Management — Releases

This repository contains **only the published installers / app binaries** of
*Docker Local Management* (a lightweight local Docker management UI).
The source code lives in a **private** repository; nothing here is source code,
so the auto-generated "Source code" archives of each release contain just this
README.

## Which file should I download?

Go to **[Releases](https://github.com/nhanlt-FLS/docker-local-management-dist/releases/latest)**:

| File | Platform | What it is |
|---|---|---|
| `docker-local-management-setup-<ver>.exe` | **Windows** | **One-file installer (recommended).** Double-click it, follow the wizard, launch from the Start menu. No admin needed. |
| `docker-local-management-<ver>-win64.exe` | **Windows** | Portable single-file app. No installation — just double-click to run. |
| `install-docker-local-management.sh` | **Linux** | **One-file setup script (recommended).** Run `bash install-docker-local-management.sh`; it installs dependencies, the app, and a menu entry. |
| `docker-local-management-<ver>-x86_64.AppImage` | **Linux** | The app itself for manual use: `chmod +x` then run it. |

## Before you run it

- **Docker must be installed and running on the device.**
- **Windows:** in Docker Desktop enable *Settings → General → "Expose daemon on
  tcp://localhost:2375 without TLS"*, then restart Docker Desktop.
- **Linux:** your user must be able to use Docker (member of the `docker` group).

## Updating

Installed apps check this repository for a newer release on launch and offer to
update themselves — normally you never need to download again.
