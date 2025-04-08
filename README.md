# 🧠 ChatGPT RAG App (Frontend + Backend)

A full-stack Retrieval-Augmented Generation (RAG) chatbot application built with **Next.js** and **FastAPI**. It includes a chat interface and scraping capability to ingest new URLs into a vector store for intelligent contextual responses.

---

## 📦 Technologies Used

### Frontend (Next.js)
- **Framework:** [Next.js](https://nextjs.org/) (v15.1.7)
- **React:** v19.0.0
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Icons:** [react-icons](https://react-icons.github.io/react-icons/)
- **HTTP Requests:** [Axios](https://axios-http.com/)

### Backend (FastAPI)
- **Framework:** [FastAPI](https://fastapi.tiangolo.com/)
- **Server:** [Uvicorn](https://www.uvicorn.org/)
- **Scraping:** `requests`, `beautifulsoup4`
- **Vector Search:** `faiss-cpu`
- **Generative AI:** `google-generativeai` (Gemini API)
- **Embeddings (optional):** `openai`

---

## 🖥️ Frontend Setup

This project was bootstrapped with `create-next-app`.

### 📍 Core Components
- `ChatBox.js` – Main chat interface.
- `ScraperForm.js` – Submit URLs to be scraped and indexed.
- `pages/index.js` – Integrates ChatBox and ScraperForm.

### 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev



