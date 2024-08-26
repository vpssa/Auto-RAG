###AutoRAG Assistant
AutoRAG is a helpful Python assistant designed to assist users in various tasks. It leverages an LLM (Large Language Model) for conversational interactions and incorporates responses from various sources and knowledge bases.

##Setup
Install the required dependencies:

pip install phi

Set up your PostgreSQL database and adjust the db_url in the code to match your configuration.

Obtain an OpenAI API key and set it as an environment variable:

export OPENAI_API_KEY=''

##Run the assistant:

python your_script.py

##Features
#Knowledge Base: AutoRAG maintains a knowledge base of relevant documents and information.
#Search Tools: It can search both its knowledge base and the internet using DuckDuckGo.
#Chat History: AutoRAG can reference chat history to provide context-aware responses.
#Markdown Support: Responses can be formatted using Markdown.
#Debug Mode: Enable debug mode for detailed tool call logs.

##Usage
Ask a question or provide a user query.
AutoRAG will search its knowledge base and external sources.
It will then provide a clear and concise answer based on the available information.
Contributing
Feel free to contribute to AutoRAG by adding more documents to its knowledge base or improving its functionality.
