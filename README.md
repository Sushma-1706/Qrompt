# Qrompt 🚀  
**ChatGPT Prompt Navigator Chrome Extension**

Qrompt is a lightweight Chrome extension that improves productivity on ChatGPT by adding a smart sidebar for navigating user prompts in long conversations.

---

## 📌 Features

- **Prompt Navigation Sidebar**
  - Automatically lists all user prompts in the current chat
  - Click any prompt to instantly scroll to it

- **Live Prompt Detection**
  - Tracks new prompts in real time
  - No page reload required

- **Search by Date**
  - Filter conversations by a selected date
  - Quickly revisit chats from a specific day
  - Implemented with Chrome policy–safe DOM handling

- **Toggleable & Non-Intrusive UI**
  - Sidebar can be shown or hidden
  - Does not interfere with ChatGPT’s native interface

---

## 🎯 Problem It Solves

ChatGPT conversations often become very long during:
- Studying
- Coding sessions
- Interview preparation
- Brainstorming

Finding a specific earlier prompt requires excessive scrolling.  
**Qrompt eliminates this friction** by turning prompts into a navigable list.

---

## 🛠 Tech Stack

- JavaScript (Vanilla)
- Chrome Extensions API (Manifest V3)
- MutationObserver (DOM change tracking)
- HTML & CSS

No backend. No external APIs.

---

## 📂 Project Structure

```bash
Qrompt/
├── manifest.json
├── content.js
├── styles.css
├── icons/
│ ├── icon16.png
│ ├── icon32.png
│ ├── icon48.png
│ └── icon128.png
└── README.md
```


---

## ⚙️ Installation (Developer Mode)

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/Qrompt.git
   ```
2. Open Chrome and navigate to:
   ```bash
   chrome://extensions
   ```
3. Enable Developer Mode
4. Click Load unpacked
5. Select the Qrompt directory
6. Open https://chatgpt.com and start chatting

---
## 🔐 Privacy & Security
- No data collection
- No external servers
- No analytics or tracking
- Works entirely on the client side
- Uses safe DOM APIs (textContent instead of innerHTML)
  
---
## ⚠️ Limitations
- Works only on ChatGPT Web
- Date filtering depends on ChatGPT’s visible timestamps
- No access to ChatGPT private APIs
  
---
## 🧪 Future Improvements
- Keyword + date search
- Prompt bookmarking
- Usage analytics
- Calendar heatmap
- Export prompts as notes

  ---
  ## 🤝 Contributing
- Contributions are welcome.
- Fork the repository
- Create a feature branch
- Commit changes
- Open a pull request

  ---
  ## 📄 License
    MIT License
  ---
 ## 👩‍💻 Author
    Sushma Damacharla
    Computer Science Student

