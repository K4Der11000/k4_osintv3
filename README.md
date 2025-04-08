# Leak Scanner by kader11000

A web-based leak scanner built with Flask that allows searching for keywords in public or local leaked databases.

## Features

- Search for leaks using online input, local keywords, or uploaded files.
- Supports `.txt`, `.csv`, `.xlsx`, and `.zip` file formats.
- Scan results displayed in a styled terminal-like interface.
- Table view with real-time filtering by keyword or domain.
- Password-protected web interface.

## Requirements

- Python 3.x
- Flask
- pandas
- openpyxl (for .xlsx support)

## Installation

```bash
pip install Flask pandas openpyxl
```

## Run the App

```bash
python app.py
```

Then open: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

**Password to access the interface:** `kader11000`
