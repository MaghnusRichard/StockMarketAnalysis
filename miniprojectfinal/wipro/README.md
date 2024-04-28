## Instructions

### Step 1

Run the sentiment analysis file `sentimentanalysislstm.ipynb`.

This will perform two main tasks:

- It will create a JSON file named `<stockname>lstmhealines.json` (e.g., `wiprolstmheadlines.json`). This file will contain news headlines in JSON format, which is needed for sentiment analysis.

- It will run sentiment analysis and outputs the results into a new JSON file named `<stockname>daily_scores.json` (e.g., `wiprodaily_scores.json`).

### Step 2

Run the LSTM data preparation file `lstmdata_prep.ipynb`.

This will merge the news sentiment and stock table together into a new CSV file named `<stock>_merged.csv` (e.g., `wipro_merged.csv`).

### Step 3

Run the LSTM training file `<stockname>lstmtraining.ipynb`. (eg: `wiprolstmtraining.ipynb` ).

- this will do the create the lstm model and do prediction
- output two graphs and a final table with the original and predicted open prices.

if all the files mentioned in step1 and step2 are there in your folder

inputdatafiles/wipronews.csv
inputdatafiles/NFY_2013-01-01_to_2024_01-01.csv

wiprodaily_scores.json
wiprolstmheadlines.json

you can direcly run the step3
