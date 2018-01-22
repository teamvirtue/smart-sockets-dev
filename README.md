# smart-sockets-dev
This repository contains the Jupyter notebooks written for the VIRTUe smart system. They contain snippets of code which can be used to create a software application which sends feedback notifications. The notifications are designed to make the user live a more sustainable lifestyle. More information about this system can be found here:
https://jortpolderdijk.github.io/VIRTUe-docs/ 

## DRED
To simulate the electricity being measured in a house, the DRED dataset is user. The dataset is provided by:
http://www.st.ewi.tudelft.nl/~akshay/dred/ 
This Jupyter notebook displays the dataset and what can be done with it.

## PV CONTROL
This is a proof of concept for using the GFS weather model to predict how much energy will be generated. This can be used to generate notifications about electrical appliance use.

## Custom notificiations
The following Jupyter notebook displays how energy use data and PV generation data can be used to determine electrical opportunity hours. This is then used to generate notifications based on the five most consuming appliance.
