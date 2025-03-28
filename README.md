# 🔍 Data Profiler

A lightweight, portable Python data profiling tool for Excel or CSV files.

## Features
- Profiles column types, nulls, and summary stats
- Calculates skew/kurtosis (with or without `scipy`)
- Generates histogram charts (PNG)
- Outputs clean CSV/JSON summaries for Tableau, ThoughtSpot, Excel, etc.

## Usage

1. Update `config.json`:
```json
{
  "data_path": "sample_data/example.xlsx",
  "sheet_name": null
}
```

2. Run via script:
```bash
python data_profile_scaffold.py
```

Or open `data_profile_scaffold.ipynb` in JupyterLab.

3. Output will be saved to the `outputs/` folder.

## Requirements
```bash
pip install -r requirements.txt
```

## License
MIT
