# mlops-assignment-2
# Name: U E Sai Pavan Vamshi Krishna
# Roll No: G25AIT2149

# Goodreads Genre Predictor (MLOps Pipeline)

This project fine-tunes a DistilBERT model to predict the genre of a book based on its text. The main focus of this project is building a complete MLOps pipeline, including tracking experiments with Weights & Biases, utilizing Kaggle GPUs for training, and deploying the final weights to the Hugging Face Hub.

## Setup Instructions
To reproduce this experiment:
1. Open the Kaggle Notebook linked below.
2. Turn on the GPU (T4 x2) and Internet in the Kaggle settings.
3. Add your `WANDB_API_KEY` and `HF_TOKEN` in the Kaggle Add-ons -> Secrets menu.
4. Run all cells in the notebook.

## Project Links
- **Kaggle Notebook (Training):** [https://www.kaggle.com/code/uesaipavang25ait2149/mlops-assignment-2-fine-tuning-classification]
- **Weights & Biases Dashboard:** [https://wandb.ai/g25ait2149-indian-institute-of-technology-jodhpur/mlops-assignment2]
- **Hugging Face Model:** [https://huggingface.co/g25ait2149/distilbert-goodreads-genres]

## Results

| Metric    | Score |
|-----------|-------|
| Accuracy  | 0.59  | 
| F1 Score  | 0.59  | 
| Eval Loss | 2.23  | 
