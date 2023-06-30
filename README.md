# haptics customized-chatBot
- Introduction
  Welcome to our Customized Chatbot project, a sophisticated, highly customizable, language-processing chatbot powered by the combined capabilities of OpenAI's GPT-4, LangChain, and LlamaIndex. This chatbot aims to provide engaging, interactive, and tailored conversational experiences, making it an ideal solution for customer support, automated assistants, and entertainment purposes.

- Key Features
  GPT-4: At the core of our Chatbot lies a series of GPT models. Its cutting-edge ability to understand and generate human-like text allows it to deliver realistic conversations.

  LangChain: The LangChain technology integrated into the Chatbot provides on-the-fly translation capabilities. This feature enables our Chatbot to communicate in various languages, making it suitable for global use.

  LlamaIndex: Our Chatbot utilizes LlamaIndex, an advanced indexing and information retrieval system, to offer high customization and context-specific interactions. It empowers the Chatbot to extract specific pieces of information from   large datasets and use them to provide highly relevant responses.

- Structure
  A simple explanation of the project
  database folder: contains all pdfs related to haptics, where the local/customized database resides.
  Storage folder: contains stored index and context.
  demo.py: python script to drive the chatBot.

- Installation & Usage
I've included detailed information about the installation process and usage instructions, which you can find below.

```shell
mkdir haptics_chatBot
cd haptics_chatBot
pip install openai langchain llama_index==0.6.12 pypdf PyCryptodome gradio
git clone "this repo"
```

- Contributions
  This project is inspired by [here](https://betterprogramming.pub/building-your-own-devsecops-knowledge-base-with-openai-langchain-and-llamaindex-b28cda15abb7).

- License
This project is licensed under the terms of the MIT license. Please have a look at LICENSE.md for more details.

