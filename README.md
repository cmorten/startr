# startr

Yet another opinionated startup script for new macs.

## Usage

To execute the script, run `./startr` in a terminal:

```console
USAGE:
./startr [options]

options:
-n              specify name              [required]
-u              specify GitHub username   [required if not already configured]
-p              specify GitHub password   [required if not already configured]
-e              specify email             [required if not already configured]
-h, --help      show help
```

> Warning: It is recommended that you fork this repo and review the script before running - use at your own risk!

The script makes the assumption that you have already created a GitHub account.

To add / remove apps edit the constant arrays in the `Constants` section.

## Easy Install

Run the script directly from this repo with commands like:

```bash
curl -fsSL https://raw.githubusercontent.com/cmorten/startr/main/startr | bash -s -- -n "Craig Morten"
```
