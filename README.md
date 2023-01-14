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

In the latter stages of the script, it changes the shell to `zsh`. If run originally in a bash shell, the script will need to be run twice to complete fully.

## Assumptions

The script makes the assumption that you already hold a GitHub account.

## Personalisation

To add / remove apps edit the constant arrays in the `Constants` section.

## Feeling Lucky?

Execute from this repo with commands like:

```bash
curl -fsSL https://raw.githubusercontent.com/cmorten/startr/main/startr | bash -s -- -n "Craig Morten"
```
