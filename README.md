### Dataset
The dataset used in this project is accessible here (https://drive.google.com/file/d/1UIAePf5Yz069rNZ_PkcLl5zXeXV-V4IK/view?usp=sharing).
Key Components
### Loading and Preprocessing:

Loaded the dataset and performed necessary preprocessing steps, including text cleaning, tokenization, and stopword removal.
Techniques such as stemming and lemmatization were applied to refine the text data.
### Basic EDAS:

Adopted Basic EDA Techniques to provide an overall information and the statistical overview of the data set.
### Visualization and trend analysis:

#### Various Visualization Tecniques used:
* Count Plot
* boxplot
* pairplot -histogram
#### Outlier Removal:

Cleaned Data for better performance.
#### Feature Engineering:

Converted all object and boolean columns to int and fload using label encoding
#### Requirements
* Python 3.x
* NLTK
* Scikit-learn
* Pandas
* NumPy
#### Aim
Identify key patterns and relationships within the data. Inform the development of predictive models. Evaluate the effectiveness of different features in driving conversions.

Dataset Information
What do the instances in this dataset represent?

The instances represent hospitalized patient records diagnosed with diabetes.

Are there recommended data splits?

No recommendation. The standard train-test split could be used. Can use three-way holdout split (i.e., train-validation-test) when doing model selection.

Does the dataset contain data that might be considered sensitive in any way?

Yes. The dataset contains information about the age, gender, and race of the patients.

### Dataset Information

The dataset represents ten years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.
* (1)	It is an inpatient encounter (a hospital admission).
* (2)	It is a diabetic encounter, that is, one during which any kind of diabetes was entered into the system as a diagnosis.
* (3)	The length of stay was at least 1 day and at most 14 days.
* (4)	Laboratory tests were performed during the encounter.
* (5)	Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab tests performed, HbA1c test result, diagnosis, number of medications, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

