# Heart_Disease_prediction_using logisticRegression
Workflow :
    Importing required libraries
    Loading Data Set
    Shape of Data
    Basic Understanding of Data
    Column types and descriptions
    Preprocessing of Data
        Cleaning of Data (checking missing values, skewness and distribution of features and target, detecting outliers, handling outlliers)
    Relationship of features with target using scatterplot
    Feature Selection (correlation, multicollinearity)
    Seggregation of Training data and test data
    Building prediction Model
    Predictions of test data
    Model Evaluation (confusion matrix, accuracy, precision, recall, f1 score, roc and auc)
Note:
columns description:
    age : age in years
    sex : (1 = male; 0 = female)
    chest pain type (4 values)
    resting blood pressure : resting blood pressure (in mm Hg on admission to the hospital)
    serum cholestoral in mg/dl
    fasting blood sugar > 120 mg/dl : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
    resting electrocardiographic results (values 0,1,2) : resting electrocardiographic results
    thalach: maximum heart rate achieved
    maximum heart rate achieved
    exang : exercise induced angina (1 = yes; 0 = no)
    oldpeak: ST depression induced by exercise relative to rest
    slope: the slope of the peak exercise ST segment
    ca: number of major vessels (0-3) colored by flourosopy
    thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
    target : 1 or 0
