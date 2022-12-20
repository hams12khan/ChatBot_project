# ChatBot_project

A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human.
Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. 
There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.

In this Python project with source code, we are going to build a chatbot using deep learning techniques. 
The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. 
We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
the file structure and the type of files we will be creating:

Intents.json – The data file which has predefined patterns and responses.
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
Classes.pkl – The classes pickle file contains the list of categories.
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.



