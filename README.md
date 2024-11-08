# Capstone_2_E_Commerce
In this project, we tackle the challenge of automating product categorization for e-commerce platforms. Text documents, especially product descriptions, contain valuable information that can influence market trends and investment flows. However, manually categorizing products into specific types is time-consuming and resource-intensive.

This project developed a a predictive classification model for e-commerce using a deep learning approach with a Bi-LSTM architecture in Natural Language Processing (NLP) to automatically classify product descriptions into four distinct categories; 'Electronics', 'Household', 'Books' and 'Clothing & Accessories'

## Architecture Model 
![architecture](https://github.com/user-attachments/assets/2e292baa-68f8-47b9-9385-5a3773cb4764)

## Results
### Training Loss
![tensorboard_training_loss](https://github.com/user-attachments/assets/f0483d8b-839d-421b-a4d2-e97bf34d2561)
### Training Accuracy
![tensorboard_training_accuracy](https://github.com/user-attachments/assets/8c89f75b-af74-4ba5-be71-1c94688fef27)
### Evaluation
![evaluation - accuracy](https://github.com/user-attachments/assets/899c027b-cf1f-4f91-8a33-08e4b200ab4f)
![evaluation - model inference](https://github.com/user-attachments/assets/97c08b56-9123-4f46-afa6-8442570c1fe6)
### Classification Report
![classification report](https://github.com/user-attachments/assets/fd8ad3b0-7bfb-4ee3-ab4d-4ed8e4e7abac)
### Accuracy Graph
![accuracy graph](https://github.com/user-attachments/assets/bd593dbd-abf7-41e8-b2fd-9a122b72fe10)
### Loss Graph
![loss graph](https://github.com/user-attachments/assets/9cde74a2-2be3-4ecc-946b-adfe2c0040b8)

## Discussion
1) The NLP model uses tokenization, padding & truncating and embedding to process the text data. 
2) The model uses LSTM and obtains an accuracy of 96.3% which is more than 85%.
3) The F1 score of this model is 0.96 which is above 0.7.  
4) The model was saved in .h5 format while the tokenizer is saved using .json.

Conclusion: The model is able to predict and categorize the unseen products into 4 categories.
## Credits
Kaggle - https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification



