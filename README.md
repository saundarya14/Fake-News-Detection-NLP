# Fake-News-Detection-NLP
This project addresses the challenge of detecting fake news on the internet by utilizing advanced deep-learning techniques. We focused on two models: LSTM (Long Short-Term Memory) and BERT (Bidirectional Encoder Representations from Transformers), chosen for their ability to understand contextual and semantic nuances in text. Our analysis showed that the LSTM model achieved an accuracy of 96.70%, while the BERT model performed even better, achieving 98.21% accuracy with excellent precision and recall rates. These results demonstrate the effectiveness of these models in enhancing the accuracy of fake news detection systems, providing a promising approach to safeguarding the integrity of online information.

Dependencies to import: 

Pandas version: 2.0.3
NumPy version: 1.25.2
TensorFlow version: 2.15.0
Scikit-Learn version: 1.2.2
Matplotlib version: 3.7.1
Seaborn version: 0.13.1
PyTorch version: 2.2.1+cu121
Transformers version: 4.40.1


Zip file: 

1. Test_Script.ipynb
2. Preprocessed_test_set.csv (LSTM)
3. processed_test_set_bert.csv
4. best_bert_model.pth
5. best_lstm_model.h5

 
Steps to run:

- Exact all of the files in the same place 
- Import all of the libraries mentioned above
- Open the Test_Script.ipynb
- Load the Preprocessed_test_set.csv (LSTM) and best_lstm_model.h5 in the Test_Script.ipynb
- Then Load processed_test_set_bert.csv and best_lstm_model.h5 in the Test_Script.ipynb
