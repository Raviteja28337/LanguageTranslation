# Language Translation - English to German

## Overview
This project focuses on developing and training multiple neural network models for English to German translation. The models explored include:

- Long Short-Term Memory (LSTM)
- Gated Recurrent Units (GRU)
- LSTM with Attention Mechanism
- Transformer Architecture
- Fine-tuned `mt5` Model

The fine-tuned `mt5` model achieved a **BLEU score of 40.25** on the **Multi30k dataset**, ranking among the top 3 scores recorded to date.

## Features
- Implementation of different sequence-to-sequence models for language translation
- Attention mechanism for improved translation accuracy
- Transformer-based architecture for state-of-the-art performance
- Fine-tuning of `mt5` for optimal translation results
- BLEU score evaluation to measure translation quality

## Dataset
- The models are trained and evaluated on the **Multi30k dataset**, a widely used dataset for English-German translation tasks.
- Preprocessing steps include tokenization, padding, and vocabulary creation.

Supported model names:
- `lstm`
- `gru`
- `lstm_attention`
- `transformer`
- `mt5_finetuned`
