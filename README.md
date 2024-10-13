# **🤖 Telegram Intelligent Agent Chatbot**:

A hybrid architecture-based chatbot for Telegram, designed to provide both quick, rule-based responses and advanced query handling using Natural Language Processing (NLP). This project aims to deliver a seamless user experience through automated replies, scheduled messages, and personalized interactions.

# 🚀 Features
- Hybrid Architecture: Combines reactive and deliberative capabilities for efficient response management.
- Natural Language Processing: Uses NLP to better understand and process complex user queries.
- Automated Responses: Quick replies to frequently asked questions or commands.
- Custom Commands: Easily configurable commands for personalized interactions.
- Scalable Backend: Built with Python and telebot, with MongoDB for data storage.
- Data Persistence: Secure storage of user interactions for improved analysis and refinement.
# 📚 Getting Started
Follow these steps to set up the chatbot locally:

1. Clone the Repository:

```bash
git clone https://github.com/Karlx12/TeleChatBot.git
cd TeleChatBot
```
Set Up a Virtual Environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
Install Dependencies:
```bash
pip install -r requirements.txt
```
Configure Your Bot: Create a .env file with your Telegram bot token:
```makefile
TELEGRAM_TOKEN=your_bot_token_here
MONGO_URI=your_mongodb_connection_string
```
Run the Bot:

```bash
python main.py
```
# 💡 Usage
Once the bot is up and running, users can interact with it through the Telegram app. Try sending commands like:

- /start - To start interacting with the bot.
- /help - To get a list of available commands.
What is the weather today? - Example of a query that can be processed with NLP.
# 🤝 Contributing
We welcome contributions! To contribute:

Fork the repository.
1. Create a new branch:
```bash
git checkout -b feature/your-feature-name
```
Make your changes and commit:
```bash
git commit -m "Add your message here"
```
Push to the branch:
```bash
git push origin feature/your-feature-name
```
Open a pull request.

# 📄 License:
This project is licensed under the MIT License - see the LICENSE file for details.

