# MSDS 458 Final Project – Math Problem Classification

## Overview

This repository contains a final project notebook for MSDS 458 focused on multi-class classification of mathematical problems using deep learning and transformer-based NLP techniques. The project evaluates a series of experiments ranging from traditional LSTM architectures to BERT and MathBERT feature extraction and fine-tuning approaches.

The notebook explores

 Exploratory Data Analysis (EDA)
 Text vectorization strategies
 Embedding generation with BERT and MathBERT
 Sequential deep learning models (LSTM)
 Transformer-based architectures
 Transfer learning and fine-tuning
 Model evaluation and visualization

---

## Dataset

The project uses the KAChallenges Series 1 Classifying Math Problems dataset.

The dataset contains mathematical questions labeled by topicclass, enabling supervised multi-class text classification.

Expected files

 `train.csv`
 `test.csv`
 `solution.csv`

The notebook originally references Google Drive paths from Google Colab. These paths may need to be updated for local execution.

---

## Project Structure

```text
MSDS_458_Final_project_.ipynb
README.md
```

The notebook is organized into the following sections

1. Imports and environment setup
2. Visualization helper functions
3. Dataset loading and exploration
4. Vectorization and statistical EDA
5. BERT embedding analysis
6. MathBERT embedding analysis
7. Deep learning experiments
8. Model evaluation and plotting

---

## Experiments Included

### LSTM-Based Models

 Experiment 1 Baseline LSTM
 Experiment 2 Modified LSTM architecture
 Experiment 3 Additional LSTM tuning
 Experiment 4 LSTM variation
 Experiment 5 LSTM variation

### BERT-Based Models

 Experiment 6 BERT feature extraction with dense layers
 Experiment 7 LSTM with BERT sequence embeddings
 Experiment 8 Transformer with BERT embeddings
 Experiment 12 Fine-tuning BERT

### MathBERT-Based Models

 Experiment 9 MathBERT feature extraction with dense layers
 Experiment 10 LSTM with MathBERT embeddings
 Experiment 11 Transformer with MathBERT embeddings
 Experiment 13 Fine-tuning MathBERT

---

## Technologies Used

### Languages & Frameworks

 Python
 TensorFlow  Keras
 Hugging Face Transformers
 Scikit-learn
 Pandas
 NumPy
 Matplotlib
 NLTK

### NLP Models

 BERT
 MathBERT

---

## Key Topics Explored

 Natural Language Processing (NLP)
 Text classification
 Transfer learning
 Transformer architectures
 Domain-specific embeddings
 Sequence modeling
 Deep learning experimentation

---

## Running the Notebook

### Recommended Environment

The notebook was originally developed in Google Colab with GPU acceleration.

### Installation

Install required packages before running

```bash
pip install tensorflow transformers datasets nltk nlpaug scikit-learn matplotlib pandas numpy
```

### Launch

Open the notebook in

 Jupyter Notebook
 JupyterLab
 Google Colab

Then run cells sequentially.

---

## Notes

 Some paths are configured for Google Drive and may require modification.
 GPU acceleration is strongly recommended for transformer fine-tuning experiments.
 Several experiments compare classical sequence models against transformer-based transfer learning approaches.

---

## Learning Objectives

This project demonstrates

 Building end-to-end NLP pipelines
 Comparing embedding strategies
 Evaluating transformer vs. recurrent architectures
 Applying domain-specific language models
 Conducting experimental deep learning workflows

---

## Future Improvements

Potential extensions include

 Hyperparameter optimization
 Cross-validation workflows
 Additional transformer architectures
 Error analysis by math topic
 Model explainability techniques
 Improved data augmentation
 Deployment as an inference API

---

## Author

Soraya Karimi Butler, MSDS 458 Final Project
