# Weather Data ETL Pipeline

An industry-relevant ETL pipeline for extracting, transforming, and loading weather data from the OpenWeatherMap API into an SQLite database. 

## Overview
- **Extract**: Fetch weather data via API for Sri Lankan cities.
- **Transform**: Clean, convert, and aggregate data.
- **Load**: Store in SQLite for analysis.
- **Extensions**: Scheduling and visualizations.

## Prerequisites
- Python 3.x (tested on 3.13.3; downgrade to 3.11 if issues).
- OpenWeatherMap API key (free signup).
- Libraries: requests, pandas, sqlite3 (built-in).

## Setup
1. Clone: `git clone https://github.com/SamadhiSamarasekara/weather-etl-pipeline.git`
2. Create venv: `python -m venv venv`
3. Activate: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows).
4. Install: `pip install requests pandas`

## Running
`python etl.py --cities "Colombo,Kandy,Galle" --api_key YOUR_API_KEY`

## License
MIT
