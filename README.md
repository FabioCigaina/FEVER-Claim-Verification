# FEVER Claim Verification

## Project overview
This project's goal is to train a machine learning model on **natural language inference** (NLI), a natural language processing task that consists of determining the relationship between two text snippets: `claim` and `evidence`. The model aims to classify the claim as entailed (true), contradicted (false) or neutral (undetermined). 

## Links
* **Live demo**: https://huggingface.co/spaces/fabiocigaina/nli-fever-demo
* **Model on Hugging Face**: https://huggingface.co/fabiocigaina/deberta-v3-base-nli-fever-pietrolesci

## Dataset
I used Pietro Lesci's NLI FEVER dataset, derived from FEVER: https://huggingface.co/datasets/pietrolesci/nli_fever

## Results
- Accuracy: `0.764`
- F1 macro: `0.754`

## Repo structure
├── nli_fever.ipynb # EDA, training, evaluation, analysis  
├── requirements.txt # for the notebook  
└── README.md  
