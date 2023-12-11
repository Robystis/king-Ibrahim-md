# WhatsApp MD User Bot

A simple WhatsApp User bot.
 <img alt=Support height="250" src="https://https://telegra.ph/file/ec1e693dbc02d6b40b0ef.jpg">
## Setup

1. Deploy on Heroku
   - Click [SCAN](https://qr-hazel-alpha.vercel.app/md) and scan the QR code through the "WhatsApp Linked Devices" option in your WhatsApp app.
   - You will get a session ID in WhatsApp, copy the ID only.
   - If you don't have an account on [Heroku](https://signup.heroku.com/), [create an account now](https://signup.heroku.com/).
   - If you don't have a GitHub account, [sign up](https://github.com/join) now.
   - [FORK](https://github.com/lyfe00011/whatsapp-bot-md/fork) this repository.
   - Now [DEPLOY](https://qr-hazel-alpha.vercel.app/heroku).

2. Deploy on Koyeb
   - Create an account on [Koyeb](https://app.koyeb.com/auth/signup). [Sign up now](https://app.koyeb.com/auth/signup).
   - Get [DATABASE_URL](https://github.com/lyfe00011/whatsapp-bot-md/wiki/DATABASE_URL). You'll need this while deploying.
   - Get [SESSION_ID](https://qr-hazel-alpha.vercel.app/md). Open Linked Devices in WhatsApp and [SCAN](https://qr-hazel-alpha.vercel.app/md) now.
   - Get the Koyeb API key. [Let's Go](https://app.koyeb.com/account/api).
   - [DEPLOY](https://qr-hazel-alpha.vercel.app/koyeb) now.
   - Enter [Environment Variables](https://github.com/lyfe00011/whatsapp-bot-md/wiki/Environment_Variables). [Read More](https://github.com/lyfe00011/whatsapp-bot-md/wiki/Environment_Variables).
   - Enter a name and click "Create Service."

    - Start and stop the bot:
        - To start the bot: `pm2 start . --name botName --attach --time`
        - To stop the bot: `pm2 stop botName`

### Thanks To

- [Yusuf Usta](https://github.com/Quiec) for [WhatsAsena](https://github.com/yusufusta/WhatsAsena)
- [@adiwajshing](https://github.com/adiwajshing) for [Baileys](https://github.com/adiwajshing/Baileys)
