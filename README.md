# Chinese to Polish Translation Demo

This project implements a two-step translation from Chinese to Polish via English using pretrained models from Hugging Face:

- Chinese → English: `Helsinki-NLP/opus-mt-zh-en`
- English → Polish: `facebook/mbart-large-50-many-to-many-mmt`

The demo runs in a Google Colab notebook and provides an interactive Gradio interface for easy use.

## How to run

1. Open the Colab notebook `translator_demo.ipynb`.
2. Run the first cell to install dependencies.
3. Run the demo code cell to launch the Gradio UI.
4. Input Chinese sentences and get Polish translations instantly!

## Requirements

- Python 3.7+
- `transformers`, `gradio`, `sentencepiece`, `torch`

Install dependencies with:

```bash
pip install transformers gradio sentencepiece torch
