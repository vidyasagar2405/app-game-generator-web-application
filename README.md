# n8n-streamlit-App-Game-Generator-Web-Application

# 🚀 **AI App/Game Generator – Streamlit + n8n + Gemini LLM**

An AI-powered application that automatically generates **Python App/Game code** using simple text prompts.
This project integrates **Streamlit** for the UI, **n8n** for backend workflow automation, and **Google Gemini LLM** for high-quality code generation.

🎯 **Just describe the app/game → click Generate → download the generated Python project.**

---

## 🛠 **Tech Stack**

* **Streamlit** – Frontend web interface
* **n8n** – Workflow automation
* **Google Gemini Chat Model** – LLM for code generation
* **VS Code** – Local development environment
* **Python** – Final app/game output

---

## 📌 **Project Features**

✔ Generate Python games/apps using prompts
✔ Uses n8n AI Agent + Gemini model
✔ Clean Streamlit UI
✔ Webhook-powered backend
✔ Generates complete runnable Python scripts
✔ Supports multiple game styles (Car Race, Fruit Catcher, Angry Birds Simplified, Zombies, etc.)

---

## 🖥 **Workflow Architecture**

The backend workflow (n8n) looks like this:

<img width="1001" height="549" alt="App: Game generator workflow" src="https://github.com/user-attachments/assets/07962065-4717-4ff3-919e-b61841ae18f8" />


---

## 🎨 **Frontend Preview**

Streamlit-based UI:

<img width="1041" height="528" alt="App:Game generator UI" src="https://github.com/user-attachments/assets/2364a151-797f-4184-89eb-fe9abeaaa0f8" />


---

## 🕹 **Output Examples**

Generated apps & games:

<img width="1470" height="956" alt="Demo games snapshot" src="https://github.com/user-attachments/assets/20d8e908-6dd0-41e0-a1a3-ecd8705c6560" />


---

## ▶️ **How It Works**

1. User enters a prompt (example: *“Create a simple car racing game in Python”*).
2. Streamlit sends request to **n8n webhook**
3. n8n AI Agent + Gemini LLM generates Python code
4. Code is returned to UI
5. User downloads the generated `.py` file
6. Run it locally to play the game

---

## 📦 **Installation**

### 1️⃣ Clone the repo

```bash
git clone https://github.com/vidyasagar2405/n8n-streamlit-App-Game-Generator-Web-Application.git
cd n8n-streamlit-App-Game-Generator-Web-Application
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

---

## 🔗 **n8n Workflow**

- Import the workflow file.

It contains:

* Webhook
* AI Agent
* Gemini Chat Model
* Response Node

---

## 🧠 **Prompt Example**

```
2d ninja fighting game
```

---

## Demo Video:

[Youtube]()
