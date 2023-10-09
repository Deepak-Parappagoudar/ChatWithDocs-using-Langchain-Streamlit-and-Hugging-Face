# ChatWithDocs-using-Langchain-Streamlit-and-Hugging-Face 🦜️

## Introduction:

Welcome to the ChatWithDocs project using Langchain, Streamlit, and Hugging Face! This project aims to provide a user-friendly interface for interacting with multiple documents using the Langchain language model from Hugging Face through a Streamlit web application. The purpose of this application is to gnerate the response to your questions based on the documnets you provide.

LLMs have took the world by storm with their remarakable abilities, however, they suffer with several limitations. And hallucination/mis-information is one of them. One way to work around it is by providing it with an external knowledge base (pdfs in this case). This technique is also known as Retrival Augmented Geneartion(RAG).


## Featires:

Multi-Pdf Chat: Engage in conversations with Langchain while referencing multiple pdfs.

Interactive Interface: A user-friendly web interface built with Streamlit for easy interaction.

Hugging Face Integration: Utilize Hugging Face's Transformers library for language model integration. 

Chat History: The model remembers your queries and their response, so that you can refer them at any point and dig further. 


## Installation:

1. Before getting started we need to get the following:  access to llama2 model by filiing the form at Meta's page; Hugging Face API token; Pinecone key and environment.

2.Clone the repository to your local machine:

```bash
git clone https://github.com/Deepak-Parappagoudar/ChatWithDocs-using-Langchain-Streamlit-and-Hugging-Face
```

3. Install all the required dependencies:

```bash
pip install -r requirements.txt
```


## Recommendations:

It is recommended to run this in a GPU accelerated environment. If not, you could always use smaller models. To do this, you have make appropiate changes in get_llm() function in [app.py](app.py).

Alternatively, you could use OpenAI API if you a have dollar to two to spare. 

 
## Usage:

1. Ensure you've installed all the dependencies and add all the keys are added in the .env file.

2. Run the app.py file using the CLI by executing the following command:

```bash
streamlit run app.py
```

3. Launch the application by following local network url, the interface will be displayed.

4. Follow the instructions & interact with the application.






