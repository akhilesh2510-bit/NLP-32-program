# NLP Lab — 32 Jupyter Programs

Contains 32 separately numbered Jupyter notebooks matching the supplied NLP practical list.

## Run
1. Extract this ZIP.
2. Open the folder in VS Code or JupyterLab.
3. Select a Python 3 kernel.
4. Open a notebook and choose **Run All**.

## Install
```bash
python -m pip install --upgrade pip
pip install numpy pandas scikit-learn nltk spacy textblob scipy gensim jupyter
```
For optional Hugging Face pretrained models:
```bash
pip install transformers torch sentence-transformers datasets accelerate
```
Pretrained model weights are downloaded on first use and require internet access.

## Important scope notes
- Each notebook contains a small self-contained sample dataset and a saved demonstration output.
- Program 6 explains that a trained spaCy NER model is needed for real entity predictions.
- Programs 24–30 include offline demonstrations/fallbacks and explain how to enable pretrained Hugging Face models. They do not claim that full BERT/GPT-2/MarianMT/BART weights were downloaded or fine-tuned in this offline run.
- Program 13 creates a small local GloVe-format sample file; use a full pretrained GloVe file for real embeddings.
- Program 14 demonstrates the optimal-transport idea on toy embeddings; full WMD needs pretrained vectors and an EMD solver.
- Use larger datasets and proper train/test evaluation before reporting academic model performance.
