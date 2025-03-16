# Sentiment_analysis
Used deep learning(LSTM) for Sentiment Analysis
This project is a sentiment analysis model that uses a Bidirectional LSTM to classify text as positive or negative. It is trained on the IMDB movie reviews dataset.

Features
Uses LSTM-based deep learning model
Trained on the IMDB dataset
Achieves around 82-85% accuracy
Can predict sentiment for custom text input
Requirements
To run this project, you need:

Python 3.x
Google Colab or you can also do it locally if possible for you, or else any cloud platform should do the job.
TensorFlow
NumPy
Matplotlib
To install required libraries, 
run: pip install tensorflow numpy matplotlib

How to Run
Open Google Colab
Upload the sentiment_analysis.ipynb notebook
Run the notebook step by step
Train the model and test with custom text
Testing the Model
After training, you can test it with custom
text: review = "The movie was fantastic! I really loved it."
print(predict_sentiment(review))
Saving and Loading the Model
To save the trained model:
model.save("sentiment_model.h5")
To load the model:
from tensorflow.keras.models import load_model
model = load_model("sentiment_model.h5")
