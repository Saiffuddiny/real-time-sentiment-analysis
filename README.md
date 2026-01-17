# Real-Time Sentiment Analysis Application

This project is a **Python application for real-time sentiment analysis**. Users can input text (e.g., movie reviews), and the application predicts whether the sentiment is **positive** or **negative** using a **Random Forest classifier** trained on labeled review data.

---

## Features

- **Random Forest classifier** trained on a labeled dataset
- **TF-IDF vectorization** for text preprocessing
- **Real-time user interaction** via command-line input or Colab UI
- Displays **sentiment prediction** and **confidence score**

---

## Dataset

This project uses a labeled dataset of text reviews with sentiment labels. You can use:

- IMDb Movie Reviews dataset ([Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews))  
- The dataset should have two columns: 
  - `review` (text of the review)  
  - `sentiment` (`positive` or `negative`)  

> The CSV is loaded in the notebook and preprocessed by dropping missing values.

---

## Installation

1. Clone the repository or download the notebook.  
2. Make sure you have **Python 3.8+** installed.  
3. Install dependencies:

```bash
pip install -r requirements.txt
