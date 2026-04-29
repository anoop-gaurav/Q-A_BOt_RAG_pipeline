This project is a Retrieval-Augmented Generation (RAG) chatbot built using a fully local pipeline. It answers history-related questions using custom documents without relying on paid APIs.

🧠 Tech Stack
Embeddings: SentenceTransformers
Vector DB: ChromaDB
LLM: FLAN-T5 (Hugging Face Transformers)
Language: Python
⚙️ Features
Semantic search over custom documents
Context-aware answer generation
No API dependency (100% free and offline)
Supports PDF, TXT, DOCX files
📂 Dataset

Includes 5 curated history documents:

French Revolution
World War II
Indian Independence Movement
Industrial Revolution
Cold War
▶️ How to Run
pip install -r requirements.txt
jupyter notebook

Run the notebook: rag_bot.ipynb

💬 Example Questions
What caused the French Revolution?
How did World War II lead to the Cold War?
What strategies did Gandhi use?
🎯 Future Improvements
Add answer confidence scoring
Improve retrieval ranking
Deploy as a web app
