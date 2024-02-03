# Sentiment-Analysis-using-LLaMa
This project involves analysis of sentiment of financial statements using LLaMa model.

### Dataset: 
The dataset is obtained from kaggle which contains around 5000 samples of data. The data is also available in the repository.

Quantized LLaMa model have been used in this project, due to computational constraints. Original model can be used if have enough computational resources. It was observed that fine tuning LLaMa model for our data drastically improved the accuracy of the model from 0.37 to 0.85. 

![image](https://github.com/darshanrk02/Sentiment-Analysis-using-LLaMa/assets/97380105/c08b5c5f-c284-46d4-8008-cb9fd9a91e0d)
![image](https://github.com/darshanrk02/Sentiment-Analysis-using-LLaMa/assets/97380105/c7a78b9f-471c-4d5d-ab3a-d0191ee9bad8)

The images show the classification report before and after fine tuning the LLaMa model.

## Getting started
1. Download all the dependencies
2. Use GPU if available, or run it on colab
3. Fine tune it to your own task

