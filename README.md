# Roptimizer

**Asset Optimization CLI for MTA:SA**

A Python-based command-line tool designed to analyze and optimize RenderWare assets used in Multi Theft Auto: San Andreas.

Roptimizer focuses on controlled asset processing, file integrity, and repeatable batch operations.

[![Watch Showcase](https://img.shields.io/badge/Watch_Showcase-YouTube-0D1117?style=for-the-badge&logo=youtube&logoColor=FF0000)](https://youtu.be/e7iSq0tSUxU)

## Video Showcase

[![Roptimizer Video Showcase](https://img.youtube.com/vi/e7iSq0tSUxU/hqdefault.jpg)](https://youtu.be/e7iSq0tSUxU)

## Key Features

- **TXD Optimization:** Texture processing with configurable compression and mipmap generation.
- **DFF Optimization:** Model processing and geometry optimization.
- **Batch Processing:** Analyze and optimize multiple assets in a single operation.
- **Validation:** Check file structures before accepting optimized output.
- **Backup & Recovery:** Preserve original assets during processing.
- **Optimization Profiles:** Select different optimization levels based on project requirements.
- **JSON Reports:** Review processing results and file-size changes.

## Technical Overview

| Component | Technology |
|---|---|
| Language | Python |
| Interface | Command-line (CLI) |
| Asset formats | TXD, DFF |
| Asset framework | RenderWare |
| Texture compression | BC1 / BC3 |
| Reporting | JSON |

## Project Scope

Roptimizer is intended for developers working with MTA:SA resources who need a repeatable process for inspecting and optimizing asset collections.

Optimization results depend on the original assets, their formats, and the selected processing profile. All optimized assets should be validated and tested in-game before deployment.

## Availability

Roptimizer is a proprietary software project. This repository serves as its public technical overview and video showcase; the implementation source code is not distributed here.

## Developer

**ARIA ZEUS** — Software Engineer & Full-Stack Developer

[GitHub Profile](https://github.com/ARIA-ZEUS) · [RocoShop](https://rocoshop.ir)
