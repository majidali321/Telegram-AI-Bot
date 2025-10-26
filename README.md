# 🥿 Telegram Shoe Store Assistant — n8n + Google Gemini

This project is an **AI-powered Telegram chatbot** built with **n8n** that simulates a smart customer support assistant for a fictional shoe store — **EmberStride Shoes**.  
It uses **Google Gemini (PaLM API)** as the language model, integrated with **n8n’s LangChain AI Agent**, to understand customer queries and provide helpful, conversational responses.

---

## 🚀 Features

- 🧠 **AI Agent (Google Gemini)** — answers questions about store details, products, timings, and policies.  
- 💬 **Telegram Bot Integration** — users can chat directly via Telegram.  
- ⚙️ **n8n Workflow Automation** — handles message flow between Telegram, the AI model, and the reply.  
- 🛍️ **Fictional Store Context** — all responses are based on “EmberStride Shoes,” a made-up brand designed for testing conversational AI.  
- 🔄 **Fully Automated Conversation Loop** — no manual triggers needed once active.  

---

## 🧩 Workflow Overview

**1. Telegram Trigger Node**  
Listens for incoming messages from users in Telegram.

**2. AI Agent (LangChain)**  
Processes the user’s message, uses the provided “store information” as context, and formulates a natural-language response.

**3. Google Gemini Chat Model**  
Powers the agent’s intelligence — generating human-like answers.

**4. Telegram Send Message Node**  
Replies automatically to the user’s chat with the generated text.

---

## 🏗️ Technologies Used

- [n8n](https://n8n.io/) – Open-source automation tool  
- [Google Gemini (PaLM API)](https://ai.google/discover/gemini/) – Large language model for AI responses  
- [LangChain Integration for n8n](https://docs.n8n.io/integrations/builtin/ai/langchain/)  
- [Telegram Bot API](https://core.telegram.org/bots/api)

---

## 🧰 Prerequisites

Before importing and running the workflow:
- n8n instance running (Docker, Desktop, or Cloud)  
- Active **Telegram Bot Token** (created via [@BotFather](https://t.me/BotFather))  
- Active **Google Gemini / PaLM API key**  
- The provided workflow JSON imported into n8n  

---

## ⚙️ How It Works

1. The **Telegram Trigger** node waits for a message.  
2. The user’s message is passed to the **AI Agent** node.  
3. The AI Agent uses **Google Gemini** to interpret and generate a relevant response.  
4. The **Telegram Send Message** node sends the answer back to the chat.  

Example:
User: What time do you open on Sundays?
Bot: We’re open from 11:00 AM to 6:00 PM every Sunday at EmberStride Shoes!


---

## 🧠 Demo Context: “EmberStride Shoes”

A fictional store created for testing:
- 📍 Located at *128 Beacon Lane, Orchard Grove District, Halcyon City*  
- 🕓 Open Monday–Saturday (10 AM–9 PM), Sunday (11 AM–6 PM)  
- 👟 Offers sneakers, boots, sandals, and more  
- 🎁 Provides fittings, repairs, and loyalty rewards  

*(All information is fictional and for demo use only.)*

---

## 🧑‍💻 Developer Info

**Author:** Majid Ali  
**Project Type:** AI + Automation Demo  
**Tools:** n8n, Telegram API, LangChain, Google Gemini  

---

## 📜 License

This project is for **educational and experimental purposes** only.  
All data and store information are fictional.

---

## 🌐 Connect

- **GitHub:** [Your GitHub Profile URL]  
- **LinkedIn:** [Your LinkedIn Profile URL]  
- **Telegram Bot Demo:** (optional) *@your_bot_name*
