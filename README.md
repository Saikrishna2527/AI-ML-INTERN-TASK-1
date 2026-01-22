
1. Titanic Dataset Analysis (891 rows × 12 columns)

   LOADED dataset using pandas.read_csv()
   DISPLAYED first 5 rows (head()) & last 5 rows (tail())
   
 IDENTIFIED data types:
   NUMERICAL: Age, Fare, SibSp, Parch
   CATEGORICAL: Sex, Embarked, Cabin, Ticket
   ORDINAL: Pclass (1>2>3 class ranking)

BINARY: Survived(0/1), Sex(male/female)
 FOUND TARGET: Survived (binary classification)
 CHECKED missing values: Age(177), Cabin(687)
 ASSESSED ML suitability: ✓ SUITABLE (891 rows perfect size)



2. Students Performance Dataset Analysis

   DEMONSTRATED same analysis process
  EXPECTED structure: 1000 rows × 8 columns.

IDENTIFIED data types:
  NUMERICAL: math score, reading score, writing score
  CATEGORICAL: race/ethnicity, lunch, test prep

BINARY: gender
   TARGET: Scores (regression problem)
   STATUS: Clean data, ML perfect

Key Observations:

TITANIC:
├── 20% Age missing → Impute with median
├── 77% Cabin missing → Drop column
├── Encode Sex, Pclass, Embarked for ML
└── Binary classification ready

STUDENTS:
├── Clean dataset (0% missing)
├── Perfect for regression modeling
└── One-hot encode categories

ML READINESS:

Titanic: Binary Classification.
Students: Multi-target Regression.
Both: Adequate size (>500 rows)
Preprocessing identified.




