# Simple Python Chatbot-----
This is a simple chatbot implemented in Python using natural language processing techniques. The chatbot is capable of engaging in conversations with users, responding to greetings, and generating appropriate responses based on user input.

# Features-----
Greeting Functionality: The chatbot can greet users with a variety of responses based on predefined greetings.
Response Generation: Utilizes TF-IDF vectorization and cosine similarity to generate responses to user input.
Conversation Protocol: Implements a conversation loop where the chatbot interacts with the user until the user ends the conversation by saying "bye".
Text Preprocessing: Preprocesses the text data by lemmatizing and normalizing it for better understanding and response generation.

# Getting Started-----
To run the chatbot locally, follow these steps:
Clone this repository to your local machine.
Ensure you have Python installed on your system.
Install the required dependencies by running pip install -r requirements.txt.
Run the chatbot script by executing python chatbot.py.
Start interacting with the chatbot by entering text inputs.

# Example Usage-----
User: hello
Chatbot: hi there

User: How are you?
Chatbot: I am sorry! I don't understand you

User: What can you do?
Chatbot: I am a simple chatbot. I can respond to greetings and engage in basic conversation.

User: bye
Chatbot: Goodbye! Take care <3
