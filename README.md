# Summarization

📝 Text Summarization Using spaCy
This project demonstrates simple extractive summarization using spaCy, a powerful NLP library in Python.

🔍 How It Works
Text Preprocessing:

Load text with spaCy’s language model (en_core_web_sm).

Tokenize and remove stop words and punctuation.

Word Frequency Calculation:

Calculate frequency of each meaningful word.

Sentence Scoring:

Score each sentence based on the sum of its word frequencies.

Summary Extraction:

Select the top n sentences with the highest scores.

🛠 Requirements
Python 3.6+

spaCy

bash
Copy
Edit
pip install spacy
python -m spacy download en_core_web_sm
🚀 Run the Script
bash
Copy
Edit
python summarizer.py
You can customize the number of summary sentences or plug in different text sources (e.g., from files or web scraping).
