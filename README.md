
# PHT-WikiSum Summarization

![Python](https://img.shields.io/badge/python-3.11-blue)
![Transformers](https://img.shields.io/badge/transformers-4.55.0-orange)
![Datasets](https://img.shields.io/badge/datasets-4.0.0-lightgrey)
![ROUGE](https://img.shields.io/badge/ROUGE-evaluation-red)

## Overview
This project implements the **Parallel Hierarchical Transformer (PHT)** model for multi-document abstractive summarization using the [WikiSum dataset](https://www.kaggle.com/datasets/sandeep16064/wikisum).

The notebook includes:
- Data loading and preprocessing
- Tokenization
- Model implementation
- Evaluation using ROUGE metrics
- Comparison with other summarization models

## Folder Structure
PHT-WikiSum-Summarization/
│
├── notebooks/ # Contains your Colab notebook(s)
├── results/ # Plots, CSVs, and other outputs
├── requirements.txt # Python dependencies
└── README.md # 


## Installation
1. Clone this repository:

git clone <your-repo-link>
cd PHT-WikiSum-Summarization

2. Install dependencies:
pip install -r requirements.txt

## How to Run
1. Open the notebook in notebooks/.
2. Follow the cells step by step:
- Load and preprocess the dataset
- Tokenize data
- Train or evaluate the PHT model
- Save results to results/
3. Evaluation:
- ROUGE scores will be printed for the model
- Comparison charts saved in results/

## Datasets
- WikiSum
- CNN/DailyMail

## Example ROUGE Scores
Model	ROUGE-1	ROUGE-2	ROUGE-L
PRIMERA (sample CPU)	0.025	0.005	0.022
BART (sample CPU)	0.018	0.002	0.016
PHT (Quick ROUGE, CPU, small subset)	0.0155	0.0000	0.0155

## Outputs
- ROUGE evaluation scores
- Comparison charts (tables or plots)
- CSV files in results/

## Notes
- CPU is used for faster experimentation on small subsets
- For full dataset training, GPU is recommended
- Ensure your requirements.txt versions match your environment
- All plots and CSVs are saved in results/ folder
