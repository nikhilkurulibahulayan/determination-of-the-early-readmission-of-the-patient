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

### Variables Table
* Variable Name	Role	Type	Demographic	Description	Units	Missing Values
* encounter_id	ID			Unique identifier of an encounter		no
* patient_nbr	ID			Unique identifier of a patient		no
* race	Feature	Categorical	Race	Values: Caucasian, Asian, African American, Hispanic, and other		yes
* gender	Feature	Categorical	Gender	Values: male, female, and unknown/invalid		no
* age	Feature	Categorical	Age	Grouped in 10-year intervals: [0, 10), [10, 20),..., [90, 100)		no
* weight	Feature	Categorical		Weight in pounds.		yes
* admission_type_id	Feature	Categorical		Integer identifier corresponding to 9 distinct values, for example, emergency, urgent, elective, newborn, and not available		no
* discharge_disposition_id	Feature	Categorical		Integer identifier corresponding to 29 distinct values, for example, discharged to home, expired, and not available		no
* admission_source_id	Feature	Categorical		Integer identifier corresponding to 21 distinct values, for example, physician referral, emergency room, and transfer from a hospital		no
time_in_hospital	Feature	Integer		Integer number of days between admission and discharge		no
