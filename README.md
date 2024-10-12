# Discord Bot Starter (Node.js)

A minimal starter template for building Discord bots using Node.js. This template provides essential features like command and event handling to streamline the bot development process.

## Features
- **Command Handling:** Organize bot commands easily.
- **Event Handling:** Manage Discord events efficiently.
- **Modular Structure:** Easy to extend and customize.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/iammuttaqi/discord-bot-starter-nodejs.git
   cd discord-bot-starter-nodejs
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure your bot token in `config.json`:
   ```json
   {
     "token": "YOUR_DISCORD_BOT_TOKEN",
     "clientId": "YOUR_CLIENT_ID",
     "guildId": "YOUR_GUILD_ID"
   }
   ```

4. Deploy commands:
   ```bash
   node deploy-commands.js
   ```

5. Run the bot:
   ```bash
   node index.js
   ```

## Usage
- Customize commands inside the `commands` folder.
- Modify event listeners in the `events` folder.

## Dependencies
- [discord.js](https://discord.js.org/) – Interact with the Discord API.
- ESLint – Ensure code consistency.

## License
This project is open-source under the MIT License.
