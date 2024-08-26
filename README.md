**AutoRAG Assistant**

A Powerful Python Assistant

AutoRAG is your one-stop shop for information and assistance. It leverages the power of Large Language Models (LLMs) to provide you with insightful responses and complete tasks efficiently.

Key Features:

*Knowledge Powerhouse:* AutoRAG maintains a comprehensive knowledge base, keeping you informed on various topics.
*Double-Duty Search:* Utilize both its internal knowledge base and the vastness of the internet (powered by DuckDuckGo) for in-depth information retrieval.
*Contextual Chat:* AutoRAG remembers past conversations, ensuring consistent and relevant responses tailored to your specific needs.
*Markdown Mastery:* Craft beautiful and informative responses using Markdown formatting.
*Debug Mode:* Gain valuable insights into tool call logs to optimize performance and troubleshoot any issues (optional).

Getting Started

Installation:

Bash
pip install phi

Database Setup:

Configure your PostgreSQL database and update the db_url variable within the code to match your settings.

OpenAI API Key:

Obtain an OpenAI API key and set it as an environment variable:

Bash
export OPENAI_API_KEY=''

Launch AutoRAG:

Bash
python your_script.py

How to Use AutoRAG

Simply ask a question or provide a user query. AutoRAG will seamlessly combine its internal knowledge with external search results through DuckDuckGo to deliver clear and concise answers.
