Data on Juvenile Arrests in the DC Area (and related info)
===

### Data

The pipeline:

- Raw data comes from [here](http://mpdc.dc.gov/node/208852)
- These are stored in the [pdf folder](https://github.com/drewbo/dc-juvenile/tree/master/data/pdf)
- Use [Tabula](http://tabula.nerdpower.org/) to convert to [raw csv](https://github.com/drewbo/dc-juvenile/tree/master/data/csv/raw)
- [Aggregate](https://github.com/drewbo/dc-juvenile/tree/master/data/csv/aggregated) this data at either the Home or Crime PSA level
- Join to the [GeoJSON](https://github.com/drewbo/dc-juvenile/tree/master/data/geo) in the technology of your choice (QGIS for now)
- Normalize by population (or juvenile population) where appropriate

### Screenshots

Juvenile arrests by Crime PSA:

![Juvenile arrests by Crime PSA](https://raw.githubusercontent.com/drewbo/dc-juvenile/master/screenshots/juvenile-arrests-by-crime-PSA.png)

Juvenile arrests by Home PSA, normalized by Under-18 Population:

![Juvenile arrests by Home PSA, normalized by Under-18 Population](https://raw.githubusercontent.com/drewbo/dc-juvenile/master/screenshots/juvenile-arrests-by-home-PSA.png)

### To-do

- Combine with information on juveniles living in poverty
- Create an interactive
- Do analysis
