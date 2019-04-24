# CS-363D-Project
Darwin project for CS 363D Spring Sp'19, Group 13

Write-up: https://v2.overleaf.com/6158614986rjsbwhnjwnrd

Files:

- Darwin Project.ipynb: Here we tried predicting the conscientious vaccination exemption rate based on sociodemographic variables for Texas counties. Along the way, we found what variables were considered the most important for determining the rate. This notebook shows that process.

- data/exemptions.csv: The conscientious vaccination exemption rates for Texas counties from 2010-2018. These were used as the "classes" for our model.
- data/\*.csv: The features we used to flesh out the dataset, which initially just contained the vaccination exemption rates. Sociodemographic data for the counties of Texas.
- data/data\_to\_remove.txt: What features we deemed weren't important or relevant for building our model. All of the features in this file were dropped from our final dataset.
- data/remove\_col\_names.txt: A differently formatted version of the above file. This is in a simpler form that can be read into Python and used more easily.

NOTE: All of the intermediate CSVs that were used for data analysis are generated and contained within the Jupyter notebook. Thus only the original CSVs are provided here.