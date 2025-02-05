LLM App Examples

A starter collection of minimum working examples for building LLM-powered applications with Streamlit. This repository serves as a practical guide for anyone looking to integrate OpenAI, LangChain, and Streamlit into their AI applications.

🚀 Features

✅ Chatbot – Simple conversational AI using OpenAI API✅ File Q&A – Upload documents and ask questions about them✅ Chat with Internet Search – Retrieve live search results for richer responses✅ LangChain Quickstart – A streamlined guide to LangChain’s core features✅ LangChain PromptTemplate – Learn how to structure dynamic prompts✅ Chat with User Feedback – Collect user ratings for AI responses

📌 Use Cases

🔹 AI-Powered Chatbots – Build interactive assistants quickly🔹 Intelligent Q&A Systems – Answer document-based questions dynamically🔹 Automated Research Assistants – Combine AI with real-time search🔹 Custom GPT Workflows – Leverage LangChain to customize AI models

🔧 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/UsernameTron/LLM-Examples.git
cd LLM-Examples

2️⃣ Set Up Virtual Environment (Optional)

python3 -m venv venv  
source venv/bin/activate  # macOS/Linux  
venv\Scripts\activate     # Windows  

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Get an OpenAI API Key

Go to OpenAI API Keys

Click + Create new secret key

Copy the key and add it to Streamlit Secrets:

OPENAI_API_KEY='your-api-key-here'

⚠ Never expose your API key publicly!

5️⃣ Run the App

streamlit run Chatbot.py

📂 Project Structure

📁 LLM-Examples/
 ├── 📄 Chatbot.py            # Streamlit chatbot example
 ├── 📄 README.md             # Documentation (this file)
 ├── 📄 requirements.txt      # Dependencies
 ├── 📁 pages/                # Additional examples
 ├── 📁 .streamlit/           # API secrets (not committed)

🎭 Demo Apps

Want to see it in action? Click here to check out the live Streamlit demo.

💡 Contributing

Have an idea for an improvement? Fork the repo and submit a PR! 🚀

📜 License

MIT License – Free to use, modify, and contribute.

⭐ Support the Project

If you find this useful, give it a ⭐ on GitHub to help others discover it!
