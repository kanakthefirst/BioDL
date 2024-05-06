# Team BioDL

## Overview
The primary objectives of the project include predicting mortality and length of stay for patients based on the provided medical data. The project specifically employs the MIMIC III dataset for its analysis. 
This project comprises four main modules: Prompt Module, Sentence Encoder, Classifier, and Regressor. It is designed to handle tabular data where the Prompt Module generates prompts based on the given data, the Sentence Encoder encodes these prompts into embeddings, and finally, the Classifier and Regressor utilize these embeddings to generate the Mortality and Length of Stay respectively.

## Modules

### 1. Prompt Module

- **Functionality**: Generates prompts based on the tabular data provided.
- **Input**: Tabular data.
- **Output**: Prompt strings.

### 2. Sentence Encoder

- **Functionality**: Encodes prompts into embeddings.
- **Input**: Prompt strings.
- **Output**: Embeddings of the prompts.

### 3. Classifier

- **Functionality**: Utilizes embeddings to classify data.
- **Input**: Prompt embeddings.
- **Output**: Mortality Prediction

### 4. Regressor

- **Functionality**: Utilizes embeddings to perform regression analysis.
- **Input**: Prompt embeddings.
- **Output**: Length of Stay prediction.



## Dependencies

- **Libraries**: Pytorch, Numpy, matplotlib, pandas, transformers

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kaiwalya-joshi/BioDL.git
