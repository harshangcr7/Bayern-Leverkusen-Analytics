# Football Analytics with StatsBomb Open Data

This project performs **exploratory football analytics and visualization** using **event-based data** from **StatsBomb Open Data**.  
The notebook focuses on understanding match events, shot outcomes, expected goals (xG), player performance, and passing structures using Python-based data analysis and visualization tools.

This is a **descriptive analytics project**.

---

## TL;DR (For Recruiters)

- Used **StatsBomb Open Data** to analyze football event data  
- Performed **shot outcome and expected goals (xG) analysis**  
- Identified **players overperforming and underperforming xG**  
- Built **passing networks** using NetworkX  
- Created tactical visualizations with **mplsoccer**  
- Focused on **football insights and interpretation**  

---

## 📊 Data Source

The analysis uses **StatsBomb Open Data**, accessed via the official Python client.


##  Architecture & Workflow

- Data Ingestion
  Fetch competitions, matches, and event data using statsbombpy
  Load nested JSON into pandas DataFrames
- Data Filtering
  Select specific competitions and matches
  Filter relevant event types (shots, passes)
- Shot Analysis
  Analyze shot outcomes
  Compare goals vs expected goals (xG)
- Visualize shot locations
  xG-Based Player Evaluation
  Aggregate xG and goals at player level
  Identify overperformers and underperformers
  Passing Network Analysis
  Construct passing graphs using networkx
  Visualize team passing structure
  Identify central players in buildup play
- Visualization
  Shot maps
  Distribution plots
  Passing networks
  Tactical diagrams using mplsoccer


## Key Insights

- Expected goals (xG) provides a more informative measure of shot quality than raw goals
- Some players consistently outperform or underperform xG, indicating finishing variance or skill
- Passing networks reveal structural and tactical patterns not visible in summary statistics

## Install all required libraries.

- Open FootballAnalytics.ipynb in Jupyter Notebook or JupyterLab.
- Run the notebook top to bottom in sequence.
- Initial data loading can take 10–15 minutes, as event data is fetched from the StatsBomb API.
- Subsequent analysis and visualization steps execute quickly.

