# DiscordBOT-MVPList - Version 1.1.0

A Discord bot for managing the list and time of death of Ragnarok Online MVPs. This bot supports full CRUD operations using Sequelize and features a countdown timer.

---

## 🆕 Version Updates

### Version 1.0.0
- Basic MVP list functionality.
- Allows listing and editing the time of death for Ragnarok MVPs.

### Version 1.1.0
- Integrated a database with complete CRUD operations using Sequelize.
- Added a countdown timer feature.

---

## 💬 List of Commands

| Command                                 | Description                                                     |
|-----------------------------------------|-----------------------------------------------------------------|
| `!bhlistall`                            | Shows every MVP's time of death.                                 |
| `!bhlist [MVP Name]`                     | Prints the specified MVP's time of death.                        |
| `!bhadd [MVP Name] [Time of Death]`       | Adds the specified MVP's info to the database.                   |
| `!bhedit [MVP Name] [Time of Death]`      | Updates the specified MVP's time of death in the database.        |
| `!bhdelete [MVP Name]`                    | Deletes the specified MVP's info from the database.               |
| `!bhtimer [# of minutes]`                 | Starts a countdown timer for the specified number of minutes.     |

---

## 🚀 Getting Started

To start the bot in your Discord channel/server:

1. Open Command Prompt.
2. Change the directory to where the `index.js` file is located.  
   Example:  

cd Desktop\mvp_list

3. Once in the desired folder, type the following command and press Enter:  

npm run start

4. Wait for the message "Starting MVP List Discord Bot..." to appear in the console.

---

## ⚠️ Disclaimer

This bot may not function correctly when moved to a different system, as Discord changes the token for security reasons.

Just copy and paste this whole block into your README.md file. Let me know if you need more changes or additions! 😄
