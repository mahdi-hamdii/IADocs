# Documentation Assistant:

This is a web application is using a Pinecone as a vectorsotre and answers questions about LangChain (sources from LangChain official documentation).

# Environment Variables:
To run this project, you will need to add the following environment variables to your `.env` file

`PINECONE_API_KEY` and `OPENAI_API_KEY`

# Run Locally:
Create Virtual Environment:
```
python -m venv venv
```

Download Langchain Documentation or any desired documentation:

```shell
mkdir langchain-docs
wget -r -A.html -P langchain-docs  https://api.python.langchain.com/en/latest
```

Install Dependencies: 

```shell
  pipenv install
```

Start the flask server

```shell
streamlit run main.py
```