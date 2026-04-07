# 🤖 Lexi

> **Lexi** is a **personal AI assistant** built with Python.  
> It comes with both **GUI** and **Non-GUI** versions and can assist with day-to-day tasks like responding to voice commands, generating QR codes, and providing helpful information.  

---

## 📦 Overview

> 🔹 **Features**  
> - 🎤 Voice Command Recognition (speech interaction)  
> - 💻 GUI with PyQt5 (`LEXI.py`)  
> - 🖥️ CLI (Non-GUI) lightweight version (`LEXIWithoutGUI.py`)  
> - 📱 QR Code Generation & Handling (`QrCodes/`)  
> - 📂 State Management (`state.py`)  
> - ⚡ Extensible design for new modules  
>
> 🔹 **What Lexi Can Do**  
> - 🎙️ Listen & respond to voice commands  
> - 🌐 Answer general knowledge queries  
> - 🔊 Read responses aloud (Text-to-Speech)  
> - 📅 Handle basic reminders & tasks  
> - 🖼️ Create and manage QR codes  
> - 🧩 Run in GUI or Terminal mode  
>
> 🔹 **Project Structure**
> ```
> lexi/
> ├── LEXI.py                # Main entry point
> ├── LEXIUi.py              # GUI logic
> ├── LEXIUi.ui              # Qt Designer file
> ├── LEXIWithoutGUI.py      # Non-GUI version
> ├── state.py                 # State management
> ├── requirements.txt         # Dependencies
> ├── QrCodes/                 # QR code files
> ├── UI/                      # UI resources
> └── README.md                # Documentation
> ```
>
> 🔹 **Installation**
> ```bash
> git clone https://github.com/TharunNarra/lexi.git
> cd lexi
> python -m venv venv
> source venv/bin/activate   # Linux/Mac
> venv\Scripts\activate      # Windows
> pip install -r requirements.txt
> ```
>
> 🔹 **Usage**
> ```bash
> # Run GUI version
> python LEXIUi.py
>
> # Run Non-GUI version
> python LEXIWithoutGUI.py
>
> # Run Main script
> python LEXI.py
> ```
>
> 🔹 **Future Enhancements**
> - 🌦️ Weather & News API  
> - 🔒 User authentication  
> - 📧 Email/SMS automation  
> - 📊 Better GUI with dashboards  
> - 🤝 Multi-language support  
>
> 👤 **Author**: [Tharun Narra](https://github.com/TharunNarra) | [LinkedIn](https://www.linkedin.com/in/tharun-narra-53b773252)

---
