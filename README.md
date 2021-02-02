CA01
# Name

India Air Quality analysis

## Description

This data is released by the Ministry of Environment and Forests and Central Pollution
Control Board of India under the National Data Sharing and Accessibility Policy
(NDSAP), using this one can explore India’s air pollution levels at a more granular scale.


## Dataset Information
The dataset has 13 columns which are:

• stn_code: Station Code

• sampling_date: Date of sampling (note how this is formatted)

• state: State

• location: Location of recording

• agency: Agency

• type: Type of area

• so2: Sulphur dioxide (µg/m3)

• no2: Nitrogen dioxide (µg/m3)

• rspm: Respirable Suspended Particulate Matter (µg/m3)

• spm: Suspended Particulate Matter (µg/m3)

• location_monitoring_station: Location of data collection

• pm2_5: PSI 2.5 (µg/m3)

• date: Date of sampling


SPM, RSPM, PM2.5 values are the parameters used to measure the quality of air based
on the number of particles present in it. Using these values, we are going to identify the
air quality over the period of time in different states of India

## Usage
packages :
numpy, pandas, matplotlib.pyplot, datetime


