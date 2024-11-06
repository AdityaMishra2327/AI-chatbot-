
# Chatbot with Gemini API in React

This project is a simple chatbot interface built with **React** and powered by the **Gemini API** for conversational AI. It allows users to interact with the chatbot and receive intelligent, context-aware responses.

## Features
- **Responsive Chat Interface**: A React-based UI for a seamless chatbot experience.
- **AI-Powered Conversations**: Utilizes the Gemini API to provide natural language understanding and responses.

## Requirements
- Node.js (v14 or higher)
- Gemini API Key (available from the Gemini API platform)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AdityaMishra2327/AI-chatbot-.git
   cd AI-chatbot-
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure the API Key**:
   Create a `.env` file in the project root and add your Gemini API key:
   ```plaintext
   REACT_APP_GEMINI_API_KEY=your_gemini_api_key_here
   ```

## Usage

1. **Run the App**:
   ```bash
   npm start
   ```
   This will start the React application, and the chatbot interface should be accessible in your browser at `http://localhost:3000`.

2. **Chat with the Bot**: Type your message in the chat input, and the chatbot will respond based on the Gemini API's natural language processing capabilities.

## Project Structure
- `src/components/Chatbot.js`: Main chatbot component handling interactions.
- `src/api/gemini.js`: API utility for interacting with the Gemini API.

## Contributing
Feel free to submit issues or pull requests to improve the chatbot's features or UI.

---

This version focuses on key steps for setup and usage in a React environment. Let me know if you'd like to add more!
