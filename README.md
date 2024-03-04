## This project uses PyTorch to implement deep learning for detecting whether an API request contains a cybersecurity attack or injection.
### Data is the foundation of all AI projects, theefore this project was built on quality security data from [Wallarm data competition](https://www.kaggle.com/competitions/wallarm-ml-hackathon).

#### The task

The project goal is to build an AI model that can predict whether a vector is injection (Usually SQLi) or not. 
The term "vector" refers to a data input that represents characteristics or features relevant to determining whether an SQL injection attack is present or not. In this case, the vector would likely contain information about the API request, such as parameters, headers, or payloads, which can be analyzed by a machine learning model to detect signs of a SQL injection attack.

**Citation** 

@misc{wallarm-ml-hackathon,
    author = {geeniecelento, Mikhail Salnikov, Renata},
    title = {Malicious Intent Detection Challenge},
    publisher = {Kaggle},
    year = {2018},
    url = {https://kaggle.com/competitions/wallarm-ml-hackathon}
}
