This project demonstrates the development of a text generation system using deep learning techniques, specifically leveraging an LSTM-based neural network. The model is trained on "The Adventures of Sherlock Holmes," learning to predict the next word in a sequence and generate coherent, contextually relevant text. This project combines multiple technical foundations from natural language processing (NLP) and deep learning. Key components include:

- **Natural Language Processing (NLP) Techniques**: Text preprocessing, tokenization, and n-gram sequence creation to prepare the dataset for model training.
- **Recurrent Neural Networks (RNNs) and LSTMs**: The core architecture is built using Long Short-Term Memory (LSTM) layers, which are designed to capture sequential dependencies in text and handle long-range context effectively.
- **Model Architecture**: The neural network includes:
  - An Embedding Layer to transform words into dense numerical vectors.
  - An LSTM Layer with 150 units for sequence learning.
  - A Dense Layer with softmax activation to predict the next word from the vocabulary.
- **Performance Metrics**: The model is trained using categorical crossentropy as the loss function and Adam optimizer, achieving an accuracy of **87.54%** and a loss of **0.4756** after 100 epochs.
- **Tools and Libraries**: TensorFlow/Keras for model development, NumPy for data manipulation.
- 
This project serves as an excellent foundation for more advanced applications such as conversational agents, text summarization, or creative writing systems, and is ideal for those interested in exploring LSTMs and sequence-based learning in NLP.
