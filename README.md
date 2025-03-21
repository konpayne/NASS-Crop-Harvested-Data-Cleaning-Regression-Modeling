### NASS-Crop-Planted-Harvested-Data-Cleaning

Compiled datatsets of various crops' planted and harvested acres from the USDA-National Agricultural Statistics Service (NASS) for later use in small area estimation models with clustering techniques. Linear regression models were built using NASS harvested crop acres in conjunction with either the same data from the Farm Service Agency (FSA) or Risk Management Agency (RMA). 

## Description

The raw data was pulled from the United States Department of Agriculture (USDA) - National Agricultural Statistics Service (NASS) in order to create datasets containing the harvested acres of corn from Iowa from 2006 to 2023. Both the USDA - Risk Management Agency (RMA) and USDA - Farm Service Agency (FSA) followed the same process of query and data cleaning. The goal of this project was to obtain regression models with possible clustering effects to train small area estimation model, so clustering was the desired pattern from the plots of NASS vs. FSA or RMA. A sample year (2022) was used to determine if these datsets were suitable for the later project, however the corn datasets were determined to show strong linear trends with no clustering, so later in the code I tested some samples from other states and crops (cotton and soybean). 

### Dependencies

Install only through Rstudio 

## Installing

Datasets can be downloaded from the following links: 
USDA-NASS: https://www.nass.usda.gov/Quick_Stats/

FSA: https://www.fsa.usda.gov/news-room/efoia/electronic-reading-room/frequently-requested-information/crop-acreage-data/index

RMA: https://www.rma.usda.gov/SummaryOfBusiness/StateCountyCrop

RMA Data Dictionary: https://www.rma.usda.gov/-/media/RMA/SCC-SOB/Type-Practice-Unit/sobtpu_allyears-pdf.ashx?la=en

## Help

Email for issues and I can help, but if the data is imported properly there should be no issues

## Authors

Konnor Payne  
konnormpayne@gmail.com
