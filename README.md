# Hate Comment Detection

**Hate Comment Detection (H2H)** is a system designed to analyze tweets and predict if they contain toxic, severe toxic, obscene, threatening, insulting, or identity hate content. This project helps to identify and flag harmful content on social media, promoting healthier and safer online interactions.

## Features
- Developed a multi-classification model to categorize tweets into five hate categories, enhancing platform safety.
- Trained an 11-layer neural network on over 150,000 data points, using sentence embeddings from `sentence-transformers/all-mpnet-base-v2`.
- Achieved high accuracy (98.95%) and precision (75%) in classifying tweets effectively.
- Performed thorough data preprocessing, including class balancing and data cleaning, to improve model accuracy and robustness.

## Installation

To use H2H, follow these steps:

1. Install Python and Jupyter Notebook on your machine.
2. Download the dataset used for training from Kaggle (Jigsaw Toxic Comment Classification Challenge).
3. Clone or download this repository to your local machine.
4. Open `code.ipynb` in Jupyter Notebook.
5. Follow the steps provided in the notebook to train the model and make predictions.

## Usage

Once the project is set up, you can use H2H to analyze tweets for hate content. Simply input the text of the tweet into the model, and it will output whether the tweet contains toxic, severe toxic, obscene, threatening, insulting, or identity hate content.

## Dataset

The project utilizes the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle, containing comments from Wikipedia discussions labeled for various types of toxicity.

## Model Performance

### Model 1 (`code.py`)
- **Accuracy**: 93.75%
- **Precision**: 50%
- **Layers in neural network**: 7

### Model 2 (`codev2.py`)
- **Accuracy**: 98.95%
- **Precision**: 75%
- **Layers in neural network**: 11

The accuracy and precision can be further tuned by adjusting the model's architecture and experimenting with additional layers or parameters.

## Contents

- `code.py`: Version 1 of the code.
- `codev2.py`: Version 2 of the code with improved model architecture.
- `output.txt`: Contains sample outputs. Example:

## WELCOME TO HATE DETECTOR:
H2H 1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 106ms/step tweet:
"I'll kill you" 
Toxic: True 
True severe_toxic: False
Obscene: False 
Threat: False 
Insult: False 
Identity_hate: False

## Contributing

Contributions to H2H are welcome! If you'd like to contribute, feel free to fork the repository, make your changes, and submit a pull request.
