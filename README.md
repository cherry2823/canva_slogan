## ✨ Features

- 🔍 Keyword-based slogan generation  
- 🎛 Adjustable number of outputs  
- 🖥 Streamlit-powered user interface  
- 🌐 Optional Hugging Face fallback (free, no API needed)

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) – UI  
- [OpenAI API](https://platform.openai.com/) – text generation (GPT-3.5)  
- [Python](https://www.python.org/) – core logic  
- [python-dotenv](https://pypi.org/project/python-dotenv/) – secure key loading

---

## 🚀 How to Run

### 1. Clone the repo

```bash
git clone https://github.com/cherry2823/canva_slogan.git
cd canva_slogan

2. Create a .env file and add your API key

OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxx

3. Install dependencies
pip install -r requirements.txt

4. Run the app

streamlit run app.py
🧪 Optional: Use local model instead of OpenAI

If you don’t want to use OpenAI due to quota limits, you can switch to a local Hugging Face GPT-2 model.
Instructions are included in the code (app.py).
🖼️ Demo Screenshot

(You can insert a screenshot here later to show the app interface)
📄 License

MIT License
Feel free to fork, remix, or build upon this project for learning purposes.
👩‍💻 Author

Made by cherry2823
Created as part of a learning journey in applying AI to real product-style interfaces.
