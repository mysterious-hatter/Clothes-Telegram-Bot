# Clothes Bot

A simple Telegram bot that helps users manage and choose their clothes — e.g. add items to a wardrobe and get suggestions what to wear.  

---

## ⚠️ Attention  

This project is no longer actively supported (since 2023). 

---

## 🚀 Quick Start  

1. Clone the repository:
    ```bash
    git clone https://github.com/mysterious-hatter/Clothes_Bot.git
    ```
2. Install dependencies (see `requirements.txt` if present).  
3. Run the bot (e.g. `python bot.py` or whatever the entry point is).  
4. Add your clothes via `/add_clothes`.  
5. Ask the bot what to wear with `/what_to_wear`.  

---

## 🧰 Features  

- Add clothes items (e.g. hat, boots, coat) with associated type and suitable temperature.  
- Store user wardrobe (in memory or persistent storage, depending on implementation).  
- Request outfit suggestions based on stored clothes and optionally context (weather, temperature, preferences).  
- List your current clothes (`/my_clothes`).  
- Remove clothes (`/delete_clothes`).  

---

## 📄 Commands  

| Command            | Description                                |
|--------------------|--------------------------------------------|
| `/start`            | Welcome / introduction message             |
| `/instruction`      | Show instructions / help                   |
| `/add_clothes`      | Add a new clothes item                     |
| `/delete_clothes`   | Remove an existing clothes item           |
| `/what_to_wear`     | Get a suggestion what to wear              |
| `/my_clothes`       | List all clothes you have added            |
| `/commands`         | List all available commands                |

---

## 📸 User Interface / Examples  

*(Original screenshots replaced by descriptions — you can substitute with translated images or screenshots in your own language.)*

- **Start screen** — bot greeting and welcome message  
- **Instruction screen** — bot explains how to use commands  
- **Add clothes screen** — user enters item name, type (hat/boots/coat/etc.), suitable temperature  
- **What to wear screen** — bot asks for weather / temperature (if implemented), then suggests clothes from your wardrobe  

> ⚠️ Since this bot isn’t actively maintained, some UI flows may not work or may require fixes — treat this as a prototype.  

---

## 📄 About & License  

- Bot was developed in Python (or the language used in the repository).  
- Feel free to fork / modify / use under the existing license (check `LICENSE` file or contact repository owner).  
- This project was created as a personal / learning project — enhancements and bug-fixes are welcome!  

---

## 🧑‍💻 Contribution  

If you want to improve the bot (e.g. add support for weather APIs, persistent storage, multi-language UI, etc.), you’re welcome to fork the repo and submit pull requests.  

---

## 📚 References  

Original repository: [mysterious-hatter/Clothes_Bot](https://github.com/mysterious-hatter/Clothes_Bot)  
