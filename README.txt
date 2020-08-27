We analyse US gun murder data collected by the FBI.

download-data.R - downloads the csv file to the 'data' directory

wrangle-data.R - creates a derived (mutate) data set of murders.csv and 
                 saves as R object in 'rda' directory as murders.rda

analysis.R - loads murders.rda and generates a barplot and saves it to
             the 'figs' directory as barplot.png