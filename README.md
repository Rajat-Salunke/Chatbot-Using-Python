This project demonstrates how to build a simple chatbot using Python, NLTK, and Keras. It utilizes a retrieval-based model trained on predefined intents and responses to interact with users.

Features
Retrieval-Based Chatbot: Selects appropriate responses based on user input patterns.

Deep Learning Model: Employs a Sequential neural network with Dense layers.

Natural Language Processing: Utilizes NLTK for text preprocessing tasks like tokenization and lemmatization.

GUI Interface: Provides a user-friendly graphical interface for chatbot interaction.

Project Structure
intents.json: Contains predefined intents with corresponding patterns and responses.

train_chatbot.py: Script to preprocess data, train the model, and save necessary files.

chatgui.py: Implements the GUI for user interaction with the chatbot.

chatbot_model.h5: Saved trained model.

words.pkl & classes.pkl: Serialized Python objects for vocabulary and class labels.

Prerequisites
Ensure the following Python packages are installed:

nltk

keras

tensorflow

numpy

pickle

Install them using pip:

bash
Copy
Edit
pip install nltk keras tensorflow numpy
Additionally, download the NLTK data required:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('wordnet')
Getting Started
Clone the Repository: Download or clone the project files to your local machine.

Prepare the Data: Ensure intents.json is in the project directory.

Train the Model: Run train_chatbot.py to preprocess data and train the model.

Launch the Chatbot: Execute chatgui.py to start the chatbot interface.
