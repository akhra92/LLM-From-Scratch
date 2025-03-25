# GPT-2 Like Model from Scratch on Shakespeare Text

This repository implements a GPT-2-like model from scratch, trained on a text dataset containing all the words from Shakespeare. The model performs character-wise text generation and serves as an excellent foundation for understanding how transformer-based models such as GPT work.

## Features
- Implements a character-level GPT model from scratch
- Trained on a dataset containing Shakespeare's complete works
- Uses a transformer-based architecture similar to GPT-2
- Based on tutorial videos by Andrei Karpathy on YouTube

## Installation
To set up the environment, install the required dependencies:

```bash
pip install torch
```

## Usage
Run the training script:

```bash
python bigram.py
```

## Acknowledgments
This implementation is adapted from the tutorial videos of **Andrei Karpathy** on YouTube. His explanations provide valuable insights into the inner workings of transformer-based models.