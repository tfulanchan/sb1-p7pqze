# RAG Application

This project is a RAG (Retrieval-Augmented Generation) application that answers questions based on context from a folder of documents. It uses React for the frontend and Python with FastAPI and Ollama for the backend.

## Prerequisites

- Node.js and npm
- Python 3.9 or higher
- Ollama (for running the language model locally)

## Setup

1. Clone the repository
2. Install frontend dependencies:
   ```
   npm install
   ```
3. Install backend dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Create a `documents` folder in the `backend` directory and add your markdown files there.

## Running the Application Locally

You can start both the frontend and backend concurrently using:

```
npm run start:all
```

Or, you can start them separately:

1. Start the backend:
   ```
   npm run start:backend
   ```
2. In a new terminal, start the frontend:
   ```
   npm run dev
   ```

The frontend will be available at http://localhost:5173, and the backend API will be at http://localhost:8000.

## Building for Production

To build the frontend for production:

```
npm run build
```

This will create a `dist` folder with the built assets.

## Deployment

Refer to the deployment instructions for Netlify (frontend) and Render (backend) in the project documentation.