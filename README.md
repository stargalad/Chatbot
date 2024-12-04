# Chatbot
Chatbot using huggingface transforners and torch

Functionalities
Text Input and Output: The chatbot accepts text input from the user and returns a corresponding text output.

Contextual Understanding: The chatbot maintains conversation history to provide context for generating responses.

Model Selection: Utilizes the facebook/blenderbot-400M-distill model for generating responses, which is suitable for conversational tasks.

Interactive Chat: Users can engage in a back-and-forth conversation with the chatbot through a terminal interface.

Libraries and Tools Used
Python: The programming language used to implement the chatbot.

Hugging Face Transformers: A library that provides pre-trained models and tools for natural language processing (NLP).

Key Classes Used:
AutoTokenizer: For tokenizing input text into a format suitable for the model.
AutoModelForSeq2SeqLM: For loading and interacting with the selected language model.
Torch: A deep learning library that provides the backend for running the model.



