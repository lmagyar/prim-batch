# Changelog

## 0.7.0

- Subprocess (prim-sync, prim-ctrl) exit code 130 results in Ctrl-C/KeyboardInterrupt
- Ctrl-C/KeyboardInterrupt results in exit code 130
- Folders can be bundled
- Test network availability even when not a scheduled run
- Optionally per-server/per-folder --ctrl-args and --sync-args arguments
- Don't use --backup-state and --restore-state options if there is no --tailscale option is used
- Update dependencies and project file structure

## 0.6.1

- Refactor exception logging arguments

## 0.6.0

- Configurable lock file location
- Fix exception logging for test option
- Make toml config options optional

## 0.5.5

- Update prim-ctrl config example in readme

## 0.5.4

- Strip newline from previous state
- Refactor logging

## 0.5.3

- Change scheduled log format

## 0.5.2

- Change scheduled log format
- Refactor exception logging

## 0.5.1

- Update Python installation in Readme

## 0.5.0

- BREAKING CHANGE: Rename --skip-ctrl to --sync-only
- Fix --ctrl-only default option

## 0.4.0

- Add --ctrl-only {test,start,stop} option

## 0.3.0

- Fix --servers and --folders, iterate all items
- Add server names to the log

## 0.2.0

- Fix networking test when --scheduled
- Update dependencies

## 0.1.0

- Publish on PyPI
- Initial upload
