# Predict the Success of Bank telemarketing Campaign

### Dataset Description
The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

#### Files
- **train.csv** - the training set (use this as a complete dataset for model training, create train/test splits from this dataset)
- **test.csv** - the test set (use this only for making predictions for submission)
- **sample_submission.csv** - a sample submission file in the correct format

#### Input variables
- **last contact date**: last contact date
- **age** (numeric)
- **job** : type of job
- **marital** : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
- **education** (categorical: "unknown","secondary","primary","tertiary")
- **default**: has credit in default? (binary: "yes","no")
- **balance**: average yearly balance, in euros (numeric)
- **housing**: has housing loan? (binary: "yes","no")
- **loan**: has personal loan? (binary: "yes","no")
- **contact**: contact communication type (categorical: "unknown","telephone","cellular")
- **duration**: last contact duration, in seconds (numeric)
- **campaign**: number of contacts performed during this campaign and for this client (numeric, includes last contact)
- **pdays**: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
- **previous**: number of contacts performed before this campaign and for this client (numeric)
- **poutcome**: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

#### Output variable (desired target)
- **target**: has the client subscribed a term deposit? (binary: "yes","no")
