# Enhanced Assesment of Seasonal Hazards

## Introduction

Use historical data from multiple databases on the recorded impacts (e.g., number of people passed away, number of people displaced, number of homes
damaged or destroyed, etc.) of past events to disaggregate flood and storm risks by country by month -- or per Admin2 area per month. Will involve
extracting data from the different databases, putting it into one or more data frames, then doing an analysis of the data using Python and sharing the
documentation and results with the IFRC colleagues so that it can presented on the IFRC's public-facing GO platform. 

## Source Code

The following repositories contain all the code required to complete the analysis, it consists of 4 packages:

- [Data Downloader](https://github.com/UCL-IFRC-IXN4/data_downloader.git)
- [Data Shaper](https://github.com/UCL-IFRC-IXN4/data-shaper.git)
- [Data Processor](https://github.com/UCL-IFRC-IXN4/data-processor.git)
- [Data Visualiser](https://github.com/UCL-IFRC-IXN4/data-downloader.git)

For best experience code should be downloaded into the following structure:

```bash
/UCL-IFRC-IXN4<br />
|──── Data/<br />
|────── DI-data/<br />
|────── IDMC-data<br />
|────── EMDAT-data<br />
|────── IFRC-data<br />
|──── Data Downloader/<br />
|────── src/<br />
|────── transl_dict/<br />
|──── Data Shaper/<br />
|────── src/<br />
|──── Data Processor/<br />
|────── src/<br />
|──── Data Visualiser/<br />
|────── src/<br />
```
