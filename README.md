# Language_Translation_Service_English_to_French

## Project Title
Language Translation Service

## Team Members and Affiliation
- Vikas Manchikant (vikasman@buffalo.edu)
- Priyanka Chakraborty (priyank2@buffalo.edu)
- Bhanu Sahith Bonthula (bhanusah@buffalo.edu)
- Department of Computer Science, University at Buffalo

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

## How to Use
(Instructions on setting up, installing dependencies, and running the project.)

## Contributing
(Information on how others can contribute to the project, if applicable.)

## License
(Information about the project's license.)

## Contact Information
For further inquiries or contributions, please contact:
- Vikas Manchikant: vikasman@buffalo.edu
- Priyanka Chakraborty: priyank2@buffalo.edu
- Bhanu Sahith Bonthula: bhanusah@buffalo.edu
