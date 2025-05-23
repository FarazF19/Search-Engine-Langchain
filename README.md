# LangChain Search Engine Chatbot with Langchain, Groq and Streamlit

Welcome to LangChain - Chat with Search, a smart chatbot built with Streamlit, LangChain Agents, and Groq’s LLaMA 3 API!

This app doesn't just guess — it thinks, searches the internet (DuckDuckGo), queries Wikipedia, and fetches scientific papers from Arxiv — all before responding to your questions.

🚀 Live Demo: You type a question → It picks the right tool → Searches live → Replies thoughtfully.

## 📋 Features

Live Web Search: Uses DuckDuckGo to get real-time results.

Wikipedia Lookup: Quick access to verified Wikipedia summaries.

Arxiv Research Papers: Fetches top research articles with short readable content.

LangChain Agent: Dynamically chooses the best tool depending on your query (ZERO_SHOT_REACT_DESCRIPTION mode).

Streamlit UI: Chat interface with real-time streaming of agent thoughts and actions.

Groq LLaMA 3 Model: Ultra-fast LLM responses using Groq’s lightning-speed API.

## 🛠️ How It Works

User enters a message in the Streamlit chat interface.

LangChain Agent analyzes the message and decides whether to search the web, query Wikipedia, or look up a paper on Arxiv.

Groq LLaMA 3 model generates and streams the response.

StreamlitCallbackHandler shows the agent’s thought process live on the screen.

⚙️ Installation
Clone the repository and install the dependencies:

Edit
git clone https://github.com/FarazF19/langchain-search-chatbot.git
cd langchain-search-chatbot
pip install -r requirements.txt
Or manually install:

pip install streamlit langchain langchain_groq #\_community python-dotenv
🔑 Setup Environment
Create a .env file in the project root:

GROQ_API_KEY=your_groq_api_key_here
Alternatively, you can manually input your API key from the Streamlit sidebar.

(Optional) Set additional environment variables if you extend this project.

## 🧩 Project Structure

├── app.py # Main Streamlit application
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .env # Environment variables (not committed to Git)

## 🚀 How to Run

Inside your project directory, simply run:

streamlit run app.py
Open the URL that Streamlit gives you (usually http://localhost:8501).

✅ Start chatting — ask anything about the world, latest news, research papers, etc.

## ✨ Screenshots

# ![Search Engine](/assets/search.PNG)

Live Streaming of Thought Process:

(Replace with your actual screenshots later)

## 🔥 Future Improvements

Add more tools (e.g., YouTube search, Scholar search)

Memory: Save past conversations

Better error handling for failed search queries

Option to prioritize certain tools

Deploy to cloud (Streamlit Cloud / HuggingFace Spaces)

## 🤝 Contributing

Feel free to submit pull requests, raise issues, or suggest new features!
Let’s build smarter agents together.

📢 License
This project is open-sourced under the MIT License.
