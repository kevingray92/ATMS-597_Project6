# ATMS-597_Project6

Using ASOS data from stations at Madison, Oshkosh, and Green Bay, WI, and Buffalo, NY, predict the precipitation type (liquid, freezing rain, or frozen) using a logistic regression model and neural network.

GetDataProject6.ipynb is used to download and parse the METAR files from the stations. This file creates the following .csv files:
decoded_metar_KBUF.zip
decoded_metar_KGRB.csv
decoded_metar_KMSN.csv
decoded_metar_KOSH.csv

Project6.ipynb contains the code that sets up the logistic regression model (used as our baseline model) and the neural network. Accurace of the models is output along with accuracy over time plots for the neural network and confusion matrices for both models.
