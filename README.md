🎋 Intro:

This project is an educative chatbot designed for our university's website. The chatbot provides information on various topics related to the university by answering questions in natural language. It utilizes two models: a Fine-tuned Language Model and a Retrieval-Augmented Generation (RAG) Model.

📦 Tech Stack:

Backend: FastAPI, Pydantic, Uvicorn
Frontend: Angular, HTML, CSS, TypeScript
NLP Models: Hugging Face Transformers, Ollama
Data Storage: Chroma for vector storage
Embeddings: FastEmbedEmbeddings
Document Processing: PDFPlumberLoader
CORS Middleware: For handling cross-origin requests
👩🏽‍🍳 Features:

Natural Language Processing (NLP): Provides accurate and context-aware responses.
User Authentication: Secure login and user management.
Session Management: Saves and loads chat sessions for users.
Multi-Model Support: Users can choose between a Fine-tuned Model and a RAG Model.
Responsive Design: User-friendly interface that works on all devices.
💭 Process:

Data Collection: Scraped data from the university's website using web scraping tools.
Data Preprocessing: Cleaned and preprocessed the scraped data, including text normalization, removing HTML tags, and tokenization.
Document Conversion: Converted the preprocessed data into PDF documents for use with the RAG model.
Model Training: Fine-tuned a pretrained model (Llama-2-7b) on our university-specific dataset.
API Development: Developed the backend using FastAPI to handle requests and provide responses from the models.
Frontend Development: Built the frontend using Angular to interact with users and display responses.
The experience was challenging yet rewarding. One major hurdle was efficiently managing the computational resources for model training and inference. Through iterative development and testing, we achieved a stable and responsive chatbot.

📚 Learnings:

NLP Techniques: Gained in-depth knowledge of fine-tuning language models and implementing RAG models.
API Development: Learned how to build and optimize APIs using FastAPI.
Frontend Integration: Improved skills in integrating complex backend services with a responsive frontend.
Data Processing: Enhanced understanding of data scraping, cleaning, and preprocessing techniques.
✨ Improvement:

Optimization: Further optimize the models to reduce inference time.
Scalability: Implement more scalable solutions for handling a larger volume of data and users.
UI/UX Enhancements: Continuously improve the user interface for better accessibility and user experience.
🚦 Running the Project:

Prerequisites:
Python 3.8+
Node.js and npm
Angular CLI
Virtual environment tools (venv, conda, etc.)
Backend Setup:
Clone the repository:

git clone https://github.com/yourusername/university-chatbot.git
cd university-chatbot/backend
Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

pip install -r requirements.txt
Run the FastAPI server:

uvicorn main:app --reload
Frontend Setup:
Navigate to the frontend directory:

cd ../frontend
Install the required dependencies:

npm install
Run the Angular development server:

ng serve

📸 Video or Image:
