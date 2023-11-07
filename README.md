# CANSSI-FrenchTrot
Welcome to Cynthia &amp; Juliette's submission to the CANSSI French Trot Horse Racing Forecasting Competition

&nbsp;

**List of files**:
- **explanatory_notebook.ipynb** summarizes our process and explains our engineered features.
- **predictions.csv** contains the winprobability variable for the 3-month holdout test period, along with the predicted class label and ground truth (WIN=1 or 0).
- **Final-Model.ipynb** is the notebook to run to obtain the predictions.csv result.
- **Final-Model_for-new-data.ipynb** is the notebook to run to test the model on new data.
    - The new dataset is to be added where indicated, and it will be used as the testing set. The output will be stored in a newdata_predictions.csv file.

&nsbp;

An entry consists of 
- an end-to-end reproducible model that the judges can run themselves (after they add the data);
- an explanatory notebook talking about your submission; and
- forecasts for the three-month holdout test period. For every observation, please create a variable winprobability, which is what you are trying to predict. As a reminder, by RaceID this winprobability should sum to 1.0

