# AI-CHATBOT-WITH-NLP

COMPANY; CODETECH IT SOLUTIONS

NAME; KAMALESHWARAN.R

INTERS ID; CT08PPJ

DOMAIN; PYTHON

DURATION; 4 weeks  from January 25th, 2025 to February 25th, 2025.  

MENTOR; NEELA SANTOSH

DESCRIPTION EXPLANATION;

nltk.download('punkt')
nltk.download('stopwords')

# Load spaCy English model
nlp = spacy.load("en_core_web_sm")

# Sample predefined responses
responses = {
    "greeting": ["Hello!", "Hi there!", "Hey!", "Hi, how can I help you?"],
    "goodbye": ["Goodbye!", "See you later!", "Bye!", "Take care!"],
    "weather": ["I'm not a meteorologist, but I hope it's sunny!", "It might rain, check your weather app!"],
    "name": ["I'm a chatbot!", "You can call me ChatBot.", "I'm your virtual assistant."],
    "default": ["I'm not sure I understand.", "Can you rephrase that?", "Sorry, I don't have an answer."]
}



Chatbot Functionality
1. Text Preprocessing: The preprocess_text_nltk function tokenizes the user input, converts it to lowercase, removes non-alphanumeric characters, and removes stopwords.
2. Intent Identification: The get_intent_spacy function uses spaCy to identify the intent behind the user input. It checks for specific lemmas (e.g., "hello", "bye", "weather") to determine the intent.
3. Response Generation: The chatbot_response function generates a response based on the identified intent. It selects a random response from a predefined list of responses for each intent.
4. Chatbot Loop: The chat function runs the chatbot in an infinite loop, prompting the user for input and generating responses until the user types "exit".

Code Structure
The code is structured into several functions, each with a specific responsibility:

1. preprocess_text_nltk: Text preprocessing
2. get_intent_spacy: Intent identification
3. chatbot_response: Response generation
4. chat: Chatbot loop

Dependencies
The code uses the following dependencies:

1. NLTK (Natural Language Toolkit)
2. spaCy (Modern Natural Language Processing)
3. Python 3.x

Improvements
Some potential improvements to the chatbot include:

1. More advanced intent identification: Using machine learning models or more sophisticated NLP techniques to improve intent identification accuracy.
2. Contextual understanding: Allowing the chatbot to understand the context of the conversation and respond accordingly.
3. More diverse responses: Adding more responses to each intent category to make the chatbot more engaging and less repetitive.
4. Error handling: Implementing error handling mechanisms to handle unexpected user input or errors in the chatbot's response generation.

   OUTPUT;
          ![Image](https://github.com/user-attachments/assets/4d93ee9c-7de2-4c3e-929c-424731365c08)
