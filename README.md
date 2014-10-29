Data on Juvenile Arrests in the DC Area (and related info)
===

### Data

The pipeline:

- Raw data comes from [here](http://mpdc.dc.gov/node/208852)
- These are stored in the [pdf folder]()
- Use [Tabula](http://tabula.nerdpower.org/) to convert to [raw csv]
- [Aggregate this]() at either the Home or Crime PSA level
- Join to the [GeoJSON]() in the technology of your choice (QGIS for now)
- Normalize by population (or juvenile population) where appropriate

### Screenshots

Juvenile arrests by Crime PSA:

![Juvenile arrests by Crime PSA]()

Juvenile arrests by Home PSA, normalized by Under-18 Population:

![Juvenile arrests by Home PSA, normalized by Under-18 Population]()

### To-do

- Combine with information on juveniles living in poverty
- Create an interactive
- Do analysis
