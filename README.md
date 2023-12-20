# About

Node.js Telegram Bot Template - if you live in Iran or Russia and has troubles connecting to Telegram servers this project might be what you're looking for.

# How To Run

1. After cloning project, run this command `npm i` in terminal to install dependencies.

2. visit Ngrok website at `ngrok.com` and signup, download the app, open it and use your token to log in ( Token is provided in your ngrok account ).

3. run a server by typing `ngrok http [Port Number e.g 5000]` ngrok will create a tunnel for you and gives you the link, something like this :
   `https://6a3a-69-12-94-107.ngrok-free.app`, leave the tunnel open and copy the link in .env file as `SERVER_URL`.

4. copy your Telegram bot token in .env file as `TOKEN`.

5. Don't forget to run VPN on your mechine ( only for Iran and Russia )

6. You can use `npm run Server` command on a second terminal screen to run the bot.

7. you have to see a log like this `{ ok: true, result: true, description: 'Webhook is already set' }` in your terminal.

   you are all set,
   goodluck 👍
