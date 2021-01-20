# jonbot

A discord bot that directs play for [Everyone Is John]

## Usage

To create an instance of Jonbot that is completely your own, run this server locally by following the steps below.

## Running locally

1. Run `$ git clone https://github.com/Berkyle/jonbot`
2. Run `$ yarn install` or `$ npm install`
3. [Create a Discord bot]
    * Follow to the end but stop at the last step.
4. Create a `.env` file with the following structure:
   ```shell
   JON_BOT_CLIENT_ID="Your bot's client id"
   JON_BOT_CLIENT_SECRET="Your bot's client secret"
   JON_BOT_BOT_TOKEN="Your bot's bot token"
   ```
5. Run `$ yarn start`
6. Invite the bot to your server using the last step from \[3.\]

## Development

1. Run `$ yarn start-dev` instead

[everyone is john]: https://rulebook.io/games/everyone-is-john/rules
[create a discord bot]: https://discordpy.readthedocs.io/en/latest/discord.html
