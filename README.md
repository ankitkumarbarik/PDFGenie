
# PDFGenie 📄🧞‍♂️

PDFGenie is a **Retrieval-Augmented Generation (RAG) chatbot** that can answer questions from your PDF documents using **vector embeddings** and AI chat models. Powered by **Gemini API** for embeddings and **GROQ API** for knowledge retrieval.

---

## Features ✨

- Upload PDFs and generate **vector embeddings** for fast semantic search.
- Ask questions and get answers from PDF content using **AI-powered chat**.
- Seamlessly integrates **Pinecone vector database** for efficient search.
- Easy configuration using **environment variables**.

---

## Tech Stack 🛠️

- **Node.js / Express.js** – Backend server
- **Gemini API** – Generate vector embeddings
- **GROQ API** – Fetch content for chat
- **Pinecone** – Vector database for fast search
- **dotenv** – Manage environment variables

---

## Setup & Installation ⚡

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankitkumarbarik/PDFGenie.git
   cd PDFGenie
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Create `.env` file** with the following variables:
   ```env
   PORT=5000
   GROQ_API_KEY=your_groq_api_key
   DEBUG=false
   GEMINI_API_KEY=your_gemini_api_key
   PINECONE_API_KEY=your_pinecone_api_key
   PINECONE_ENVIRONMENT=your_pinecone_env
   PINECONE_INDEX_NAME=your_index_name
   ```

4. **Run the server:**
   ```bash
   npm start
   ```

5. **Access your chatbot:**
   Open your browser and go to: `http://localhost:5000`

---

## Usage 💡

1. Upload your PDF(s) through the provided interface or API.
2. PDFGenie will create **embeddings** and store them in **Pinecone**.
3. Ask your questions — PDFGenie will fetch relevant content and generate AI responses.

---

## Contributing 🤝

Contributions are welcome! Feel free to submit **issues** or **pull requests**.

