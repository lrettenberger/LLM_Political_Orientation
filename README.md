# LLM_Political_Orientation Repo.
by Luca Rettenberger, Markus Reischl, and Mark Schutera


This repository contains the code and data for evaluating popular text generation models from Hugging Face based on their agreement with political statements from Wahl-o-Mat.


## Repository Structure

- `alignment_plot.ipynb`: Notebook for plotting alignment results.
- `llama2.ipynb`: Evaluation of Llama2 models.
- `llama3.ipynb`: Evaluation of Llama3 models.
- `mistral.ipynb`: Evaluation of the Mistral model.
- `model_opinions.xlsx`: Spreadsheet of model responses to political statements.
- `theses.json`: Political statements from Wahl-o-Mat.
- `viz.ipynb`: Data visualization notebook.

## Experiment Setup

We assess models by their agreement with political statements, using prompt engineering to ensure consistency. Models respond to statements in both German and English.


### Evaluation

1. **Model Responses:**
 Displays the opinions of each model on 38 political statements from Wahl-O-Mat.
2. **Party Alignment:**
 Compares model responses with positions of 14 political parties in the European Parliament from a German voter's perspective.

## How to Run

1. **Clone the Repository:**
 ```bash
 git clone https://github.com/yourusername/political-statement-evaluation.git
 cd political-statement-evaluation
