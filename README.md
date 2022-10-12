# Telegram bot

Gemaakt door Adam el Ghareib - 500849066
11 oktober 2022

# Introductie

In deze tutorial ga je leren hoe je de kleur van je LED strip aanroept via een bot van Telegram.

# Benodigde hardware componenten

- 1x Arduino Board (ESP8266 Development Board)
- 1x LED strip
- Telegram app

# Stap 1: Creating a Telegram bot

1. Install the Telegram app in the app store or the play store
2. Open Telegram, search for “botfather” and click the BotFather as shown below. Or open this link t.me/botfather in your smartphone.
<img src="/images/InstallLibrary.png" width="375px">
3. The following window should open and you’ll be prompted to click the start button.
<img src="/images/InstallLibrary.png" width="375px">
4. Type /newbot and follow the instructions to create your bot. Give it a name and username.
<img src="/images/InstallLibrary.png" width="375px">
5. If your bot is successfully created, you’ll receive a message with a link to access the bot and the bot token. Save the bot token because you’ll need it so that the ESP32/ESP8266 can interact with the bot.
<img src="/images/InstallLibrary.png" width="375px">

# Stap 2: Get your Telegram ID

1. In your Telegram account, search for “IDBot” or open this link t.me/myidbot in your smartphone. 
<img src="/images/ActivateKey.png"> 
2. Start a conversation with that bot and type /getid. You will get a reply back with your user ID. Save that user ID, because you’ll need it later in this tutorial.
<img src="/images/ActivateKey.png">

# Stap 3: Preparing Arduino

# Errors:

Problem:
<img src="/images/Error1.png">
<img src="/images/Error2.jpeg">

Solution:
<img src="/kjhuimages/Error3.png">

# Resources:

https://randomnerdtutorials.com/telegram-control-esp32-esp8266-nodemcu-outputs/
https://www.electroniclinic.com/esp8266-with-telegram-messenger-for-monitoring-temperature-and-humidity-using-dht11/
