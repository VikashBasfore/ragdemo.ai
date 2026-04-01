# ragdemo.ai
Retrieval Augmented Generation(RAG) is a technique that enhances the capabilities of LLMs by combining information retrieval with text generation. Instead of relying on pre-traned knowledge, RAG fetch relevant data from external sources and use it to generate more accurate responses.

### Packeges
streamlit
python-dotenv
PyPDF2
google-generativeai

lengchain # core dramework
lengchain-huggingface # Connect huggingface models to perform embedding
faiss-cpu # fast vector database to store embedded data
langchain-community # extra integration
langchain-text-aplitters # to split large text into smaller chunks
sentence-transformers # pr-trained embedding wholes to convert text into vectors
langchain-core # documents, chains etc.....

### In simple words
Text -> split text -> convert vectore -> store in database -> dearch similar content -> send to LLM --> Get answer for Questions

'all-MiniLLM-L6-v2' -> simple hugging face model which splits the text and converts the text into vectors