# Bigram Language Model using a Transformer

This is a project implementation of a Bigram Language Model using a Transformer, consisting of Multi-Head Self Attention Blocks. The model will predict the next character in a sequence given the previous `block_size` characters.

## Model Architecture

The Transformer model consists of:
- **Embedding Layer**
- **Positional Embedding**
- **Transformer Blocks** (Multi-Head Self Attention + Feed Forward Neural Network)
- **Layer Norm**
- **Output Layer** (MLP)

## Training

The model is trained using the AdamW optimizer and cross-entropy loss.

## Inspiration

This implementation was inspired and guided by:
- The [char-rnn project](https://github.com/karpathy/char-rnn) by Andrej Karpathy
- The paper [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
