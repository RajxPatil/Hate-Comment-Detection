# HATE DETECTION
Devising hate detection system that takes tweets as inputs and predicts whether the tweet contains **toxic, severe toxic, obscene, threat, insult, or identity** hate content. It aims to identify and flag harmful content on social media platforms to promote healthier online interactions.

## Installation
To use H2H, follow these steps:

* Install Python and Jupyter Notebook on your machine.
* Download the dataset used for training the model from Kaggle.
* Clone or download this repository to your local machine.
* Open the code.ipynb notebook in Jupyter Notebook.
* Follow the steps provided in the notebook to train the model and make predictions.

## Usage
Once you have set up the project, you can use H2H to analyze tweets for hate content. Simply input the text of the tweet into the model, and it will output whether the tweet contains toxic, severe toxic, obscene, threat, insult, or identity hate content.

## Dataset
The project uses the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle. The dataset contains comments from Wikipedia discussions, along with labels for various types of toxicity.

## Model Performance
### Model 1 (code.py)
Accuracy: 93.75%  
Precision: 50%  
Layers in neural network: 7
### Model 2 (codev2.py)
Accuracy: 98.95%  
Precision: 75%  
Layers in neural network: 11  

The accuracy and precision can be further improved by adjusting the layers in the model architecture.

## Contents
### code.py: 
version1 of code
### codev2.py
version2 of code
### output.txt
contains sample outputs
Example -  
WELCOME TO HATE DETECTOR: H2H  
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 106ms/step  
tweet: "I'll kill you"  
toxic: True  
severe_toxic: False  
obscene: False  
threat: False  
insult: False  
identity_hate: False  

## Contributing
Contributions to H2H are welcome! If you would like to contribute to the project, feel free to fork the repository, make your changes, and submit a pull request.
