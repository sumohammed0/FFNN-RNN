# FFNN-RNN
CS 6375: FeedForward Neural Network and Recurrent Neural Network  

To Run:  
- Unzip Data_Embedding  
- Specify hyperparams  

**FFNN**  
example run:
`python ffnn.py --hidden_dim 28 --epochs 10 --train_data ./Data_Embedding/training.json --val_data ./Data_Embedding/test.json --test_data ./Data_Embedding/testing.json`

**RNN**  
example run: 
`python rnn.py --hidden_dim 32 --epochs 10 --train_data ./Data_Embedding/training.json --val_data ./Data_Embedding/test.json --test_data ./Data_Embedding/testing.json`
