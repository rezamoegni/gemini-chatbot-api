# Gemini-Powered Chatbot

This project is final assignment for AI Productivity and AI API Integration for Developers course by Hacktiv8. A full-stack, real-time chatbot that allows users to have a conversation with a Gemini-powered AI model. The application supports not only text-based chat but also the ability to upload various file types, including images, documents, and audio, for the AI to process.



---

## Features

- **Real-time Chat**: Engage in a live conversation with an AI.
- **Markdown Rendering**: AI responses are formatted using markdown to enhance readability.
- **Multi-modal Input**: Upload images, documents (PDF, DOCX), and audio files directly to the chat for the AI to analyze and respond to.
- **Clean UI**: A simple, modern, and responsive user interface built with Tailwind CSS.

---

## Tech Stack

### Frontend

- **HTML**: The core structure of the web application.
- **CSS**: Styled using a combination of custom CSS and the Tailwind CSS framework for a clean, mobile-first design.
- **JavaScript**: Vanilla JavaScript handles all client-side logic, including form submission, API calls, and dynamic DOM manipulation.
- **Showdown.js**: A library used to convert markdown responses from the AI into formatted HTML.

### Backend
- **Node.js**: Server-side runtime environment.
- **Express.js**: Handles routing and API endpoints.

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/rezamoegni/gemini-chatbot-api.git
cd gemini-chatbot-api

# Install dependencies
npm install

# Copy environment variables
cp dotenv-example .env

# Start the server
node index.js
```

---

## ⚙️ Environment Variables

Create a `.env` file based on `dotenv-example` and fill in the following:

```env
GEMINI_API_KEY=your_gemini_api_key
PORT=3000
```

- `GEMINI_API_KEY`: Your API key for accessing Gemini AI.
- `PORT`: Port number for the server (default: 3000).

---

## 📖 Usage

- Open the app in your browser.
- Type a message or upload a file (image, PDF, DOCX, audio).
- The AI will respond in real-time with markdown-formatted output.

---

## 📄 License

This project is Unlicensed. See the [LICENSE](./LICENSE) file for details.

---

## 🙏 Acknowledgments

- Hacktiv8 AI Productivity & API Integration Course
- Google Gemini API
- Tailwind CSS
- Showdown.js

---

Feel free to fork, contribute, or reach out if you have any questions!
