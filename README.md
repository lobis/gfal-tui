# gfal-tui

Standalone Textual TUI extracted from [`gfal`](https://github.com/lobis/gfal).

It depends on `gfal` for the actual filesystem operations and provides a
two-pane browser for local files, HTTPS/WebDAV, and XRootD paths.

## Install

```bash
pip install -e .
```

This installs the `gfal-tui` executable.

## Run

```bash
gfal-tui
gfal-tui root://eospublic.cern.ch//eos/opendata/cms/ .
```

## Development

```bash
python -m pip install -e ".[dev]"
pre-commit run --all-files
pytest tests/ -q
```
