# Aseprite Windows Build

This repository provides scripts and instructions for building [**Aseprite**](https://github.com/aseprite/aseprite) from source on Windows.

## Important Notice: Aseprite EULA Compliance

This project is subject to the [Aseprite End User License Agreement (EULA)](https://github.com/aseprite/aseprite/blob/main/EULA.txt). Please read the EULA carefully before using this repository.

### Key Points from the EULA

- **No Distribution of Binaries:** You may not distribute compiled Aseprite binaries (release builds) from this repository unless you hold a commercial license from the original Aseprite authors.
- **Private Repositories:** If you build or host release binaries from this source, you MUST keep your forked repository private.
- **Source Modifications:** You are allowed to modify, build, and use Aseprite for personal use.
- **Attribution:** Aseprite is developed by David Capello and community contributors. See [Aseprite](https://github.com/aseprite/aseprite) for more information.

### Template for EULA Compliance

> This repository does **not** distribute any Aseprite binaries.  
> All scripts and instructions are provided for personal building purposes only, in compliance with the [Aseprite EULA](https://github.com/aseprite/aseprite/blob/main/EULA.txt).  
> **If you build or distribute release binaries, you must make this repository private.**

## How to Build (For Personal Use Only)

1. Use this template (or fork) as a private repository.
2. (Optional) Add a schedule to run daily builds.
   ```
   schedule:
     - cron: '0 0 * * *'
   ```
3. Do **not** distribute compiled binaries unless you have a commercial license.

## Disclaimer

This project is not affiliated with or endorsed by the official Aseprite project or its authors.  
All rights for Aseprite belong to David Capello and contributors.

---

## FAQ

### libcrypto-1_1-x64.dll Not Found

Download the [OpenSSL 1.1.1 binary for Windows](https://kb.firedaemon.com/support/solutions/articles/4000121705-openssl-3-1-3-0-and-1-1-1-binary-distributions-for-microsoft-windows), and extract the required DLL files to the appropriate location.
