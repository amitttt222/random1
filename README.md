# DL-Assignment-3
# train a CNN model from scratch and learn how to tune the hyperparameters and visualize filters
    Assignment 3, Course Assignment of CS6910 Deep Learning IIT Madras
## Abstract<br/>
The goal of this assignment is threefold: (i) learn how to model sequence-to-sequence learning problems using Recurrent Neural Networks (ii) compare different cells such as vanilla RNN, LSTM and GRU (iii) understand how attention networks overcome the limitations of vanilla seq2seq models
## Dataset<br/>
 Aksharantar dataset released by AI4Bharat is used in this assignment. This dataset contains pairs of the following form:
x,y
ajanabee,अजनबी (this is an example of english to hindi dataset)
i.e., a word in the native script and its corresponding transliteration in the Latin script (how we type while chatting with our friends on WhatsApp etc).. The dataset is divided into training, validation, and testing sets, with the training set containing 80% data, the validation set containing 20% data, and the testing set.
## Objective<br/>
dataset and achieve high accuracy by tuning hyperparameters. this is the problem of mapping a sequence of characters in one language to a sequence of characters in another. Notice that this is a scaled-down version of the problem of translation where the goal is to translate a sequence of words in one language to a sequence of words in another language (as opposed to a sequence of characters here).. Through this assignment, we will learn how to fine-tune hyperparameters, experiment with different model architectures, and interpret the results to improve model performance.
### Folder Structure<br/>
these below files contain the required code for third assignment<br/>
(assignment-3-v4.ipynb) ------- This code file is for training the vanilla model and This code file defines a transliteration model using a sequence-to-sequence architecture without attention mechanism. It preprocesses the data, creates vocabulary mappings, and prepares the train, validation, and test datasets. It then trains the model, logs the training progress using Weights & Biases, and evaluates the model on the validation set. Finally, it saves the best model based on validation accuracy and logs the final training and validation metrics. <br/>
(assignment-3-att-v5.ipynb)-------This code file is for training the attention model and This code file defines a transliteration model using a sequence-to-sequence architecture with attention mechanism. It preprocesses the data, creates vocabulary mappings, and prepares the train, validation, and test datasets. It then trains the model, logs the training progress using Weights & Biases, and evaluates the model on the validation set. Finally, it saves the best model based on validation accuracy and logs the final training and validation metrics.<br/>
(predictions_attention)---------<br/>
(predictions_vanilla)------------<br/>
(predictions-attention-code.ipynb)--------<br/>
(predictions-vanilla-code.ipynb)----------<br/>
(train_attention.py)----------<br/>
(train_vanilla.py)-------<br/>
README.md<br/>
## Results<br/>
The best test accuracy on Aksharantar dataset released by AI4Bharat achieved on vanilla model is *37.76%* while on attention model the  test accuracy is *40.94%*. The explanation and results of subproblems 
can be accessed (https://wandb.ai/cs22m010/DL_Assign_3_attention/reports/CS6910-Assignment-3--Vmlldzo0NDI1NDE2)
