# PowerBI
Project Context:
This report was created for the Engeto Akademie training as part of the TEMP Power BI projekt (Lekce 1 / 1: Datová Akademie projekt 2: Power BI). The goal is to visualize selected datasets in an interactive Power BI report, meeting the following criteria:
- 2–3 report pages
- At least 5 different visual types
- Filtering via slicers and bookmark/page navigation
- Integration of multiple data sources
- Use of a data hierarchy with at least two levels
- Creation of at least 1 measure and 1 calculated column
- Visually polished, user-friendly design

****Data** - Loaded files:**
- Episodes and Ratings.csv
- GOT_screentimes.csv
- characters.json
- game-of-thrones-deaths-data.csv

**Logic Highlights:**
- Defined table relationships on Season and CharacterID across datasets.
- Applied slicers for Season and Episode to slice visuals dynamically.
- Aggregated data using AVERAGE, SUM, COUNTROWS, and CALCULATE for running totals and percentage changes.

**Report Pages:**
- Ratings Overview: Matrix of episode ratings by season, plus cards for total episodes and average rating.
- Deaths Analysis: Cards showing total deaths and kills; line chart of deaths per season; stacked bar chart of deaths by house; bar chart of kills by character.
- Screentime Analysis: Cards for total screentime, distinct characters, and average screentime; bar chart of screentime by house; table of top characters by screentime.

**Outcome:** An interactive Power BI report delivering clear insights into ratings, character presence, and mortality trends.
