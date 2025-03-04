# POS Tagging and Medical Named Entity Recognition

This project focuses on two key Natural Language Processing (NLP) tasks: `Part-of-Speech (POS) Tagging` and `Medical Named Entity Recognition (NER)`. Both tasks are implemented in separate Jupyter Notebook files and are designed to be run on Google Colab.

## Project Overview

**1. POS Tagging (`pos_tagging.ipynb`)**

- Identifies and labels words in a sentence according to their grammatical categories (e.g., noun, verb, adjective).
- Uses a pre-trained transformer-based model (such as BERT) for high accuracy tagging
- Trained and evaluated on the `Penn Tree Bank` dataset.

**2. Medical Named Entity Recognition (NER) (`ner_recog.ipynb`)**

- Extracts medical entities from clinical text, such as diseases, genes, and body parts.
- Uses a specialized biomedical pre-trained model for entity recognition.
- Trained on the `MACCROBAT2018` dataset.

## Setup & Execution

The project is designed to be run on `Google Colab` for easy access to GPU acceleration. Follow these steps to get started:

1. **Open Google Colab** and upload the respective notebook file (1pos_tagging.ipynb1 or 1ner_recog.ipynb`).
2. **Install Dependencies** by running the first code cell in each notebook.
3. **Load and Preprocess Data** as described in the notebooks.
4. **Train the Model** or use pre-trained weights for inference.
5. **Run Inference** on sample text to evaluate performance.

## Results

- The `POS Tagging model` achieved `99.09% accuracy` on the test set.
- The `Medical NER model` achieved `78.5% accuracy` on the validation set.
