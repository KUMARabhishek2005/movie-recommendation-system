# 🎬 Movie Recommendation System

A content-based movie recommendation system that suggests similar movies based on user input using **TF-IDF vectorization** and **cosine similarity**. Built with Python and Jupyter Notebook, this project includes a clean GUI version using Tkinter as well as a notebook-based exploration of the logic behind it.


## 📌 Overview

This project is designed to help users discover new movies similar to ones they already like. It uses **Natural Language Processing (NLP)** techniques to process movie metadata and recommend titles based on textual similarity of movie genres or descriptions.

## 🔍 Features

- ✅ **Content-Based Filtering** (using TF-IDF + Cosine Similarity)
- ✅ **Fuzzy Matching** of user input to handle typos or partial matches
- ✅ **Jupyter Notebook** for analysis and experimentation
- ✅ **Clean GUI (optional)** version using `tkinter`
- ✅ Works completely **offline** with a local dataset (`movies.csv`)

visual of the interface 


## 📊 How It Works

1. **Text Vectorization**:
   - Movie titles or descriptions are transformed using **TF-IDF (Term Frequency-Inverse Document Frequency)** to numerical vectors.

2. **Similarity Computation**:
   - Cosine similarity is used to compare vectorized titles and find the most similar ones.

3. **User Input Handling**:
   - `difflib.get_close_matches()` is used to match user input to the closest title in the dataset, making the system user-friendly.

## 🧠 Technologies Used

| Technology   | Purpose                        |
|--------------|--------------------------------|
| Python       | Core programming language      |
| Jupyter      | Data exploration and modeling  |
| pandas       | Data loading and preprocessing |
| scikit-learn | TF-IDF and cosine similarity   |
| difflib      | Fuzzy string matching          |
| tkinter      | GUI (optional)                 |

## 📂 Project Structure
movie-recommendation-system/
├── untitled3.ipynb # Jupyter Notebook version
├── movies.csv 
├── requirements.txt 
└── README.md 
## 🚀 Getting Started

### Clone the repository
```bash
git clone https://github.com/KUMARabhishek2005/movie-recommendation-system.git
cd movie-recommendation-system

pip install -r requirements.txt
