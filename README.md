# CricBot

CricBot is an AI-powered cricket assistant built using Streamlit, Groq API, FAISS, and speech recognition. It leverages a knowledge base and an LLM to provide answers to complex cricket-related queries.

## Features
- *Text & Voice Input*: Users can interact via text or voice commands.
- *Knowledge Base Integration*: Utilizes a structured cricket knowledge base for information retrieval.
- *FAISS for Similarity Search*: Retrieves relevant information using FAISS for efficient similarity-based search.
- *LLM-Powered Responses*: Uses Groq's LLM to provide detailed cricket-related answers when the knowledge base is insufficient.
- *Text-to-Speech Output*: Converts AI responses to audio for an enhanced user experience.


## Running the Application
sh
streamlit run app.py


## How It Works
1. Users enter their query via text input or voice recording.
2. The system retrieves relevant information from the knowledge base using FAISS.
3. If no relevant context is found, the Groq API generates a response.
4. The response is displayed in text and optionally converted to speech.

## File Structure

CricBot/
│── cricket.json          # Knowledge base file
│── app.py                # Main Streamlit application
│── requirements.txt      # Dependencies
│── .streamlit/secrets.toml # API key configuration


## Future Enhancements
- Expand the knowledge base with more detailed cricket statistics.
- Improve voice recognition accuracy.
- Implement user personalization based on query history.

## Contributing
Feel free to open issues or submit pull requests to improve CricBot!
