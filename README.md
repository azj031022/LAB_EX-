# LAB_EX-
SOCIAL MEDIA LAB_EX3
📂 Social Media Computing - Lab Exercise 3
Course: CDS-6344 Social Media Computing
Lab Exercise 3 - Sentiment Analysis

✅ Tasks Implemented
a) Dependency-based Parsing (Aspect Extraction)
Using spaCy dependency parser to extract noun-adjective relations as aspects.

b) Unsupervised Machine Learning
KMeans Clustering with TF-IDF features to group text data into 2 clusters.

c) Supervised Machine Learning
Logistic Regression classification model for binary sentiment prediction.

📊 Dataset
Dataset file: data/res_review.csv

Original review dataset used from real restaurant review data.

Ratings converted to binary sentiment:

Rating 4-5 → Positive (1)

Rating 1-3 → Negative (0)

⚙️ Installation & Setup
1️⃣ Clone this repository:

bash
Copy
Edit
git clone <your-repo-link>
cd social-media-sentiment-lab3
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
python -m spacy download en_core_web_sm
🚀 Run the Solution
bash
Copy
Edit
python lab3_sentiment_analysis.py
💡 Notes
This lab exercise demonstrates opinion mining, aspect extraction, and basic ML models on social media reviews.

Fine-tuning with transformer models (like BERT) can be added as an advanced optional extension.
