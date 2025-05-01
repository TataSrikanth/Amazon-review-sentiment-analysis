
# 📊 Amazon Reviews Sentiment Analysis

This project performs **sentiment analysis** on Amazon product reviews using Natural Language Processing (NLP). It uses libraries like `nltk`, `pandas`, and `matplotlib` to clean, visualize, and classify review text into positive or negative sentiment.

## 🚀 Features

- Loads and preprocesses a dataset of Amazon product reviews
- Visualizes review score distribution
- Applies NLTK sentiment analysis tools
- Classifies review text based on polarity (positive/negative)

## 📁 Dataset

- File: `Reviews.csv`
- Columns used:
  - `Text`: The review text
  - `Score`: Star rating (1 to 5)

Only a subset of 500 reviews is used for quick analysis.

## 🧪 Techniques Used

- Text preprocessing (removing nulls, sampling)
- Visualization with Seaborn/Matplotlib
- Sentiment scoring using `nltk.sentiment.vader`
- Exploratory Data Analysis (EDA)

## 🛠️ Libraries

- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `nltk` – natural language processing

## 📌 How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn nltk
   ```

2. Run the notebook:
   ```bash
   jupyter notebook sentiment_analysis.ipynb
   ```

3. The notebook will load the dataset, run preprocessing, and perform sentiment classification.

## 📈 Output

- Graphs showing review distribution
- VADER sentiment scores per review
- Sample review analysis and result

## 📄 License

This project is for educational use. Check the dataset source for usage rights.
