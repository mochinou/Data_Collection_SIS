# Airport Operations Analysis

Jupyter Notebook project examining flight events and weather at Almaty International Airport (ALA/UAAA).

## Files
- `Airport_Operations_Analysis.ipynb` — collection, cleaning, merging, EDA, and plots.
- `requirements.txt` — Python dependencies.
- `data/` and `figures/` are created when notebook cells run.

## Run
1. Install dependencies: `python -m pip install -r requirements.txt`
2. Start Jupyter in this directory: `jupyter notebook`
3. Run the notebook from top to bottom.
4. At the OpenSky section, enter an OpenSky API client ID and secret when prompted. The secret is hidden and is not saved to the notebook. Do not commit API credentials.

The notebook makes 28 OpenSky requests for a 14-day study period (one arrivals and one departures request per day), so OpenSky account permissions and API rate limits apply. If the airport flight endpoints deny historical access, resolve that access before interpreting or writing up flight/weather results. The notebook intentionally does not fabricate missing flight data.
