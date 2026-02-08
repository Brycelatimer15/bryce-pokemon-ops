
# Bryce Pokémon Ops (Streamlit App)

## Run locally
1) Install Python 3.10+
2) In a terminal:
   pip install -r requirements.txt
3) Start:
   streamlit run app.py

## Weekly workflow
1) Export from Collectr (CSV)
2) Upload CSV into app
3) (Optional but recommended) Upload last week's history.csv
4) Download the new history.csv and save it for next week

## Notes
- Uses conservative eBay fee and shipping assumptions (editable in sidebar)
- Allocates pack spend across items where Avg Cost Paid = 0, proportional to value
- Trend alerts require accumulating history over multiple weeks
