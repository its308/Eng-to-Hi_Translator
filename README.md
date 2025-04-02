# English-to-Hindi Translator

## Overview
This project implements an **English-to-Hindi Translator** using a **Sequence-to-Sequence (Seq2Seq) model with Attention**. The model is trained on parallel English-Hindi sentence pairs and leverages **Recurrent Neural Networks (RNNs) with LSTMs** to generate translations.

## Features
- **Seq2Seq Architecture**: Uses an encoder-decoder framework with LSTMs.
- **Attention Mechanism**: Improves translation quality by focusing on relevant input words.
- **Preprocessing Pipeline**: Tokenization, padding, and encoding of sentences.
- **Training and Evaluation**: Model is trained on a dataset of English-Hindi sentence pairs.
- **Inference Module**: Generates Hindi translations for given English sentences.

## Model Architecture
- **Encoder**: LSTM-based model encodes English sentences into a context vector.
- **Decoder**: LSTM with Attention decodes the context vector into Hindi translations.
- **Attention Layer**: Helps the model focus on relevant words during translation.

## Dependencies
- Python 3.x
- TensorFlow/Keras
- NumPy
- Pandas
- NLTK (for text preprocessing)

## Installation
```bash
pip install tensorflow numpy pandas nltk
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/its308/Eng-to-Hi_Translator.git
   cd Eng-to-Hi_Translator
   ```
2. Run the Jupyter Notebook `Translator.ipynb` to train the model and test translations.

## Dataset
- The model is trained on a dataset of English-Hindi sentence pairs.
- Dataset preprocessing includes tokenization, padding, and vocabulary creation.

## Sample Translation
**Input (English)**: "How are you?"
**Output (Hindi)**: "आप कैसे हैं?"

## Future Improvements
- Train on a larger dataset for better accuracy.
- Experiment with Transformer-based models like BERT or MarianMT.
- Deploy as a web application using Flask/Streamlit.

## Author
Developed by [Itisha Choudhary](https://github.com/its308).

## License
This project is open-source and available under the MIT License.

 
