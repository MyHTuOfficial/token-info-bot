# Telegram Token Bot 
Telegram bot that sends information about your tokens every minute/hour/day.
## Installation
This bot uses python, some built-in and some that needs installation libraries.
```
pip install requests
```
```
pip install telebot
```
```
pip install schedule
```
```
pip install ast
```
## Available commands
```
/start
```
Simple start command. It sends simple message.

![изображение](https://github.com/MyHTuOfficial/token-info-bot/assets/140544788/cc4a54f6-405b-45b0-a9a2-34fa9f899152)

```
/addtoken
```
This command adds tokens that you are interested in. You must use abbreviation of a token, BTC not Bitcoin or ETH not Etherium, and you will have to name token after command.

![изображение](https://github.com/MyHTuOfficial/token-info-bot/assets/140544788/84e30182-a5c0-4811-9a55-902a2daa974d)

```
/settime
```
Sets time period in which you will be receiving notifications. For now available time periods are: minute, hour and a day.
![изображение](https://github.com/MyHTuOfficial/token-info-bot/assets/140544788/1fcca018-20a1-4c73-bcb3-d2c1a185fce1)
## How this works
It uses requests for parsing token info from binance api, ast for easy working with dictionary and file saving, and schedule to send messages every minute/hour/day.
To save file it simply uses a token.txt file, it MUST be in the directory with the bot. Every user has token list and time period, in which bot sends notifications.
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
