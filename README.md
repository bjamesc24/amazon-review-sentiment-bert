# Amazon Review Sentiment Analysis with BERT

Fine-tuned BERT model for 3-class sentiment classification (positive, negative, neutral) 
on the Amazon Food Reviews dataset.

## Results
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Negative | 0.64 | 0.83 | 0.72 |
| Neutral | 0.62 | 0.51 | 0.56 |
| Positive | 0.88 | 0.78 | 0.83 |
| **Overall Accuracy** | | | **0.71** |

## Tech Stack
- Python, PyTorch, HuggingFace Transformers
- BERT (bert-base-uncased), fine-tuned for sequence classification
- scikit-learn, pandas, NLTK, textaugment (EDA)

## How to Run
1. Upload `Reviews.csv` to your Colab environment
2. Run the patch cell first, then restart the kernel
3. Run all cells in order

## Dataset
[Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) — 568k reviews scored 1–5, converted to negative/neutral/positive labels.
