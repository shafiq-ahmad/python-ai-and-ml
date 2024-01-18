# Types of ML

- Supervised
  - Works undersupervistion
  - Labeled data
- Unsupervised / Clustring
  - No labeled data
- Simisupervised
  - Mixed above
- Reinforcement
  - Hit and trail learning
  - learn from mistakes

## Machine learning steps/flow

1. Define the problem
2. Data collection
3. Data pre processing
4. Choose the model
5. Split the data (train/testing)
6. Evaluate the model
7. Hyper parmeter tuning
8. Cross validation (switch dataset for testing the model)
9. Model finalization: test on real dataset
10. Deploy the model

Terms

- Training data: used to train the model
- Testing data: used to test the performance of the model
- Features: individual properties that used as input for variables in model. and labels are output
- Model: a specific representation learned from data, based on which predictions or decisions are made.

Underfitting / Overfitting
Work on generalized model. that was taken from 

1. Overfitting: 
   - example: model perform best on trained data. and poor on unknown data.
2. Underfitting: 
   - example: it is too general.
model must be in between of above.

Python library

- scikit learn
- tnsorflow / keras
- pytorch
- nltk
- opencv

Scikit library

- Preprocessing
- Features


## Installation

Create a new conda env 'python_ml'

pachages
pandas, numpy, matplotlib
seaborn
scipy
scikit-learnjupyter
openpyxl
plotly

VS code or miniconda commandline

`conda create -n python_ml`

`conda activate python_ml`

`conda install python=3.11`

`pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter openpyxl plotly`

Choose env in VS code run any code to test env.

## Data Pre processing

### Data cleaning

> Tidy
> Discord data \
> Missing values imputations\
> New columns / Feature engineering\
> Smoothing noise data\
> Outliers

### Data Integration

> Combine data taken from different suorces\
> Remove duplicates\
> Merge data\
> Data consolidation

### Data transformation

> Scaling data\
> Normalize data\
> Agregation data / combining two or more features\
> Data generalization

### Data Reduction

> Reduce input columns that are not important\
> Numorosity reduction: data encoding convert categorial data to number / code\
> Data compression

### Data discretization

> convert data to nominal variables. numerical to categorical data\
> Binning\
> Clustering

## Data Inconsistencies

Inconsistence Format
Example: using different date formats

Inconsistent Naming convension
Example country name: US, USA, United State of America

Typographical errors

Duplications

Contradictory data

## Outliers

Change in normal data or different then others.

Different names

- Outliers
- Deviants
- Abormalities
- Anomalous points
- Abberrat

Types

- Univariant: in one variable
- Multivariant:
- Global outliers
- Point outliers
- Local outliers
- Contextual outliers
- Collective outliers
- Recurrent outliers
- Periodic outliers

Causes of outliers

Data entry error
Measurement error
Experimental error
Intentional outliers
Data Processing error
Sampling error
Natural outliers

Why important
Hidden clues
Data quality
Impact
Better model/decision
Visualization

Methods to remove

Z-Score
remove out side -3 to 3

IQR method
which is 25% to 75% of data
IQR*1.5 outsize is outliers
Q1-IQR*1.5
Q3+IQR*1.5

KMeans methods

Data Merging
when data taken from various sources

using pandas lib
pd.merge(data1, data2, on='id', how='inner')

Data Concatenation

pd.concat([data1, data2], axis=1)

## Transforming / scaling linear data

- Min/max scalar: 0 - 1
- Max abs scalar: -1 to 1
- Standard scalar: 3 to -3

before adoptin a method check if AI model support negitive values

scikit learn online
standardization method and map of functions

## Standard Scaling
