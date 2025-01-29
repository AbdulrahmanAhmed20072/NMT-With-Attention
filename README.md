# Neural Machine Translation with Attention

This repository implements a Neural Machine Translation (NMT) model with attention using TensorFlow. The project leverages an encoder-decoder architecture to translate sentences, demonstrating state-of-the-art techniques for sequence-to-sequence tasks.

## Features

- **Encoder-Decoder Architecture**: Bidirectional LSTM-based encoder and attention-enabled decoder.
- **Cross-Attention Mechanism**: Custom implementation for enhanced context understanding.
- **Training Metrics**: Masked loss and accuracy to handle padding in sequences.
- **Translation Decoding**: Includes Minimum Bayes-Risk (MBR) decoding and similarity-based metrics.
- **Data Preparation**: Preprocessing for Portuguese-English sentence pairs.

## Files

1. **`NeuralMachineTranslation.ipynb`**: Python script implementing the NMT model.
2. **Dataset**: Portuguese-English sentence pairs prepared for training and validation.
3. **Utility Functions**: Functions for preprocessing, tokenization, and evaluation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulrahmanAhmed20072/NMT-With-Attention.git
   ```
2. Install the required Python packages:
   ```bash
   pip install tensorflow numpy tensorflow-text
   ```

## Usage

1. Preprocess the dataset for tokenization and vectorization.
2. Train the NMT model using the provided pipeline.
3. Use the trained model for inference to translate input sentences.
4. Evaluate translations using Jaccard and ROUGE similarity metrics.

Run the script:
```bash
python NeuralMachineTranslation.ipynb
```

## Outputs

- Trained NMT model with attention for sequence-to-sequence tasks.
- Translations with similarity scores using Jaccard and ROUGE metrics.
- MBR-decoded translations for optimal outputs.

## Example

Input Sentence:
```
I love programming.
```

Translated Output:
```
Eu adoro programar.
```
