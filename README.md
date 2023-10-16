# AAI520_Final_Project_ChatBot

# ChatterBot

## Description
This repository contains code for a final project for the NLP class at the University of San Diego. The project focuses on building a question-answering system using the DistilBERT model to handle multilingual contexts while utilizing Hugging Face's Transformers library.

## Project Overview

The project involves the following major steps:

    1. **Data Preparation**: The project starts with loading and preprocessing the SQuAD dataset, extracting relevant information such as context, question, answer, and their respective positions.

    2. **Data Splitting**: The dataset is split into training, validation, and test sets, and appropriate preprocessing functions are defined for tokenizing and formatting the data for model training.

    3. **Model Fine-Tuning**: The DistilBERT model is fine-tuned using the preprocessed data to create a question-answering system.

    4. **Model Evaluation**: The model is evaluated using various metrics such as accuracy, precision, recall, F1 score, and a comprehensive classification report.

## Project Structure

The project is structured as follows:

- `ChatterBotQA.ipynb`: Jupyter notebook containing the code and step-by-step explanation of the project.
- `qa.csv`: Dataset saved as a CSV file for convenience.
- `README.md`: This file, providing an overview of the project.

## Instructions for Running the Code

To run the code in this repository, follow these steps:

1. Open the Jupyter notebook `ChatterBotQA.ipynb` in Google Colab.
2. Mount your Google Drive using the provided code in the notebook.
3. Run the notebook cells in sequence to execute the project code.
4. See it live via: 

## Acknowledgements
This project was completed as a part of the NLP class at the University of San Diego.

## License
ChatterBot is licensed under the MIT License. See the LICENSE file for more details.

## Authors
Selina Lasher, Fernando Calderon and Prachi Khanna

