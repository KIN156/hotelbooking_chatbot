# hotelbooking_chatbot

This project implements a simple chatbot using natural language processing techniques. It can understand and respond to various user queries based on predefined intents.

# Getting Started
To get started with the chatbot, follow these instructions:

# Prerequisites
Python 3.x
Required libraries: 
nltk
keras
numpy
tensorflow


# Installation
Clone the repository or download the source code.
Install the required dependencies by running the following command:
pip install -r requirements.txt


Train the chatbot model by running the train_chatbot.py script:
python train_chatbot.py
This will generate the necessary training data and save the trained model as chatbot_model.h5.

Start the chatbot GUI by running the chatgui.py script:
python chatgui.py
This will launch a simple graphical interface where you can interact with the chatbot.

Enter your message in the text input field and click the "Send" button to send it to the chatbot. The chatbot will process the message and display its response in the chat window.

# Files
train_chatbot.py: Script to train the chatbot model using the intents defined in intents.json.

chatgui.py: Graphical user interface for interacting with the chatbot.

intents.json: JSON file containing the predefined intents and their corresponding patterns and responses.

words.pkl: Pickle file containing the preprocessed words used in training.

classes.pkl: Pickle file containing the unique classes (intents) used in training.

chatbot_model.h5: Trained chatbot model saved in the Keras HDF5 format.

# Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
