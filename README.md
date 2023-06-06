# Spam Classifier
![sms](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/5bb489bc-7561-4520-ac4e-30c28eed5927)

## Exploratory Data Analysis (EDA):
After cleaning the data, exploratory data analysis was performed to gain insights into the characteristics and distribution of our SMS dataset. This step helped understand the composition of spam and non-spam messages, identify any class imbalances, and explore other relevant patterns or trends within the data. WordCloud and Seaborn were utilized for visualizations and statistical analysis techniques to extract meaningful information from the dataset.
![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/63d4ea41-b3da-42b9-8b25-e33a8e392a45)
![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/693da1ac-8a12-449f-a25d-844ef64b4974)

## Data Cleaning and Text Preprocessing using NLP:
To prepare the SMS text data for classification, text preprocessing using various NLP techniques. This involved converting the text to lowercase to ensure uniformity and removing any special characters or numerical values that might not contribute to spam classification. Techniques like stemming or lemmatization to reduce words to their base forms and improve the efficiency of the subsequent modeling steps. NLTK library was utilized for data cleaning. NLTK is a powerful Python library that provides various tools and functionalities for natural language processing tasks. NLTK's functions to remove any unwanted characters, punctuation, and stop words from our SMS dataset. Additionally, tokenization was used to split the text into individual words, enabling further analysis and preprocessing.

![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/dd5e997c-06f3-40c2-a3ce-7f7e2fc60666)

![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/87044adb-ba5f-49ed-aa30-8ddf736903b3)

## Model Building using GaussianNB and MultinomialNB:
With the preprocessed data, multiple models were built for SMS spam classification models. The two best performing models were Naive Bayes classifiers, namely GaussianNB and MultinomialNB, which are commonly used for text classification tasks. GaussianNB assumes a Gaussian distribution for the features, whereas MultinomialNB is suitable for discrete features such as word counts. These models were trained on the preprocessed SMS dataset to learn the patterns and distinguish between spam and non-spam messages.
![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/c61f797c-40fa-4850-9592-4ee25b467b7f)

## Evaluation based on Precision Score:
To evaluate the performance models, precision score was the best metric. Precision measures the proportion of correctly classified spam instances out of the total instances predicted as spam. It helps us determine the accuracy of the model's positive predictions and is especially important in spam classification to minimize false positives (i.e., classifying a non-spam message as spam). The calculated precision scores for both GaussianNB and MultinomialNB and compared their performance to identify the model with the higher precision.

## Web Application Development using Streamlit:
Finally, a web application was developed using Streamlit to provide a user-friendly interface for SMS spam classification. Streamlit is a Python library that simplifies the process of building interactive web applications. Our web application allowed users to input an SMS message, and the trained model (selected based on its precision score) would classify it as spam or non-spam. The application provided real-time predictions and an intuitive interface to enhance user experience.
![image](https://github.com/SurajspatiL99/Spam_Classifier/assets/101862962/d744e59e-fbdd-415c-b58c-bce3d7a8c515)

## Conclusion
In conclusion, this project involved cleaning and preprocessing SMS data using NLTK, performing EDA to gain insights, building classification models using GaussianNB and MultinomialNB, evaluating model performance based on precision scores, and developing a user-friendly web application using Streamlit for real-time SMS spam classification. The application can be a valuable tool for users to identify and filter spam messages efficiently.

