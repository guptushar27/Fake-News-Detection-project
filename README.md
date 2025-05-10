A machine learning-based system that classifies news articles as real or fake, trained and evaluated using Indian news-style inputs. This project demonstrates the use of NLP and classification models to combat misinformation.

🚀 Features
✅ Classifies news as Real or Fake using Logistic Regression

✅ Trained on labeled news dataset

✅ Text preprocessing with stopword removal and TF-IDF vectorization

✅ Indian news headline testing and evaluation

✅ Achieved ~92% accuracy

✅ Ready-to-use in Jupyter/Colab

📁 Dataset
Used: news.csv (with text and label columns)

Labels:
0 → Real News
1 → Fake News

🛠 Tech Stack
Python

Scikit-learn

Pandas, NumPy

NLTK (stopwords)

TF-IDF Vectorizer

Jupyter Notebook / Google Colab

🧪 Sample Predictions
Headline	Prediction
PM Modi announces ₹5000 direct benefit transfer to every citizen.	❌ Fake News
India successfully launches Chandrayaan-3 mission to the Moon.	✅ Real News
CBSE board exams postponed due to heatwave across North India.	✅ Real News

📈 Model Performance
Accuracy: ~92%

Precision: 91.7%

Recall: 93.1%

F1 Score: 92.4%

📌 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:
Open FakeNewsDetection.ipynb in Jupyter or Google Colab.

🔮 Future Scope
Multilingual news classification (Hindi, Tamil, etc.)

Transformer-based models (like BERT)

Real-time fake news detection API

Source credibility scoring

User reporting and retraining mechanism

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

📄 License
This project is licensed under the MIT License.

