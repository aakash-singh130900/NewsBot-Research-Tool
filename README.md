# NewsBot-Research-Tool
NewsBot is user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the articles.
![Research Tool Interface](https://github.com/user-attachments/assets/a0695a68-7383-436c-8f80-e91ca8c4c2fe)

## 🚀 Features

- **Load URLs or Upload Text Files**  
  Fetch article content by either pasting URLs or uploading a file containing multiple URLs.  

- **Automated Content Processing**  
  Extracts and processes article content using **LangChain's UnstructuredURLLoader** for structured data retrieval.  

- **Efficient Information Retrieval**  
  - Constructs an **embedding vector** using **OpenAI's embeddings**.  
  - Utilizes **FAISS (Facebook AI Similarity Search)** for fast and accurate similarity-based retrieval.  

- **AI-Powered Q&A**  
  - Interact with **LLMs (ChatGPT/Gemini-Pro)** by inputting queries.  
  - Receives AI-generated responses along with **source URLs** for transparency.
 

## 📂 Project Structure  

📂 NewsBot-Research-Tool
├── 📜 main.py → The main Streamlit application script.
├── 📜 requirements.txt → List of required Python packages for the project.
├── 📜 faiss_store_openai.pkl → Pickle file to store the FAISS index.
├── 📜 .env → Configuration file for storing your Model's API key (not included in the repository).
