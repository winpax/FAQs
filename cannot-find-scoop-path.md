# Cannot find scoop path

## Relevant Issues

- [#759](https://github.com/winpax/sfsu/issues/759)
- [#824](https://github.com/winpax/sfsu/issues/824)
- [#89](https://github.com/winpax/sprinkles/issues/89)

## Problem

Scoop is installed at a non-default path, and `sfsu` or `sprinkles` crashes, with an error akin to: `Cannot find Scoop path`

## Solution

- Set the path in the `root_path` field in `~/.config/scoop/config.json`

Or

- Set the `SCOOP` environment variable to the path where scoop is installed.
