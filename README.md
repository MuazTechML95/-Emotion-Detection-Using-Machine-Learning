# -Emotion-Detection-Using-Machine-Learning
This project focuses on Emotion Classification using textual data. The main goal was to identify the emotion expressed in a given sentence (e.g., happiness, anger, sadness, fear, etc.) by applying various machine learning techniques.

🚀 Project Overview

Emotion recognition is a crucial task in Natural Language Processing (NLP), helping machines understand human emotions from text.
The dataset was imbalanced, meaning some emotions had more examples than others, which made the training process challenging.

To address this, several preprocessing and balancing techniques were applied to achieve a stable and high-performing model.

🧠 Workflow
1️⃣ Data Preprocessing

Cleaned the text (removed stopwords, punctuation, and unnecessary symbols).

Converted text into numerical form using TF-IDF Vectorization.

2️⃣ Handling Imbalanced Data

Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the emotion classes and improve model fairness.

3️⃣ Model Training

Trained multiple models including:

Logistic Regression

Random Forest Classifier

Extra Trees Classifier

Random Forest achieved the best performance among all models.

4️⃣ Model Deployment

Created a Flask Web App to allow users to input text and get real-time emotion predictions.

Used Ngrok for public access to the local Flask app.

🧰 Tools & Technologies Used

Python 🐍

Pandas, NumPy, Scikit-learn

NLTK (for text cleaning and tokenization)

Imbalanced-learn (SMOTE)

Flask (for web deployment)

Pyngrok (for temporary online hosting)

🎯 Results

✅ Model Accuracy: 80%
✅ Improved balance across all emotion categories using SMOTE
✅ Successfully deployed the model using Flask and Ngrok

💡 Key Takeaways

Learned how to handle imbalanced datasets effectively using SMOTE.

Strengthened understanding of TF-IDF, Feature Scaling, and Machine Learning Pipelines.

Gained hands-on experience in web integration of ML models.
