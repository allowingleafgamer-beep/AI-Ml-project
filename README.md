# 📧 Spam Email Detector (CLI)

A lightweight, locally-hosted Machine Learning application built with Python that seprate emails and text messages as spam or non-spam. It show an interactive Command Line Interface and uses a model trained on a custom dataset of localized, modern messaging scams.

## ✨ Features

* **Real-time Classification:** Instantly check whether a message is spam or legitimate.
* **Confidence Scoring:** it not just give simple yes/no answers but also providing the exact probability percentage of a message being spam.
* **Batch Processing:** Check multiple emails in a row and get a summarized report at the end.
* **Custom Contextual Dataset:** Trained on a curated list of modern scams.
* **Interactive CLI:** A user-friendly, loop-based terminal menu for seamless testing.

## 🛠️ Tech Stack & Algorithm

* **Language:** Python 3.x
* **Library:** `scikit-learn`
* **Feature Extraction:** `CountVectorizer` (Bag-of-Words approach)
* **Algorithm:** `MultinomialNB` (Multinomial Naive Bayes)

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your system. You will also need the `scikit-learn` library.

### Installation

Copy the program and past it in you compiler and run the program.

### If by chance you not have install the scikit-learn 

copy the command this command `pip install scikit-learn` and paste this command in your terminal.
