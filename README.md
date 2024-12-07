This repository represents Tim's work for CF's Crypto Trading Data Science Assessment.

The repository contains the following scripts:

1. Main.ipynb:              
The entire assessment has been performed in this Jupyter Notebook.

The repository contains the following folders:

1. Matteos Datasets:        
This folder contains the original datasets Matteo sent me via email.

2. Tim Binance API:         
This folder contains a trading dataset which I retrieved from Binance via an API.

3. Cleaned Datasets:        
This folder contains the cleaned versions of Matteo's datasets.

4. 1h Reampled Datasets:    
This folder contains Matteo's datasets resampled to an hourly interval.

5. Interpolated Datasets:   
Since the two Kraken datasets had 3 respectively 4 missing values (2min interval instead of 1min),
I created two new datasets out of them which linearly interpolated the missing timestamps.

6. Calculated Datasets:     
This folder contains a BTC and an ETH dataset (based on the cleaned version of Matteo's Binance datasets).
These two datasets were used to do all sorts of calculations and visualizations in the assessment.

7. Figures:                 
This folder contains all figures produced by the main.ipynb script.

