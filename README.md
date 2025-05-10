# Chatbot Web App

A sleek, modern chatbot web application featuring file uploads, emoji support, and seamless integration with the Gemini API.

## ✨ Features

- **Responsive Popup UI:** Clean, mobile-friendly chat interface that pops up on demand.
- **Real-Time Messaging:** Instantly send and receive messages.
- **Image Upload & Preview:** Attach and preview image files directly in the chat.
- **Emoji Picker:** Express yourself with a built-in emoji selector.
- **Animated Typing Indicator:** See when the bot is responding.
- **Dark Theme:** Stylish, eye-friendly design.

## 🚀 Getting Started

1. **Clone or download** this repository.
2. **Open** `index.html` in your browser.
3. **Click** the chat icon to launch the chatbot popup.
4. **Type** your message, add emojis, or upload an image.
5. **Press Enter** or click the send button to chat.

## 🗂️ Project Structure

- [`index.html`](index.html): Main HTML file containing the chatbot UI.
- [`style.css`](style.css): Custom styles and layout for the app.
- [`script.js`](script.js): Chatbot logic, Gemini API integration, and UI interactivity.

## 🛠️ Dependencies

- [Google Gemini API](https://ai.google.dev/) — AI-powered chat responses.
- [Emoji Mart](https://github.com/missive/emoji-mart) (CDN) — Emoji picker component.

## 🔑 Configuration

- **Gemini API Key Required:**  
  To enable AI features, insert your Gemini API key in [`script.js`](script.js):
  ```js
  // script.js
  const GEMINI_API_KEY = 'YOUR_API_KEY_HERE';
  ```
- **Customize the Theme:**  
  Edit [`style.css`](style.css) to personalize colors, fonts, and layout.

