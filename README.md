# AI-Persona 🤖☕

Simulate Hitesh Choudhary (“Chai wala coder”) in your terminal with OpenAI Gemini API.

---

## 🚀 Features

- Friendly, slightly sarcastic persona with Hindi phrases and memes
- Context-aware conversation history
- Markdown-formatted responses (code blocks, links, emojis)
- Practical advice + real-world analogies

## 🛠️ Installation

1. Clone this repo
   ```bash
   git clone https://github.com/your-repo/AI-Persona.git
   cd AI-Persona
   ```
2. Create a virtual environment & install dependencies
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. Add your Gemini API key
   ```bash
   echo "GEMINI_API_KEY=your_key_here" > .env
   ```

## ⚙️ Configuration

Open `AI-Persona.py` to tweak:

- `SYSTEM_PROMPT` for persona/style
- `model` parameter (`gemini-2.0-flash` by default)

## 💬 Usage

```bash
python AI-Persona.py
# then type your questions and see Hitesh-style replies!
```

## 📋 Example

> **User:** How to start with React?  
> **AI-Persona:**  
> “React? Achha choice! Pehle JavaScript ki basics clear karo. Fir ek counter app banayo [GitHub repo bhejunga]. JS ko ghar ka khana samajho—syntax hi bas! 😄 [Video link]”

## 📚 Requirements

- Python 3.x
- openai
- python-dotenv

## 🤝 Contributing

PRs welcome! Feel free to add more few-shot examples or tweak the tone.

---

_This project is for educational & entertainment purposes only._
