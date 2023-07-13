<p align="center">
  <img width="180" src="./public/openai.png" alt="ChatGPT">
  <h1 align="center">ChatGPT + Google Drive App with LangChain and Python</h1>
  <p align="center">This project demonstrates how to build a Python app powered by GPT and Google Drive. This combination is made possible by LangChain's Google Drive document loader and serves as a foundation for an infinite number of great apps</p>
</p>

## 💡 Why LangChain?

LangChain is a framework for building complex LLM powered apps. It provides functionalities like:

- Importing and transforming data so that it's usable with ChatGPT.
- Allowing your LLM powered app to interact with the outside world.
- Making it easy to swap out your current LLM for a new one without rewriting a lot of code.
- Providing retries with exponential backoffs for free.

## 🚀 Getting Started

### 🔍 Prerequisites

- Python 3.6 or higher
- OpenAI account
- Google Drive API credentials

### 📦 Installation

1. Clone the repo:

   ```sh
   git clone https://github.com/fonckchain/gdrive-chatgpt
   ```

2. Install the required Python packages:

   ```sh
   pip install openai langchain pypdf2 chroma tiktoken google-api-python-client google-auth-httplib2 google-auth-oauthlib
   ```

3. Set your OpenAI API key as an environment variable:

   ```sh
   export OPENAI_API_KEY='your-api-key'
   ```

## 🛠️ Usage

1. Replace `YOUR_FOLDER_ID` in the `folder_id` variable with your Google Drive folder ID.

2. "Run python file"

3. When prompted, enter your query.

## 📬 Contact

If you have any questions, feel free to contact me at AFonck@protonmail.com

## 🙏 Acknowledgements

- [LangChain](https://www.langchain.com/)
- [OpenAI](https://www.openai.com/)
- Original guide made by [Greg Baugues](https://www.haihai.ai/gpt-gdrive/)
