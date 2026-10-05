# Sentiment Analysis

## 📌 Project Overview

**Sentiment Analysis** is a basic Natural Language Processing (NLP) project that identifies the sentiment of a given text.

The system analyzes a statement and classifies it into one of three categories:

* **Positive**
* **Neutral**
* **Negative**

### Example

**Input:**

> I really enjoyed this movie.

**Output:**

> Positive

---

## 🎯 Objective

The main objective of this project is to build a simple sentiment analysis system that can understand the overall sentiment expressed in a statement.

The project focuses only on three sentiment categories:

| Sentiment   | Meaning                                          |
| ----------- | ------------------------------------------------ |
| 😊 Positive | Shows happiness, satisfaction, or a good opinion |
| 😐 Neutral  | Shows a normal, factual, or unclear opinion      |
| 😞 Negative | Shows dissatisfaction, sadness, or a bad opinion |

---

## ⚙️ How It Works

The project follows a simple process:

```text
User enters a statement
        ↓
Text is processed
        ↓
Sentiment is analyzed
        ↓
Sentiment is classified
        ↓
Positive / Neutral / Negative
```

### Example 1

**Input:**

```text
I love this product.
```

**Output:**

```text
Positive
```

### Example 2

**Input:**

```text
The meeting is scheduled for 10 AM.
```

**Output:**

```text
Neutral
```

### Example 3

**Input:**

```text
I am disappointed with the service.
```

**Output:**

```text
Negative
```

---

## 🛠️ Technologies Used

* **Python**
* **Natural Language Processing (NLP)**
* **Machine Learning**
* **Jupyter Notebook / Google Colab**

---

## 📂 Project Structure

```text
Sentiment-Analysis/
│
├── Sentiment_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Sentiment-Analysis.git
```

Move into the project folder:

```bash
cd Sentiment-Analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Open the project in **Jupyter Notebook** or **Google Colab**.
2. Open `Sentiment_Analysis.ipynb`.
3. Run the notebook cells.
4. Enter a statement.
5. The system will classify the statement as:

```text
Positive
Neutral
Negative
```

---

## 🧪 Sample Input and Output

| Input Statement                  | Predicted Sentiment |
| -------------------------------- | ------------------- |
| I am very happy today.           | Positive            |
| The weather is normal today.     | Neutral             |
| I don't like this product.       | Negative            |
| This is an excellent experience. | Positive            |
| The class starts at 9 AM.        | Neutral             |
| The service was terrible.        | Negative            |

---

## 🎯 Features

* Classifies text into **Positive, Neutral, or Negative**
* Simple and easy to use
* Beginner-friendly NLP project
* Accepts a statement as input
* Provides the predicted sentiment as output

---

## 📊 Sentiment Classes

The project contains only **three classes**:

### Positive

Used when the statement expresses a positive feeling or opinion.

Example:

```text
This product is amazing.
```

### Neutral

Used when the statement is factual, normal, or does not clearly express a positive or negative feeling.

Example:

```text
The product was delivered today.
```

### Negative

Used when the statement expresses a negative feeling or opinion.

Example:

```text
The product quality is very poor.
```

---

## 🔮 Future Improvements

The current project is intentionally kept simple with three sentiment classes.

Possible future improvements include:

* Improving prediction accuracy
* Using a larger dataset
* Adding a graphical user interface
* Supporting multiple languages
* Deploying the model as a web application

---

## 👩‍💻 Author

**Sheeba Catherine**

Artificial Intelligence and Data Science Student

---

## 📜 License

This project is created for **educational and learning purposes**.

