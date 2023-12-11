# Language_Translation_Service_English_to_French

## Project Title
Language Translation Service

## Project Description
This project focuses on developing a neural machine translation model for translating text from English to French. It leverages advanced techniques like sequence-to-sequence architecture, bidirectional LSTM, and attention mechanisms to accurately capture linguistic details.

## Technologies and Techniques
- **Models**: Seq2Seq with GRU, Seq2Seq with Bidirectional LSTM and Attention Mechanism, BERT for sentiment classification.
- **Optimizers**: Adam, SGD, RMSprop, AdamW.
- **Loss Functions**: CrossEntropyLoss, NLLLoss.
- **Evaluation Metrics**: BLEU Score, Accuracy.

## Performance Evaluation
The model's performance was evaluated using BLEU scores and accuracy metrics. The Seq2Seq model with Bidirectional LSTM and Attention Mechanism using the Adam Optimizer and Cross-Entropy Loss Function achieved the highest BLEU score of 35.6.

## Google Cloud Platform Demo
The project's demo is hosted on Google Cloud Platform (GCP) and can be accessed at http://35.245.152.69:5000/. The interface was developed using Flask, HTML, and CSS.

## Requirements
To run this project, ensure the following libraries and packages are installed:
- Python 3.x
- pandas
- torch
- torch.nn
- torch.optim
- torch.utils.data (Dataset, DataLoader)
- torch.nn.utils.rnn (pad_sequence)
- torchtext.data.utils (get_tokenizer)
- torchtext.vocab (build_vocab_from_iterator)
- spacy
- matplotlib.pyplot
- torch.nn.functional (F)
- math
- tqdm
- seaborn
- collections (Counter)



## Future Work
- **Expanding Language Support**: Extending the model to support additional language pairs beyond English and French.
- **Improving Model Accuracy**: Implementing more sophisticated neural network architectures to enhance translation accuracy and fluency.
- **Optimization for Speed**: Optimizing the model for faster translation times, making it more suitable for real-time applications.
- **User Interface Enhancements**: Developing a more intuitive and user-friendly interface for the translation service.
- **Incorporating Feedback Loop**: Implementing a system for users to provide feedback on translations, which can be used to further train and refine the model.
- **Exploring Advanced NLP Techniques**: Investigating the use of newer NLP techniques and models to improve translation quality.

## Dataset
The dataset used in this project is an English-French translation dataset, consisting of parallel sentences in both languages. It's essential for training the neural machine translation model. The dataset can be accessed [here](https://www.kaggle.com/datasets/devicharith/language-translation-englishfrench).


