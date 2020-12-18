# ML-project
The aim of this project is to predict the pleasantness of smell of molecules. 

Here is the organisation of our project:
```
ML-project                         Comments:
│   README.md                       │      
│                                   │   
└───Data                            │
│   │  ImportanceBoost.csv          │  # This is data that we got in boost filed and used in look test data for visualization
│   │  sampleSubmission.csv         │  # A test to figure out how to submit
│   │  test_data.csv                │   
│   │  training_data.csv            │                      
│                                   │
└───src                             │
│   │                               │
│   └───Linear methods              │  
│   │     │  Generalize Reg.ipnyb   │  # exploration of different regularization
│   │     │  Lasso.ipynb            │  # first Lasso exploration 
│   │     │  LM.ipynb               │  # first exploration of linear regression and subset selection
│   │                               │  
│   └───Non linear methods          │  # 
│   │     │  Boosting.ipnyb         │  #
│   │     │  NN.ipynb               │  #
│   │     │  RF2.ipynb              │  # continuity of the Tree and RF file
│   │     │  Tree and RF.ipynb      │  #
│   │                               │
│   └───visualize data              │
│         │  Custom.ipynb           │  # Our best model and submission ("innovative approach" in the rapport)
│         │  Look test data.ipynb   │  # Important data plotted
│         │  PCA_test.ipynb         │  # PCA visualization and PCR test
│                                   │  
└───Submission                      │
    │  Our submissions              │       
```
The usage is very simple: run the cells in order.

##### IMPORTANT 
We sometimes wrote comments like #Do not run in certain cells: it means that these cells that will run for a very long time (Typically large CVs).

### Version and libraries
- keras
- MASS
- caret
- RandomForest
- ggfortify
- leaps
- glmnet
- tidymodels
- xgboost
- Matrix
- plotly
- pls
- tree

We used R version 3.6.1 (2019-07-05) and coded exclusively on anaconda.