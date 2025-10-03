# TalkSphere – Python Chat App

[![Python](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-2.x-lightgrey)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A lightweight **real-time group chat app** built with **Python, Flask, and Socket.IO**. Anyone who visits the site can instantly chat with others online — no account required. Inspired by the simplicity of Omegle, but designed as a group-based chat room.

🌐 Live Demo: [TalkSphere on Render](https://python-chat-ahfr.onrender.com)

---

## ✨ Features

* 💬 **Instant messaging** in a shared group chat
* 🌐 **No signup needed** — join and chat right away
* ⚡ Powered by **Flask-SocketIO** for real-time updates

---

## 🛠️ Tech Stack

* **Backend**: Python, Flask, Flask-SocketIO
* **Frontend**: HTML, CSS (inline), JavaScript (inline with Socket.IO)
* **Deployment**: Render

---

## 📂 Project Structure

* `app.py` → Flask backend with Socket.IO event handling
* `templates/index.html` → Chat frontend (HTML + CSS + JS combined)

---

## 📦 Installation

Clone the repo:

```bash
git clone https://github.com/miaabarejo/python-chat.git
cd python-chat
```

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 💡 How to Test

To test the chat in action, open **two or more tabs** of the live demo link (or localhost when running locally).
Each tab will be assigned a unique username + avatar, and you can chat between them in real time.

---

## 🌱 Roadmap / Future Edits

* [ ] Add project logo
* [ ] Custom avatars (male / female)
* [ ] Light and dark mode toggle
* [ ] Private chat rooms

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
