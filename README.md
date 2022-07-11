# Heart-Disease-Predictor

### Hello
This is my take on the infamous heart disease dataset from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. The original datasheet consisted of 76 attributes but most of the research publishers make use of the main 14 attributes. The beginning 13 are information based on the patients reports and life, whereas the last one is a binary series denoting wether 1 - patient might have heart issues or 0 - patient might not have heart issues.

My program has all been done in Jupyter Notebooks specifically in my case I have used the VSCode Extension of the same, nevertheless it should work in a normal .ipynb notebook as well

The model heart disease predictor is a machine learning model which has taken and studied data from the heart.csv and formulated its own function wherein we input the paramteres and get an output of wether we might ot might not have heart disease. To take in the paramteres I have made use of IPyWidgets available in jupyter to interactively take in the values from the user in an easier rather than inputting it manually at each step.

#### Preview of the working: https://drive.google.com/file/d/1OKOaFlnEywPG9UdZRCrvbTM5BoFmPCO6/view?usp=sharing

### Prerequisites Required:
* Python 3.10
* Scikit-Learn
* Jupyter Notebook (or its extensions)
* Pandas
* NumPy
* Joblib
* IPyWidgets

### Detailed info on the 14 attributes:
* age - age in years
* sex - sex (1 = male; 0 = female)
* cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 = asymptomatic)
* trestbps - resting blood pressure (in mm Hg on admission to the hospital)
* chol - serum cholestoral in mg/dl
* fbs - fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
* restecg - resting electrocardiographic results (0 = normal; 1 = having ST-T; 2 = hypertrophy)
* thalach - maximum heart rate achieved
* exang - exercise induced angina (1 = yes; 0 = no)
* oldpeak - ST depression induced by exercise relative to rest
* slope - the slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 = downsloping)
* ca - number of major vessels (0-3) colored by flourosopy
* thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
* target - the predicted attribute - diagnosis of heart disease
