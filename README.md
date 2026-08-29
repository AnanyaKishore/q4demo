This is the private repository shared between

- Ananya Kishore (DA24B035)
- Aramati Chiru Thejaswi (DA24B036)

for question 4 of assignment 1 (DA3408). 

## Partner A (DA24B035):

I assumed the role of partner A.

I have recorded the metrics, parameters, the git commit and the model training the iris dataset on a Random Forest Classifier as can be seen below:

![Iris RFC, Partner A](MLflow_PartnerA.png)

## Partner B (DA24B036):
I assumed the role of Partner B and reproduced Partner A's result using only the permitted commands: 
git clone, git checkout <commit>, dvc checkout, mamba env create -f environment.yml, and rerunning the script 

Steps performed:

Cloned the repository and checked out commit 7feab49 (Partner A's latest commit, containing the trained model, versioned dataset, and environment).
Retrieved the versioned Iris dataset using dvc pull and dvc checkout.
Recreated the exact environment using mamba env create -f environment.yml.
Reran question_4.ipynb 
Reproduced MLflow run: brawny-squid-212 (Run ID: 7328e02c7a02428fb32d48ff33c94456), which auto-logged a git_commit tag matching 7feab49, confirming the exact commit was used.
Results produced:
<img width="1853" height="798" alt="MLflow_PartnerB" src="https://github.com/user-attachments/assets/7aa37f1b-58b1-49ad-a949-ef501ff831f4" />

