# CODE_REVIEW

## Overview

**Code Review** is a web-based application that utilizes Google Gemini AI to analyze and provide feedback on code snippets. Built with a modern JavaScript stack, it features a React-based frontend and an Express-powered backend.

## Features

- **Syntax Highlighting** using PrismJS
- **Code Editing** with react-simple-code-editor
- **Markdown Rendering** using react-markdown & rehype-highlight
- **AI-Powered Code Review** using @google/generative-ai
- **Seamless Communication** between frontend and backend via Axios
- **Environment Configuration** with dotenv
- **CORS Handling** for secure API access

## Tech Stack

### Frontend

- Vite\@latest
- React
- JavaScript
- PrismJS
- react-simple-code-editor
- Axios
- rehype-highlight
- react-markdown

### Backend

- Express
- dotenv
- @google/generative-ai
- CORS

## Installation & Setup

### Prerequisites

Ensure you have **Node.js** and **npm** installed.

### Clone the Repository

```sh
git clone https://github.com/yourusername/code_review.git
cd code_review
```

### Install Dependencies

#### Frontend

```sh
cd frontend
npm install
```

#### Backend

```sh
cd backend
npm install
```

### Setup Environment Variables

Create a `.env` file in the backend directory and add the necessary API keys:

```
GOOGLE_API_KEY=your_google_ai_key
PORT=3000
```

### Run the Application

#### Start Backend

```sh
cd backend
npm init -y
```

#### Start Frontend

```sh
cd frontend
npm run dev
```

### Usage

1. Enter your code snippet in the editor.
2. Submit for AI-powered code review.
3. Receive suggestions and improvements from Gemini AI.

## Contribution

Feel free to fork the repository and submit pull requests.

## License

This project is licensed under [MIT License](LICENSE).

