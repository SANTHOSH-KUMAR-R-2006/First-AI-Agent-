# First AI Agent 
![First AI Agent](https://github.com/user-attachments/assets/f64c5544-cc25-4e8b-99fa-36b6f2ead11c)


# 🤖 AI Agent Task Automation – Built with n8n

This project demonstrates how to build an **AI-powered assistant** using **n8n**, that can receive chat instructions, interpret them using Google's Gemini model, and automatically schedule, update, or log tasks into **Google Calendar** and **Google Sheets**.

## 💡 Use Case Overview

This is my first project using the **AI Agent node in n8n**. I built this as a student to explore how **AI + Automation** can be used to **save time**, **organize tasks**, and **manage schedules** — without writing code manually.


### 👇 Here's how it works:

1. **Chat Trigger**  
   A user sends a task/message in the chat.

2. **AI Agent**  
   Receives and interprets the message using:
   - **Google Gemini Chat Model** for understanding natural language.
   - **Simple Memory** to store recent instructions and context.

3. **Automation Actions**  
   Based on the intent of the chat message, the AI agent:
   - **Schedules the task** in **Google Calendar**
   - **Appends the task** to a row in **Google Sheets**
   - **Reads or updates tasks** on demand using Google Sheets or Calendar

4. **Update Flow**  
   If I want to reschedule, update, or cancel a task — I just send a follow-up message, and the AI handles the rest. ⚙️


## 🧠 Components Used

| Component         | Purpose                                     |
|-------------------|---------------------------------------------|
| `AI Agent (n8n)`  | Central controller of logic + memory        |
| `Google Gemini`   | Understands the task/instructions via chat  |
| `Google Sheets`   | Logs all scheduled tasks                    |
| `Google Calendar` | Creates/updates calendar events             |
| `Simple Memory`   | Retains conversation context                |


## 🚀 Features

- Natural language task scheduling via chat
- Task logging and tracking in Google Sheets
- Google Calendar integration with dynamic scheduling
- Easy task modification and updates
- Fully built using **no-code** with **n8n**


## 📚 Learnings & Reflections

Building this gave me a lot of insight into:
- Working with AI APIs like **Gemini**
- Handling dynamic data flow with **memory context**
- Connecting Google services via **OAuth in n8n**
- Thinking from a **user-experience** perspective — how simple instructions can drive powerful actions


## 📌 Future Scope

- Integrate voice-to-text for voice instructions
- Add Telegram/Slack as front-end chat interface
- Use webhooks to trigger from external apps
- Set reminders and recurring events


## 📬 Let's Connect

If you're working on similar automation ideas or learning n8n like me, feel free to connect or fork this repo!  
Feedback is most welcome 😊


## 🏷️ Tags

`n8n` `aiagent` `automation` `gemini` `chatbot` `googlecalendar` `googlesheets` `studentproject` `nocode` `workflowautomation`
