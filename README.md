# Capstone_2_E_Commerce
In this project, we tackle the challenge of automating product categorization for e-commerce platforms. Text documents, especially product descriptions, contain valuable information that can influence market trends and investment flows. However, manually categorizing products into specific types is time-consuming and resource-intensive.

This project developed a a predictive classification model for e-commerce using a deep learning approach with a Bi-LSTM architecture in Natural Language Processing (NLP) to automatically classify product descriptions into four distinct categories; 'Electronics', 'Household', 'Books' and 'Clothing & Accessories'

## Architecture Model 
![architecture](https://github.com/user-attachments/assets/0a540d43-928f-4b6e-b9f9-768b4e8a6364)
## Results
### Training Loss
![tensorboard_training_loss](https://github.com/user-attachments/assets/ecb4195f-c54f-4ab6-a91e-158b89f33513)
### Training Accuracy
![tensorboard_training_accuracy](https://github.com/user-attachments/assets/dc30614e-a208-426c-81dd-c0df2b5685b2)
### Evaluation
![evaluation - accuracy](https://github.com/user-attachments/assets/8fed4e4d-9441-4108-ba7e-ecd90dbf76f0)
![evaluation - f1 score   model inference](https://github.com/user-attachments/assets/f41ee5ce-0bc7-4fc0-9693-5110c0daf5ae)
### Accuracy Graph
![accuracy graph](https://github.com/user-attachments/assets/84e38dde-0dc4-4ea3-9126-0682523d95b1)
## Discussion
1) The NLP model uses tokenization, padding & truncating and embedding to process the text data. 
2) The model uses LSTM and obtains an accuracy of 97.1% which is more than 85%.
3) The F1 score of this model is 0.99 which is above 0.7.  
4) The model was saved in .h5 format while the tokenizer is saved using .json.
Conclusion: The model is able to predict and categorize the unseen products into 4 categories.
## Credits
Kaggle - https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification



