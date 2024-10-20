# GenAI-Driven-Telegram-Assistant


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n GenAIAssitant python=3.10 -y
```

```bash
conda activate GenAIAssitant
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### AIogram docs
https://docs.aiogram.dev/en/latest/

## Telegram Setup:

1. Search for botfather
2. /newbot
    - GenAiAssitant
    - GenAiAssitantBot

    * Now click on url to access the bot
    * Make sure you collect the access token

### Create a `.env` file in the root directory and add your OpenAI API key and Telegram BOT TOKEN as follows:

```ini
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TELEGRAM_BOT_TOKEN=xxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

 Run `python src/chatgpt.py` to start the bot
 Open Telegram and search for your bot username
 Start a conversation with your bot and enjoy!

