# news-classifier-ml
This project is a **News Classification System** that uses various **Machine Learning** algorithms to classify news articles into different categories. It is built using Python and leverages the popular **20 Newsgroups dataset**.

---

## Features
- Text cleaning and preprocessing (punctuation removal, stopwords filtering)
- Feature extraction using **TF-IDF vectorization**
- Multi-class classification using:
  - Logistic Regression
  - Decision Tree
  - Naive Bayes
- Performance evaluation with:
  - Accuracy scores
  - Confusion matrix
  - Comparison of algorithms
- Real-time prediction based on user input

---

## Dataset

- **20 Newsgroups Dataset** (from `scikit-learn`)
- Contains ~18,000 news articles across 20 categories like:
  - `sci.space`, `rec.sport.hockey`, `talk.politics.guns`, `comp.sys.mac.hardware`, etc.

---

## Technologies Used

- **Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy` – data handling
  - `matplotlib`, `seaborn` – visualization
  - `nltk` – natural language processing
  - `scikit-learn` – ML models and utilities

---

## How to Run

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/news-classifier-ml.git
   cd news-classifier-ml


2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt

3. **Run the script**  
   ```bash
   python news_classifier.py
