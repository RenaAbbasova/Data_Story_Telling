# Airbnb Istanbul: exploratory analysis and data storytelling

Exploratory analysis of Airbnb listings in Istanbul, told as a story: where the listings are, what kinds of properties and rooms
there are, how prices and review scores vary by neighbourhood, whether some hosts look like unlicensed hotels and how availability
changes over time. Built during the Upgrade Hub data analytics bootcamp (2022). **The notebook is written in Spanish.**

## What it covers

1. **Data:** 24,864 listings (17 columns in the summary file and 73 in the detailed file) and about 9 million calendar rows.
2. **Exploratory analysis:** neighbourhoods, room types, property types and number of guests.
3. **Potential illegal hotels** and the effect of professional hosts.
4. **Advice for tourists:** average price by neighbourhood, neighbourhood safety, review scores and location, how to use review
   scores, and availability over time.
5. **Text mining** of the reviews (optional section).

## Tools

Python, pandas, NumPy, matplotlib, seaborn, Plotly, Folium, GeoPandas, NLTK, WordCloud and scikit-learn.

## Data

The Airbnb Istanbul dataset (`listings.csv`, `listings_details.csv` and `calendar.csv`). The data is not stored in this repository.

## Limitations

This is a descriptive analysis: it describes patterns in the data, not causes, and it makes no predictions.
