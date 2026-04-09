# Personal Data Pipeline

This project collects personal data from various sources and loads it into a Ghost Postgres database.

## Data Sources

- Google Bookmarks
- GitHub

## Setup

1. Install dependencies:
   ```bash
   uv sync
   ```

2. Run the data collection and loading scripts:
   ```bash
   ./runbooks/1-google-bookmarks.md
   ./runbooks/2-github.md
   ```

## Files

- `requirements.md`: Lists the required command-line tools
- `runbooks/`: Contains the scripts for collecting and loading data
- `raw/`: Stores the raw data exports
- `gists/`: Contains helper scripts