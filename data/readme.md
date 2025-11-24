# Share of the population with access to clean fuels for cooking - Data package

This data package contains the data that powers the chart ["Share of the population with access to clean fuels for cooking"](https://ourworldindata.org/grapher/access-to-clean-fuels-and-technologies-for-cooking?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 24, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Proportion of population with primary reliance on clean fuels and technologies for cooking (%) - Residence area type: Total
Proportion of population with primary reliance on clean fuels and technology is calculated as the number of people using clean fuels and technologies for cooking, heating and lighting divided by total population reporting that any cooking, heating or lighting, expressed as percentage. “Clean” is defined by the emission rate targets and specific fuel recommendations (i.e. against unprocessed coal and kerosene) included in the normative guidance WHO guidelines for indoor air quality: household fuel combustion.
Last updated: May 19, 2025  
Next update: May 2026  
Date range: 1990–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization - Global Health Observatory (2025) – processed by Our World in Data

#### Full citation
World Health Organization - Global Health Observatory (2025) – processed by Our World in Data. “Proportion of population with primary reliance on clean fuels and technologies for cooking (%) - Residence area type: Total” [dataset]. World Health Organization, “Global Health Observatory” [original data].
Source: World Health Organization - Global Health Observatory (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization - Global Health Observatory (2025)?
#### Rationale
The use of solid fuels and kerosene in households is associated with increased mortality from acute lower respiratory, chronic obstructive pulmonary disease, stroke, ischaemic heart disease, and lung cancer.

#### Definition
Proportion of population with primary reliance on clean fuels and technology is calculated as the number of people using clean fuels and technologies for cooking, heating and lighting divided by total population reporting that any cooking, heating or lighting, expressed as percentage. “Clean” is defined by the emission rate targets and specific fuel recommendations (i.e. against unprocessed coal and kerosene) included in the normative guidance WHO guidelines for indoor air quality: household fuel combustion.

#### Method of measurement
The indicator is calculated as the number of people using clean fuels and technologies divided by total population, expressed as a percentage. Based on the recommendations included in the WHO Guidelines for indoor air quality: household fuel combustion, the fuels and technologies that are considered clean include electricity, natural gas, liquified petroleum gas, biogas, ethanol, and solar.

#### Method of estimation
A non-parametrical statistical model based on household survey data and time as inputs is applied to derive estimates. For further information on the model, see Stoner O et al, 2020: Global Household Energy Model: A Multivariate Hierarchical Approach to Estimating Trends in the Use of Polluting and Clean Fuels for Cooking (see link below). Input data for the model is found in the WHO Household Energy Database. This database compiles data from nationally-representative surveys and censuses that provide estimates of primary cooking fuels and technologies. In cases where estimates of the population not cooking at home, with missing data or cooking with "other" fuels are provided, these populations are removed from the denominator for estimation purposes. The population data source is the 2018 Revision of World Urbanization Prospects (see link below).

### Source

#### World Health Organization – Global Health Observatory
Retrieved on: 2025-05-19  
Retrieved from: https://www.who.int/data/gho  


    