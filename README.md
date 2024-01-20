# README

## Project Title: Analysis On The On-Time Reliability of Airlines Departing From IAD, BWI, or DCA


### Overview:

This repo provides information regarding data, methodology, and other contexual information regarding the following __[post](https://x.com/sebbystats/status/1748206329246671288?s=20)__ on X: . The post includes a graphic that showcases the on-time reliability of airlines. An on-time reliability score is calculated based on flight delay and cancellation rates, with the later being penalized more heavily. 


### Data Sources:

1. __[On-Time : Marketing Carrier On-Time Performance](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr)__
   - Downloaded and unzipped data can be found in ./data. This data was downloaded from BTS on January 11, 2024.
   - Analysis was based on data from January 2022 - October 2023 (latest available data at the time). 


### Usage Instructions:

1. Download data

2. Run airline_delays_V2.1.ipynb, which will read in datasets above, and output data/airline_delays_output.csv.

3. Visualize in platform of your choice. 
