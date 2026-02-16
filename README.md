# mlp-sentiment-analysis
Multi-Layer Perceptron (MLP) built from scratch to predict movie review sentiment (positive/negative) using VADER + TextBlob features.
# Results
- **Test Accuracy**: XX% (from your final evaluation)
- **Features**: VADER compound/pos/neg + TextBlob polarity (4 features)
- **Architecture**: Input(4) → Hidden(8, ReLU) → Output(1, Sigmoid)

# Model Files
- `mlp_best_model.pkl` - Trained weights (ready to use!)
- `mlp_submission.csv` - Test predictions

#Quick Start
```bash
pip install pandas numpy matplotlib seaborn nltk textblob scikit-learn
jupyter notebook IMDB_MLP_Sentiment_Analysis.ipynb
