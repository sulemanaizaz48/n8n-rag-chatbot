# n8n RAG Chatbot

Upload a PDF → Ask questions → AI answers using only the document knowledge.

## What It Does

- Frontend form uploads PDF and sends user question via webhook
- n8n extracts text from PDF, chunks it, stores embeddings in Simple Vector Store
- AI Agent retrieves relevant chunks and generates contextual answers
- Response sent back to frontend via Respond to Webhook

## Tech Stack

- n8n (self-hosted)
- Google Gemini (embeddings + chat model)
- Simple Vector Store
- Webhook trigger

## Screenshot

https://drive.google.com/drive/folders/11aqrxeHjZ-9OxICbCG0n5mG2DVyGZEhg?usp=drive_link

## Video Demo

https://drive.google.com/file/d/1uEymoCRDqFiDWVmdXsivizjAO18hFfSI/view?usp=sharing

## How to Run

1. Self-host n8n
2. Get Gemini API key from Google AI Studio
3. Import workflow JSON
4. Set webhook URL in frontend
5. Upload PDF and ask questions
