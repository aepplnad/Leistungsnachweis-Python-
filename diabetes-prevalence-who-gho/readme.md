# Prevalence rate of diabetes in adults - Data package

This data package contains the data that powers the chart ["Prevalence rate of diabetes in adults"](https://ourworldindata.org/grapher/diabetes-prevalence-who-gho?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 26, 2026.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV structure

Each row is an observation for an entity (usually a country or region) at a timepoint.

- "Entity" — the name of the entity, e.g. "United States".
- "Code" — our internal entity code. For most countries this is the [ISO alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code, e.g. "USA"; historical and other non-standard entities get a custom code.
- "Year" or "Day" — the timepoint. Annual data has a "Year" column holding an integer year; otherwise a "Day" column holds a date string in the form "YYYY-MM-DD".
- The final column is the data column — the time series that powers the chart. Downloaded with the "full data" option it corresponds to the time series below; with "only selected data visible in the chart" it is transformed depending on the chart type, so the correspondence may be less direct.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc.

## How we process data at Our World in Data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stitch together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

Preparing this data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/).

## Detailed information about the data


### Raised fasting blood glucose (>=7.0 mmol/L) (age-standardized estimate) - Sex: both sexes - Age group: 18+  years of age
Last updated: May 22, 2026  
Next expected update: May 2027  
Date range: 1980–2014  
Source: World Health Organization – Global Health Observatory (2026) – with minor processing by Our World in Data  

#### How to cite this data

World Health Organization – Global Health Observatory (2026) – with minor processing by Our World in Data

#### How this data is described by its producers
#### Rationale
To assess the level of treatment with glucose-lowering medication among people with diabetes

#### Definition
Percentage of people aged ≥ 30 years with diabetes who are currently using glucose-lowering medication. Diabetes is defined as FPG ≥7.0 mmol/L, or HbA1c ≥6.5%, or taking medication for diabetes.

#### Method of measurement
Estimated from population-based surveys as follows: **Numerator:** number of adults aged ≥ 30 years with diabetes who are currently taking glucose-lowering medication **Denominator:** total number of adults aged ≥ 30 years with diabetes, defined as fasting plasma glucose (FPG) ≥7.0 mmol/L, glycated haemoglobin (HbA1c) ≥6.5%, or taking medication for diabetes. Whether a person is taking glucose-lowering medication for diabetes is assessed using survey-specific questions worded as variations of “are you currently taking medication for diabetes or high blood sugar?”; or the combination of “do you currently inject/use insulin for diabetes?” and “are you currently taking any medicines, tablets, or pills for diabetes?”; or using information gathered on prescribed medicines.

#### Method of estimation
Population-representative studies with measurements of fasting glucose and/or glycated haemoglobin (HbA1c), and information on diabetes treatment were compiled. Data were pooled using a Bayesian hierarchical meta-regression model to estimate diabetes treatment coverage. Age-standardized estimates are produced by weighting the age-specific estimates by the product of the WHO Standard Population fraction and the age-specific prevalence of diabetes. Full details of input data and methods are available at: NCD Risk Factor Collaboration (NCD-RisC). Worldwide trends in diabetes prevalence and treatment from 1990 to 2022: a pooled analysis of 1108 population-representative studies with 141 million participants. Lancet 2024. Available online at: https://doi.org/10.1016/S0140-6736(24)02317-1


## Sources

These are the sources behind the data in this package. Each time series above names the ones it draws on in its citation.

### World Health Organization – Global Health Observatory

The GHO data repository is WHO's gateway to health-related statistics for its 194 Member States. It provides access to over 1000 indicators on priority health topics including mortality and burden of diseases, the Millennium Development Goals (child nutrition, child health, maternal and reproductive health, immunization, HIV/AIDS, tuberculosis, malaria, neglected diseases, water and sanitation), non communicable diseases and risk factors, epidemic-prone diseases, health systems, environmental health, violence and injuries, equity among others.

Producer: World Health Organization  
Published: 2026-05-28  
Retrieved on: 2026-05-22  
Retrieved from: https://www.who.int/data/gho  
License: CC BY-NC-SA 4.0 (https://www.who.int/about/policies/publishing/copyright)  

Citation: World Health Organization. 2026. Global Health Observatory data repository. http://www.who.int/gho/en/.

    