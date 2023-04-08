# chatgpt-integration-with-discord

Create a Discord Bot using OpenAI API that interacts on the Discord Server.

# Prerequisite

- Node.js v18+
- npm v8+
- Discord AC
- OpenAI AC

# Step-by-step Tutorial

- Package installation

```bash
cd YOUR_PROJECT_FOLDER_PATH
npm install discord.js openai dotenv
```

- New channel on Discord

![](res/img/discord_new_channel.gif)

- Add Discord App

https://discord.com/developers/applications/

![](res/img/discord_add_app.gif)

- Add Discord App Bot token

![](res/img/discord_bot_token.gif)

Create .env file in your project folder. Then, add the following code in your .env file in your project folder, and replace the YOUR_DISCORD_BOT_TOKEN.

```bash
DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
OPENAI_ORG=YOUR_TOKEN
OPENAI_KEY=YOUR_TOKEN
```

![](res/img/discord_bot_setting.gif)

- Discord App OAuth2 setting

Modify and paste it "https://discord.com/oauth2/authorize?scope=bot&permissions=8&client_id=YOUR_CLIENT_ID"

![](res/img/discord_app_oauth2.gif)

- Add Discord App Bot to your channel

![](res/img/discord_add_bot.gif)

- OpenAI API keys

https://platform.openai.com/account/api-keys

![](res/img/openai_api_keys.png)

Replace the OPENAI_KEY in your .env file in your project folder.

- OpenAI Organisation key

https://platform.openai.com/account/org-settings

![](res/img/openai_org_key.png)

Replace the OPENAI_ORG in your .env file in your project folder.

- Run Node.js

```bash
cd YOUR_PROJECT_FOLDER_PATH
node index.js
```
