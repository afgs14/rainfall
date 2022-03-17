# rainfall
This repository contains an analysis of monthly rainfall patterns in Melbourne (Australia) and Oxford (UK) from 1855-2015

To run this analysis use the following commands:

```
Rscript src/combine-data.R
Rscript src/make-plot.R
```

The input data is in data and the results are in out

Melbourne climate statistics:
The data was obtained from the Bureau of Meteorology:
http://www.bom.gov.au/climate/averages/tables/cw_086071.shtml

Oxford climate statistics:
The data was obtained from the Met Office:
https://www.metoffice.gov.uk/pub/data/weather/uk/climate/stationdata/oxforddata.txt

The analysis was run in R version 4.1.2
