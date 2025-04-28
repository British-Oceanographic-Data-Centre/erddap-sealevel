# erddap-sealevel
These are the required files for making a sea level erddap

## datasets
This is the root folder for all the data your datasets are loading.

## xml
This is the root folder for any xml you want ERDDAP to read.

## usage
This is being used to load data into a cloud-native erddap federation, we are basing this work of the fab starter in [erddap-helm](https://github.com/kumulustech/erddap-helm). The init container is extended to also pull the data and datasets.xml from this repo as well as the [gold-standard] https://ioos.github.io/erddap-gold-standard/. 
