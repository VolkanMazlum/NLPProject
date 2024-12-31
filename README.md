# Cornell Movie Dialog Dataset Analysis

This repository contains a comprehensive project analyzing the **Cornell Movie Dialog Dataset**, focusing on Natural Language Processing (NLP) techniques and machine learning models. The project explores conversational patterns, dialogue generation, metadata predictions, and chatbot development. It is a group project from Politecnico di Milano

## Dataset

- **Source**: [Cornell Movie Dialog Dataset](http://www.cs.cornell.edu/~cristian/data/cornell_movie_dialogs_corpus.zip)
- **Paper**: [Chameleons in Imagined Conversations](https://www.cs.cornell.edu/~cristian/papers/chameleons.pdf)
- **Citation**: 
  > Danescu-Niculescu-Mizil, C., & Lee, L. (2011).  
  > *Chameleons in imagined conversations: A new approach to understanding coordination of linguistic style in dialogs.*  
  > ACL 2011.

---

## Features and Objectives

### Main Tasks
1. **Exploratory Data Analysis (EDA)**:
   - Dataset statistics
   - Dialogue searches using regular expressions
   - Topic modeling and clustering
   - Learning word embeddings

2. **Dialogue Generation**:
   - Encoder-decoder models
   - Attention mechanisms
   - Pre-trained models (Flan-T5, DialoGPT, fine-tuned GPT-2)

3. **Metadata Predictions**:
   - Multi-label classification for movie genres
   - Rating predictions using linear models and fine-tuned BERT

4. **Chatbot Development**:
   - Speech-to-text and text-to-speech integration
   - GPT-2 fine-tuning for character-specific dialogue generation

### Key Objectives
- Analyze dialogue characteristics using NLP techniques.
- Compare dialogue generation models and fine-tuning methods.
- Predict metadata with classification and regression models.
- Build a movie character chatbot for interactive responses.

---

## Requirements

- Python 3.7+
- Libraries: TensorFlow, PyTorch, Hugging Face Transformers, nltk, scikit-learn, etc.
- [Google Colab](https://colab.research.google.com/) for running the notebook (optional).

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/VolkanMazlum/NLPProject.git
   cd repository-name
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset:
   ```bash
   curl -L -o cornell_movie_dialogs.zip http://www.cs.cornell.edu/~cristian/data/cornell_movie_dialogs_corpus.zip
   unzip cornell_movie_dialogs.zip
   ```

---

## Usage

1. Open the notebook:
   ```bash
   jupyter notebook NLP_cornell_movie_dataset.ipynb
   ```
2. Follow the notebook sections:
   - **EDA**: Explore dataset characteristics.
   - **Modeling**: Train dialogue generation and metadata prediction models.
   - **Chatbot**: Run the chatbot for interactive conversations.

---
