# PDF_Q-A-Using-LLM

In this Project I have illustrated an example of how we can build a chatbot to query multiple PDF documents (size upto 200Mb) using Langchain, Facebook A.I. Similarity Search (F.A.I.S.S.), and the Google Gemini API. The goal is to create a chat interface where users can ask questions related to the PDF’s content, and the system will provide relevant answers based on the text in the uploaded PDF’s .


## Required Reliances


Streamlit: This is a Python package made especially to make websites with little to no coding required. It makes it simple to organise your code using layouts and widgets to create interactive user interfaces.

Langchain: This library serves as a link between many artificial intelligence tools. It allows different AI models to collaborate and communicate with one other more easily, allowing them to function as a single cohesive unit inside a process.

FAISS-cpu: This module offers an optimised CPU-usage version of FAISS (Facebook AI Similarity Search). Finding similar sections within a PDF or across many documents can be made easier with the help of FAISS, a potent library for the effective recovery of similar data points.


The langchain_google_genai : This module is a LangChain connector made especially to interface with Bard and other Google generative AI models. It enables you to include these models into your LangChain workflow to carry out operations such as question answering, text summary, and even the creation of creative writing depending on the information contained in your PDFs.

PyPDF2: This library offers Python users the ability to work with PDF documents. It enables you to programmatically open, read, extract text from, and even edit PDF files. This is essential for handling and retrieving the content from your PDF files.

Python-dotenv : This is a little package that helps you manage environment variables in your Python programme safely. Sensitive data, such as API keys—which are necessary to communicate with cloud-based generative AI services—can be stored in environment variables.

