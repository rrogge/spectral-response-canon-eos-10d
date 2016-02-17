# Spectral Response of Canon EOS 10D

You may want to check out the [RPubs document](http://rpubs.com/rrogge/spectral-response-canon-eos-10d) when you don't want to run the code on your own but only want to lookup the results.

The easiest way to run the project is to load "Spectral Resonse Canon EOS 10D.Rmd" into R Studio an knit it. 

## Codebook

### Input File "Atmosphere Transmission.csv"

This files contain the atmosphere transmission values

1. Wavelength [nm]
1. Transmission [0.0 - 1.0]

### Input file "Wehrli1985.csv"

This file contains the solar reference spectrum without any atmosphere (AM0)

1. Wavelength [nm]
1. Irradiance [W/m^2/nm]
1. Cumulative integral of irradiance [W/m^2]