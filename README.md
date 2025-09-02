Amazon Reviews Sentiment Analysis:
This project applies Hugging Face Transformers to analyze customer sentiment from Amazon product reviews. The goal was to classify reviews into Positive, Neutral, or Negative categories using state-of-the-art NLP techniques.


Approach:
Fine-tuned DistilBERT on 100K+ Amazon reviews.

Achieved 94% accuracy with strong performance on positive reviews (F1: 0.97).

Training completed in 1 epoch (~44 min runtime) with final loss = 0.26.

Compared performance against classical ML baselines (TF-IDF + Logistic Regression, ~72% accuracy).

Conducted EDA and error analysis, highlighting challenges with neutral-class detection.

Tech Stack:

Python, PyTorch, Jupyter Notebook

Hugging Face Transformers (Trainer API, DistilBERT)

Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
