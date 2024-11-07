# BookGPT - Virtual Book Assistant

BookGPT is a virtual assistant with extensive knowledge of the literary world. It can answer any questions about books, authors, genres, and more, all in under 100 words. The app is built with Streamlit, offering an interactive and responsive interface where users can engage in a conversation with BookGPT.

## Features
- **Instant Book Knowledge**: BookGPT knows book titles, authors, genres, and key facts, making it a powerful resource for book enthusiasts.
- **Conversational Interaction**: The app allows users to ask questions directly and receive concise responses.
- **Conversation History**: The app maintains a session-based conversation history, so users can view past questions and answers within a session.

## Installation

### Prerequisites
- **Python 3.8+** installed.
- **Streamlit** installed (`pip install streamlit`).

### Clone the Repository
```bash
git clone <repository_url>
cd BookGPT

Install Dependencies
bash
Copy code
pip install -r requirements.txt
Ensure requirements.txt includes streamlit and any other necessary packages like openai or other libraries you use in chatbot.py.

Usage
Run the Application

bash
Copy code
streamlit run app.py
Access the Application

Open a web browser and go to the URL provided in the terminal (typically http://localhost:8501).
File Structure
app.py: The main Streamlit file that sets up the interface, collects user input, and displays BookGPT's responses.
chatbot.py: Contains the response function, which processes the conversation history and returns BookGPT's answers based on user queries.
Code Overview
The main file app.py:

Initializes a session-based conversation history so users can view prior messages in the chat.
Displays the Streamlit chat input for users to type queries.
Uses the response function from chatbot.py to fetch answers based on the current conversation history.
Example Questions
"Who wrote Pride and Prejudice?"
"Tell me about The Great Gatsby."
"What are some famous books by George Orwell?"
Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or suggest new features.

License
This project is licensed under the MIT License.
An open api chat bot.
