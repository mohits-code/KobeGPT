# KobeGPT

This project features a chatbot designed to embody the "Mamba Mentality" of Kobe Bryant. The chatbot responds to user prompts with tough, motivational, and insightful advice, particularly focusing on code-related assistance. Responses are generated using a language model and delivered via a web-based interface.

## Architecture

### Data Collection
A chatbot interface is provided for users to input prompts. These prompts are sent to a backend server that processes the input and generates responses using a language model.

### Data Storage
Conversation history is stored in memory to offer contextually relevant responses as the conversation progresses.

### Data Processing
Input prompts are processed and formatted to include the entire conversation history. This formatted input is then sent to the backend server, which uses the language model to generate the response.

### EDA (Exploratory Data Analysis)
User interactions with the chatbot are analyzed to fine-tune the response generation process. This analysis involves examining the types of prompts received and the corresponding responses to ensure alignment with Kobe Bryant's "Mamba Mentality."

### Search Algorithm
A sequential search algorithm is used to process the conversation history and generate relevant responses. The history is concatenated into a single prompt string, which is then fed into the language model.

### Deployment
The chatbot is deployed using Gradio, providing a clean and simple UI for interaction. The backend server is hosted locally and handles API requests for generating responses.

## Technologies Used
- **Gradio**: For creating the web-based user interface.
- **requests**: For making HTTP requests to the backend API.
- **Python**: The primary programming language used.
- **codellama**: The language model used for generating responses.
