# Strategic Relocation from Overcrowded to Underpopulated Cities in Türkiye

A data-driven analysis that identifies optimal internal migration corridors in Türkiye by evaluating overcrowded metropolitan areas against underpopulated provinces using multi-criteria decision-making and geospatial analytics.

## Overview

Rapid urbanization has created significant population imbalances across Türkiye: a handful of metropolitan centers—Istanbul, Ankara, İzmir—absorb the majority of economic activity and newcomers, while hundreds of smaller provinces face depopulation, aging demographics, and underutilized infrastructure. This project quantifies these imbalances and proposes evidence-based relocation strategies that could benefit both sending and receiving regions.

## Key Questions

- Which cities are most critically overcrowded by composite indicators (population density, housing cost, commute time, air quality)?
- Which underpopulated provinces offer the most favorable conditions for attracting new residents (employment potential, infrastructure, quality of life)?
- What policy levers and incentive structures are most likely to shift migration patterns?

## Methodology

- **Data collection:** TurkStat (TÜİK) population and migration records, Ministry of Environment urban density indices, housing price indices
- **Feature engineering:** Composite overcrowding score and composite attractiveness score per province
- **Scoring & ranking:** Weighted multi-criteria analysis to rank candidate destination cities
- **Visualization:** Choropleth maps and bubble charts illustrating migration pressure and opportunity zones

## Project Structure
├── main.ipynb                                              # Full analysis notebook
└── Strategic Relocation from Overcrowded to
Underpopulated Cities in Turkiye.pdf                    # Project report

## Usage

Open `main.ipynb` in Jupyter and run all cells sequentially. No external API keys required; all data sources are embedded or publicly downloadable from TÜİK.

## Technologies

Python · Pandas · GeoPandas · Matplotlib · Seaborn · Jupyter Notebook
