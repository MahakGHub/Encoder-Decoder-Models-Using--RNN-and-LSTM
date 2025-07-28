# Encoder-Decoder-Models-Using--RNN-and-LSTM
This project is a simple implementation of an Encoder-Decoder model using LSTM to perform English to French translation on a small set of sentence pairs. Built and tested in Google Colab, the model demonstrates how sequence-to-sequence learning works using deep learning techniques.
- What I Did
Created a toy dataset with 5 English-French sentence pairs
Used Keras Tokenizer to convert text to sequences and padded them
Built an Encoder-Decoder architecture using LSTM layers
Trained the model for 10 epochs while printing the loss after each epoch
Performed greedy decoding to translate 5 test English sentences into French
Visualized the training loss using Matplotlib

-Tools & Libraries
TensorFlow / Keras
NumPy
Matplotlib
Google Colab

-How to Run
Open the .ipynb notebook in Google Colab or Jupyter Notebook
Run all cells in order

Observe:
Training loss printed after each epoch
Translations for 5 English test sentences

📝 Example Output
yaml
Copy
Edit
Input: hi             → Predicted: salut  
Input: how are you    → Predicted: comment ça va  
Input: i am fine      → Predicted: vais bien  
Input: thank you      → Predicted: merci  
Input: good morning   → Predicted: bonjour  
-Author
Mahak Gupta
2nd Year B.Tech CSE | GenAI Explorer
