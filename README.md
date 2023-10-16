# BERT-ISE244

## Comparing 3 pre-trained BERT-based models by performing Sentiment Analysis and Text Classification.

The field of NLP is fascinating, and the goal here is to contribute to the ongoing exploration and understanding of BERT. I have started the project by first  understanding the BERT model’s architecture and its pre-training, and further implemented and compared three of the famous variants of BERT on different datasets for different purposes. The goal was to compare the performance of these models and analyze how the performance varies based on the type of dataset and the task. The goal of the project  is to implement and analyze BERT, and to understand the performance of BERT variants: BERT(base), DistilBERT and RoBERTa on different datasets. 

## Task 1: Sentiment Analysis:
- BERT achieved an accuracy of 66.7%, and the model compiled in 16 minutes.
- DistilBERT achieved an accuracy of 66.3%,  compiling in under 8 minutes.
- RoBERTa achieved the best accuracy of 68.5%, with run time under 15 minutes. 

## Task 2: Text Classification:
- BERT achieved an accuracy of 77.8%, and the model compiled in 90 minutes.
- DistilBERT achieved an accuracy of 81.9%,  compiling in under 48 minutes.
- RoBERTa achieved the best accuracy of 85.7%, with run time under 65 minutes.

## Inferences:

- For both the sentiment analysis and text classification tasks, RoBERTa demonstrated superior performance in terms of accuracy compared to BERT and DistilBERT. Additionally, the runtime of models varied across the tasks. This was expected as RoBERTa was extensively trained on a larger number of parameters compared to BERT and DistilBERT. However, the trade-off here is longer compilation times. 

- BERT, which was the base, seems to be outclassed by its newer versions. Although the difference was not significant for sentiment analysis, DistilBERT and RoBERTA performed much better in text classification while also being much faster at compiling. So, it could be possible that the BERT model has difficulties classifying text if there are more than 3 classes involved.

- DistilBERT is the subtle winner here, which is faster at compilation while also not compromising significantly on accuracy. Overall, the choice of the model ultimately depends on the specific requirement of the task, whether it is faster compilation(DistilBERT) or better accuracy(RoBERTa). 
