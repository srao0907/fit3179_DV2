#Australia’s Volunteers: Who, Where and Why

FIT3179 Data Visualisation 2, Monash University. Simran Rao, October 2026.

A single-page data story about who volunteers in Australia, where they live and how volunteering is changing.

- `index.html`: the page (Pure.css grid, charts embedded with vega-embed)
- `css/styles.css`: layout and typography
- `js/*.vg.json`: one readable Vega-Lite (or Vega, for the treemap) specification per chart
- `data/`: CSV and TopoJSON files used by the charts
- `sketch.pdf`: the hand-drawn A4 sketch

## Charts
1. Line chart: formal and informal volunteering 2010–2025
2. Tile-grid cartogram: states, 2025 rate and change since 2020
3. Choropleth map: rate by local council (Census 2021)
4. Proportional symbol map: number of volunteers by council
5. Treemap (Vega): every council grouped by state
6. Heatmap: age group × state
7. Back-to-back bar chart (population pyramid): age × sex
8. Dumbbell chart: labour force status 2020 vs 2025
9. Marimekko chart: hours volunteered by age group
10. Sorted bar chart: types of organisation

## Data sources
- ABS Census of Population and Housing 2021, GCP DataPack table G23 (Local Government Areas)
- ABS Local Government Areas 2021 boundaries (ASGS Ed. 3), simplified with mapshaper
- Volunteering Australia (May 2026), *Volunteering Statistics: General Social Survey 2025* (ABS GSS 2025)
