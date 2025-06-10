This notebook implements a machine learning model for text generation using Hugging Face.
For this script, it is required to have a Hugging Face account so that the user can acquire the necessary HF API token. 
Then, the user must set the token as a variable, HF_TOKEN in this example. 
The user must import the os module, as well as the InferenceClient class from Hugging Face. 
This project uses the Cohere model to generate text based on user input using InferenceClient.
The user is prompted to enter a message, and the model generates the response utilizing the CohereLabs/c4ai-command-r-plus model..
In order to quit the loop, the user must type "exit". 
This is all dependent upon having the right packages installed, stated earlier, os and InferenceClient class from Hugging Face. 
