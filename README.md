## This project uses Xgboost to detect whether an API request contains a cybersecurity attack/injection.

#### The Data
Data is the foundation of all AI projects, therefore this project was built on quality security data from [Wallarm data competition](https://www.kaggle.com/competitions/wallarm-ml-hackathon).

#### The task

The project goal is to build an AI model that can predict whether a vector is an injection (Usually SQLi). 
The term "vector" refers to a data input representing characteristics or features relevant to determining whether an SQL injection attack is present. In this case, the vector would likely contain information about the API request, such as parameters, headers, or payloads, which can be analyzed by a machine learning model to detect signs of a SQL injection attack.

#### The model 

In this project, I employed advanced machine learning techniques, specifically XGBoost, to enhance predictive accuracy in this binary classification task. The model, trained on a comprehensive feature set extracted from injection attacks textual data using TF-IDF vectorization, demonstrated remarkable performance with an AUC score of 0.99.

AUC (Area Under the ROC Curve) is a robust measure of a model's ability to discriminate between positive and negative classes. Our model's AUC score of 0.99 indicates its exceptional capability in distinguishing between these classes, showcasing its high true positive rate and low false positive rate.

**Citation** 

@misc{wallarm-ml-hackathon,
    author = {geeniecelento, Mikhail Salnikov, Renata},
    title = {Malicious Intent Detection Challenge},
    publisher = {Kaggle},
    year = {2018},
    url = {https://kaggle.com/competitions/wallarm-ml-hackathon}
}
