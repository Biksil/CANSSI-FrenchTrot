# CANSSI-FrenchTrot
Welcome to Cynthia &amp; Juliette's submission to the CANSSI French Trot Horse Racing Forecasting Competition

&nbsp;

**List of files**:
- **explanatory_notebook.ipynb** summarizes our process and explains our engineered features.
- **predictions.parquet** contains the winprobability variable for the 3-month holdout test period, along with the predicted class label and ground truth (WIN=1 or 0).
- **Final-Model.ipynb** is the notebook to run to obtain the predictions.csv result.
- **Final-Model_for-new-data.ipynb** is the notebook to run to test the model on new data.
    - The new dataset is to be added where indicated, and it will be used as the testing set. The output will be stored in a newdata_predictions.parquet file.
