🤖 Smart Company News Chatbot
“Ask about any company. Get the latest news. Instantly.”

This AI-powered chatbot helps you find real-time news about any company. Just type a company name (like “Tesla” or “Infosys”), and it will search the internet live, then provide a short, clear summary — including links to reliable sources. It can also engage in basic conversation like a real assistant and answer simple questions.

🧠 What Can This Bot Do?
📰 Find live news about any company (e.g., Google, Tesla)

✍️ Summarize news using an AI model

💬 Respond in different styles (Formal, Casual, Bullet points)

🔗 Share links to news articles

😄 Handle greetings, typos, and casual chat

✅ Fully open-source — uses only free tools and models!

💻 Tools Used
Purpose	Tool/Library
Programming Language	:  Python
News Search	: duckduckgo_search
Web Scraping : BeautifulSoup4
Text Summarization	:  facebook/bart-large-cnn via HuggingFace Transformers
Typo Handling	:  fuzzywuzzy
Chat Flow :	Custom Python logic
Memory : Python session variables (Colab memory)


⚙️ How It Works (Step-by-Step)
👤 You enter a company name (e.g., “Netflix”).

🔍 The bot searches for recent news using DuckDuckGo.

📄 It retrieves news titles, snippets, and links.

🧠 Uses an AI model to summarize the news.

🗣️ Displays a neat response — formatted in the style you choose.

▶️ Run It on Google Colab
No setup required — just run!

Open the notebook: 🔗 Click here to open Colab (add your notebook link)

Select Runtime > Run all

Enter the company name when prompted

Enjoy fast, summarized news at your fingertips! 🎉

📁 Files in This Project
text
NEWSGenie.ipynb        ← Main notebook for easy running
Screenshots_chatbot    ←screenshot of the chatbot
requirements.txt       ← Python dependencies (optional)
README.md              ← This README file


❓ FAQ
Q: Do I need to install anything?
A: No, everything runs right in Google Colab.

Q: Does this use ChatGPT or OpenAI APIs?
A: No. It uses free, open-source models from HuggingFace.

Q: Can I use this on my website or app?
A: Yes! It's easy to adapt and deploy with Streamlit or other frameworks.
