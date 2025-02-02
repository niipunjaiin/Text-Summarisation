# Text-Summarisation
Topsis to find best pre-trained model for Text summarisation
# AI Model Comparison for Text Summarization using TOPSIS

## 🏆 Models Evaluated
We tested the following pre-trained models:

- **📘 M1: facebook/bart-large-cnn** - Optimized for summarizing news articles.
- **📗 M2: t5-small** - A lightweight version of T5, designed for various NLP tasks.
- **📙 M3: Falconsai/text_summarization** - A community-trained model for general summarization.
- **📕 M4: sshleifer/distilbart-cnn-12-6** - A faster, smaller version of BART for summarization.

## 📊 Evaluation Criteria
We assessed model performance based on the following factors:

- **📌 ROUGE-1**: Measures how much the generated summary matches the original text using single words.
- **📌 ROUGE-2**: Looks at two-word combinations to check accuracy.
- **📌 ROUGE-L**: Finds the longest matching phrases to judge readability and fluency.
- **📌 Compression Ratio**: Checks how much the summary shortens the original text without losing key information.
- **📌 Readability Score**: Evaluates how easy the summary is to understand.
- **📌 Inference Speed**: Measures how fast the model generates summaries, which is important for real-time applications.

## ⚙️ What is TOPSIS?
TOPSIS is a method used to rank models based on their scores in the above criteria. It works by:

1. **Standardizing the scores** to ensure fair comparisons.
2. **Identifying the best and worst possible results** for each factor.
3. **Measuring how close each model is to the ideal result**.
4. **Ranking the models accordingly** based on their overall performance.

This approach ensures an objective and fair comparison of the models.

## 🏅 Results
Using **TOPSIS scores**, we determined the best overall model:

### 🥇 Best Model: **M2 (t5-small)**
Based on the evaluation, **M2 (t5-small)** achieved the highest rank across multiple summarization tasks. It performed consistently well in ROUGE scores, readability, and compression ratio, making it the most effective summarization model for various applications.

## 🚀 Use Cases
M2 (t5-small) is highly effective for:

- **📰 News Summarization**: Summarizing long articles into key points.
- **⚖️ Legal Document Summarization**: Extracting important details from legal texts.
- **📄 Scientific Paper Summarization**: Making research findings easier to understand.
- **🤖 Chatbots and Virtual Assistants**: Improving AI-generated responses with shorter, clearer summaries.

📌 *For more details, check the code and dataset used in this project.*

- **Legal Document Summarization**: Extracting important details from legal texts.
- **Scientific Paper Summarization**: Making research findings easier to understand.
- **Chatbots and Virtual Assistants**: Improving AI-generated responses with shorter, clearer summaries.

For more details, check the code and dataset used in this project.
