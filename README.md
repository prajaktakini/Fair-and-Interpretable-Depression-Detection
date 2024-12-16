# Project Overview
Traditional machine learning models for depression classification lack interpretability 

We propose a neuro symbolic model that combines the strengths of deep learning models with the transparency of rule-based systems.

# Rule Based Model Architecture
![Rule Based Architecture](./images/rule_based.png)

# Neuro-Symbolic Loss Calculation
![neuro-symbolic loss](./images/NeuroSymbolic_Loss.png)

# Experimental Results
![results](./images/Results.png)


# Rule Based System: Code Re-run

### Go to implementation/rule-based/adjective/

In the file : RuleBasedSystem_DepressionAnalysis.ipynb

Search for the following comment and change the file address:

1. /## Change File location 1 

change file path to : ./datasets/DAIC demographc data.xlsx

2. /## Change File location 2

change file path to : ./datasets/DAIC demographc data.xlsx

3. /## Change File location 3

change file path to : ./datasets/train_split_Depression_AVEC2017.csv

4. /## Change File location 4

change file path to : ./datasets/test_split_Depression_AVEC2017.csv

5. /## Change Folder location 1

change folder path to : ./datasets/Dataset

6. /## Change File location 5

change file path to :   ./implementation/rule-based/adjective/embeddings/adjective_embeddings.pkl

After doing these changes, run the file to execute the code.


You will get a plot of Balanced Accuracy against all the combinations of t1 and t2 provided.

If you wish to change the values of t1 and t2, search for the list "parameters", and update the list as per your interest.

# Limitations Analysis

### Go to implementation/utils/

In the file : LimitationsAnalysis.ipynb

Search for the following comment and change the file address:

1. /## Change File location 1 

change file path to : ./datasets/DAIC demographc data.xlsx

2. /## Change File location 2

change file path to : ./datasets/train_split_Depression_AVEC2017.csv

3. /## Change File location 3

change file path to : ./datasets/test_split_Depression_AVEC2017.csv

4. /## Change Folder location 1

change folder path to : ./datasets/Dataset

5. /## Change File location 4

change file path to : ./datasets/depression_dataset_reddit_cleaned.csv

After doing these changes, run the file to execute the code to get the Noun, Adjective and Verbs count overlap between the Interview transcripts and SentenceBank dataset.


