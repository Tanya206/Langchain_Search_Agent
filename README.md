# 🔎 LangChain Search Agent

An interactive chatbot built with **LangChain**, **Groq**, and **Streamlit** that can intelligently search the web, Wikipedia, and arXiv to answer your questions.

🌐 **Live Demo:** [Click here to try the app](https://langchainsearchagent-mvnfuq5cdwz4kvvkmfizz2.streamlit.app/)

---

## 📌 Features

- 🧠 Uses `Llama3-8b-8192` model from **Groq** for fast, intelligent responses.
- 🌍 **Real-time web search** using:
  - 🔎 **SerpAPI** (Google search)
  - 📚 **Wikipedia**
  - 📄 **arXiv** (scientific research papers)
- 💬 Chat interface with memory (conversation history).
- ⚡ Streaming responses via `StreamlitCallbackHandler`.
- 🎛️ Easy-to-use sidebar for setting your **Groq API key**.

---

## 🚀 Try It Yourself

1. Go to the live app:  
   👉 [https://langchainsearchagent-mvnfuq5cdwz4kvvkmfizz2.streamlit.app/](https://langchainsearchagent-mvnfuq5cdwz4kvvkmfizz2.streamlit.app/)

2. Paste your **Groq API key** in the sidebar.

3. Ask any question like:
   - *"What is machine learning?"*
   - *"Summarize the latest paper on diffusion models from arXiv"*
   - *"Who won the Turing Award in 2023?"*

---

## 🛠️ Local Setup

To run this app locally:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/langchain-search-agent.git
cd langchain-search-agent
2. Set Up Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
4. Create a .env file
env
Copy
Edit
SERPAPI_API_KEY=your_serpapi_key
5. Run the App
bash
Copy
Edit
streamlit run app.py
📂 Project Structure
bash
Copy
Edit
├── app.py              # Main Streamlit app
├── .env                # Environment file with API keys
├── requirements.txt    # Required Python packages
└── README.md           # Project documentation
🔐 Environment Variables
Create a .env file and add your keys:

ini
Copy
Edit
SERPAPI_API_KEY=your_serpapi_key
Your Groq API key will be entered in the app sidebar during runtime.

🧠 Built With
LangChain

Groq API

SerpAPI

Wikipedia API

arXiv API

Streamlit

Python dotenv

👩‍💻 Author
Tanya Sharma

📄 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute.

