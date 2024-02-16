# Comments-Toxicity-Classification-Deep-Learning-NLP-
Toxic comments come in various flavors: hate speech, obscenity, threats, and offensive language. Detecting them manually is a Herculean task. Enter natural language processing (NLP) and deep learning—the dynamic duo that equips us to tackle this challenge head-on.

# About Me
I am a computer science engineer specialized in data science and machine learning, I offer my services on 'Upwork' and 'Freelancer'. you can check out my profile [https://www.freelancer.com/u/jalilb9] [https://www.upwork.com/freelancers/~01c41cc0b08423ddb3]

# Project Description 
The goal is to create a model that can accurately classify text comments, and evaluate them based on the level of toxicity. Toxicity encompasses various forms, including obscenity, hate speech, threats, and offensive language. By developing an effective classifier, we can enhance online safety and promote healthier interactions.

# Data Collection and Preprocessing
The dataset used for the purpose of this project is the 2018 kaggle's comments toxicity classification challenge, note that only the train.csv file is used for both training and testing the deep learning model
Before diving into model training, we preprocess the raw text data by tokenizating it using TextVectorization method from Keras, limiting the vocabulary by 1800 words and maximum of 200k samples

# Training and Evaluation
We split our dataset into training, validation, and test sets. During training, the model learns to differentiate different level of toxicity in the comments. We monitor metrics such as categorical accuracy, precision, recall to assess performance. 

# Conclusion
Building a toxic comment classification system involves a harmonious blend of NLP, deep learning, and data engineering. By controlling and combatting toxicity, we contribute to a more respectful and constructive online environment—one where discussions thrive without fear of harmful comments.
