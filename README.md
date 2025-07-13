
# 📚 Bookie – Your Personal Book Recommendation Chatbot

**Bookie** is an intelligent chatbot that helps users discover new books based on their preferences such as genre, mood, or favorite authors. Built using **IBM Watson Assistant**, Bookie offers natural and engaging conversations to guide readers toward their next great read.

---

## 🚀 Features

- 🔍 **Genre-Based Recommendations**: Get book suggestions by simply stating your preferred genre.
- 🗣️ **Natural Language Interaction**: Communicate with Bookie like a human—no need for specific commands.
- 💡 **Follow-Up Questions**: Bookie asks smart follow-ups to refine its suggestions.
- 📖 **Dynamic Book List**: Recommendations are pulled from a curated list or an external book API.
- 🌐 **Multi-Platform Ready**: Can be deployed on web, mobile apps, or integrated into messaging platforms.

---

## 🛠️ Built With

- **IBM Watson Assistant** – For chatbot dialogue, intent detection, and entity extraction.
- **IBM Cloud** – Hosting and managing assistant configurations and optional backend.
- **External Book API / Static Dataset** – To provide book recommendations (e.g., Google Books, Open Library).
- *(Optional)* **IBM Cloud Functions** – For custom backend logic and API integration.

---

## 🧠 How Bookie Works

1. **User Input**: The user starts a conversation with a prompt like:
   > "Can you suggest a good mystery novel?"

2. **Watson Assistant**:
   - Identifies the intent (e.g., "get_recommendation").
   - Extracts the genre (e.g., "mystery") using entities.
   - Asks clarifying questions (e.g., tone, length) if needed.

3. **Response**: Bookie replies with a recommendation like:
   > "You might enjoy *The Girl with the Dragon Tattoo* by Stieg Larsson. Would you like another option?"

---

## 📁 Project Structure
bookie-chatbot/
│
├── README.md # Project documentation
├── intents.json # Watson Assistant intents (e.g., get_recommendation)
├── entities.json # Watson Assistant entities (e.g., genre list)
├── dialog.json # Dialog flow for Watson Assistant
├── book_dataset.json # Optional: Custom book list (if not using external API)
├── server/ # Optional backend (Node.js/Flask) for API requests
└── ui/ # Optional frontend (web or app integration)



---

## ✅ Getting Started

### Prerequisites
- IBM Cloud Account
- IBM Watson Assistant Service Instance
- (Optional) Book API Key (e.g., Google Books API)

### Setup Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/bookie-chatbot.git
   cd bookie-chatbot
Create IBM Watson Assistant Workspace:

Log in to IBM Cloud

Create a Watson Assistant service

Import intents.json, entities.json, and dialog.json to define your assistant

(Optional) Set Up Backend:

Use IBM Cloud Functions or a simple Node.js/Flask server to connect to external book APIs

Deploy Bookie:

Integrate with your desired frontend or messaging platform

🧪 Example Intents
"Can you suggest a science fiction book?"

"Recommend me something romantic."

"I loved Harry Potter. What’s next?"

🤝 Contributing
Contributions are welcome! Feel free to fork the project, make changes, and submit pull requests.

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙋‍♀️ Contact
For feedback or collaboration:

Your Name – keshavrohilla32@gmail.com
GitHub – @keshavgitRohilla



