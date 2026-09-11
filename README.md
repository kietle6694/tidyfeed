# tidyfeed

Small pandas pipeline that cleans messy CSV exports

## Installation

```bash
pip install -r requirements.txt
```

## Examples

```bash
python pipeline.py raw.csv --config config.yaml --out clean.csv
```

## Features

- Chunked reading for files that do not fit in memory
- Config-driven column renames and type casts
- Drops duplicates, trims strings, normalizes dates
- Writes a cleaning report next to the output

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── config.yaml
├── pipeline.py
└── requirements.txt
```

## License

MIT. Do whatever you want.
