# The Data-Driven Guide to Bangkok Prostitutes

This repository is a sandbox for a [Medium article](https://medium.com/p/af965fc55e4b/). You can also read the article [here](http://cstorm125.github.io/curry)

## Codebook
The ```curry dataset```  contains 693 observations of prostitues operating in Bangkok and nearby areas. The data were scraped from an online listing on May 21, 2016 and stored as XML in the ```data``` folder. The raw dataset (```big.rds```) contains such features as name, gender, age, price, range of services and locations, physical measurements, view counts, number of pictures, and contacts of all prostitutes (22 features in total). Furthermore, the processed dataset (```features.rds```) augmented such features as location clusters, body measurement ratios, and view counts per day listed, as well as transformed some features such as location and range of services for machine learning purposes (58 features in total). This report explains the process.

## Processed
This folder contains processed files of the ```curry dataset``` as described in the codebook.
