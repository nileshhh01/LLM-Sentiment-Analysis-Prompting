# Sentiment Analysis with LLM Prompting 🤖📝

This project explores sentiment classification of Yelp restaurant reviews using advanced prompting techniques with Large Language Models (LLMs). We experiment with zero-shot, few-shot learning, and multiple LLMs including Claude and LLaMA.

## 🎯 Objectives
- Perform zero-shot sentiment analysis using Claude 3 Sonnet
- Apply few-shot prompting with selected positive/negative examples
- Compare outputs across multiple LLMs
- Evaluate using classification metrics (accuracy, precision, recall, F1-score)

## 📁 Files
- `Sentiment-Analysis with LLM Prompting.ipynb`: Main notebook with code and results
- `restaurant_reviews_az.csv`: Dataset used (external, not included in repo)
- `README.md`: Project summary
- `.gitignore`: Ignored system files
- `requirements.txt`: Python dependencies

## 🧰 Tools & Libraries
- Python (pandas, numpy)
- OpenAI/Anthropic LLM APIs (Claude, LLaMA, etc.)
- Scikit-learn
- Jupyter Notebook

## 🧪 Techniques Used
- Zero-shot prompting
- Few-shot prompting
- Multi-LLM comparison
- Evaluation using confusion matrix and classification report

## 📊 Observations
- Few-shot prompting improved performance over zero-shot
- Misclassifications often occurred in sarcastic or ambiguous reviews
- LLMs produced varying results depending on prompt design

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/llm-sentiment-analysis-prompting.git

# Install required packages
pip install -r requirements.txt

# Run the notebook
jupyter notebook
