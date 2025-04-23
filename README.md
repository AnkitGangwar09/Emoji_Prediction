# Emoji_Prediction
Created an emoji prediction model using RNNs — feeding in text and letting the model decide the best-fitting emoji.

# Goal
Given a sentence, predict one of five emojis  ❤️ 😂 😍 😢 😡.

# Dataset 
Pre‑labelled sentences (train/test split).

### Framework --> PyTorch 2.x

## Key Concepts
Tokenisation, Embedding layer, Bi‑LSTM, Softmax.


## Architecture
### Embedding Layer – learns 128‑dimensional word vectors.
### Bi‑Directional LSTM – hidden size = 256, 2 layers, dropout = 0.3.
### Fully Connected + Softmax – outputs 5‑class probabilities.

Accuracy = 87 %


## Lessons Learned
Hands‑on practice with tokenisers, padding, and packed sequences in PyTorch.
Saw how bidirectional context improves emoji recall for longer sentences.
Explored class imbalance mitigation with weighted loss.


