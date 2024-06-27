# Docubot
Docubot is an AI-powered chatbot designed to process and answer questions from uploaded PDF and DOCX documents
# Introduction 
Docubot is an AI-powered chatbot designed to process and answer questions from uploaded PDF and DOCX documents. It leverages natural language processing to understand and extract relevant information from documents, making it an efficient tool for document management and information retrieval. The primary goal of Docubot is to save time and improve productivity by eliminating the need to read through entire documents. Instead, users can quickly find specific information or answers located anywhere in the doocument, without manually searching throught the text. 
# Technologies Used
Programming Language: Python
UI: Streamlit
Vector Database: FAISS
Embeddings: OpenAIEmbeddings
Libraries Used: Langchain, PyPDF2, python-docx
Connectivity Tool: ngrok
# Architecture and Workflow
<img width="581" alt="image" src="https://github.com/SaikiranBSK10/Docubot/assets/66936785/434b7222-ead4-42d6-905f-e9014378f2c6">

- File Upload: Users can upload multiple PDF or DOCX files to the application.
- Text Extraction: The application extracts text from the uploaded documents.
- Text Processing: The extracted text is split into manageable chunks.
- Embedding Creation: Text chunks are converted into embeddings using OpenAI's embedding model.
- Similarity Search: The application uses FAISS to perform similarity searches on the text embeddings.
- Question Answering: Users can input questions, and the application will search for relevant document chunks to generate accurate answers using OpenAI's language model.

# Real-Time Industry Use Cases
- Legal Industry: Law firms can use Docubot to quickly search through legal documents, case files, and contracts to find relevant information and precedents.
- Healthcare: Medical professionals can utilize Docubot to extract information from patient records, research papers, and clinical guidelines.
- Education: Educators and students can use Docubot to search through academic papers, textbooks, and lecture notes.
- Finance: Financial analysts can leverage Docubot to gather data from financial reports, market analysis, and investment documents.

# Installation
1. Clone the repository
   ```bash
   git clone <repository-url>
   cd Docubot
  
2. Install the required dependencies
   ```bash
   pip install langchain openai tiktoken python-dotenv PyPDF2 python-docx faiss-cpu streamlit pyngrok
  
3. .env file

     OPENAI_API_KEY=your_openai_api_key

# Usage 
1. Run Application
   ```bash
   streamlit run RAG_Chatbot.py

2. Ngrok will provide a public URL to access the application.

Docubot is designed to be a versatile tool that can be easily integrated into various industry workflows, enhancing document management and information retrieval processes.

# Sample Images 
<img width="446" alt="image" src="https://github.com/SaikiranBSK10/Docubot/assets/66936785/e48a234d-2622-4fe6-ab3d-7fbf9f01b0f3"> <br>

<img width="398" alt="image" src="https://github.com/SaikiranBSK10/Docubot/assets/66936785/c4f33200-d685-44f2-8e58-61a029fceb35"> <br>

<img width="395" alt="image" src="https://github.com/SaikiranBSK10/Docubot/assets/66936785/b8e87994-1d22-4f19-b36a-010f5cdc2789">






