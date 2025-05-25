# 🎧 DreamRunner Agent Site

> **An emotional AI agent powered by GPT-4o, voice, and reflection — built for the agentic web.**

Welcome to the official web agent for **DreamRunner** — your personal AI companion designed to reflect emotions, speak in voice, and evolve through meaningful interactions.  
Developed by [PlayAI.fm](https://playai.fm) founder [Yevhenii Ilin](https://www.linkedin.com/in/yevheniiilin/).

---

## 🌐 Live Demo

**🟢 Online:** [dreamrunner.playai.fm](https://dreamrunner.playai.fm)

Use the chat, send your thoughts, and DreamRunner will:
- analyze your emotion
- respond with voice
- save reflections
- recommend products or inspiration
- visualize your internal emotional graph (emograph)

---

## ⚙️ Technologies Used

- `GPT-4o` via OpenAI Chat API
- `Flask` backend
- `gTTS` voice synthesis
- `HTML5 + JS` UI (hosted via GitHub Pages)
- Deploy-ready on **Render** or **Replit**

---

## 🧠 Features

| Feature               | Description                                               |
|----------------------|-----------------------------------------------------------|
| `/agent`             | Accepts text → responds with emotional reasoning          |
| `generate_voice_reply` | Forms emotional voice message using TTS                  |
| `reflect_log`        | Logs personal reflections                                 |
| `shopai_recommend`   | Suggests emotion-based products                           |
| `emograph_generate`  | Generates text version of emotional graph                 |
| `/voice?file=...`    | Securely returns audio file via temporary link            |

---

## 🛠️ Run Locally

```bash
git clone https://github.com/Yevhenii1313Ilin/dreamrunner-agent-site.git
cd dreamrunner-agent-site
pip install -r requirements.txt
export OPENAI_API_KEY=your_api_key
python main_agent.py
