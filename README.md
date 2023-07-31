# Discord Bot Job Crawler

## Introduction

Discord Bot Job Crawler is a Python-based bot that allows users to interact with it on Discord and retrieve job information from Json files that were crawled through Scrapy. This README provides technical instructions for setting up and running the Discord Bot.

## Setup

Before using the Discord Bot, follow these steps to set up your environment:

1. Create an application on the Discord Developer Portal by visiting [here](https://discord.com/developers/applications).

2. Create a `.env` file in the root directory of the project and add the following line:

```env
DISCORD_TOKEN='YOUR_API_KEY'
```

Replace `YOUR_API_KEY` with the API token you obtained from the Discord Developer Portal.

3. Install the required packages by running the following commands in your terminal:

```terminal
pipenv shell
pipenv install

# This will install the following packages
# "discord.py"
# "python-dotenv"
```

## Running the Discord Bot

To run the Discord Bot, execute the `bot.py` script using the following command in your terminal:

```terminal
python3 bot.py
```

The bot will now be up and running, ready to respond to commands on your Discord server.

## Available Commands

Currently, the Discord Bot supports the following commands:

- `!test`: Use this command to check if the bot is responsive.
- `!jobs`: Use this command to fetch and display job data from our JSON files.

## Resources

Our Discord Bot utilizes Discord.py to seamlessly embed job data in messages. For detailed information about Discord.py and its functionalities, refer to their official documentation [here](https://discordpy.readthedocs.io/en/stable/).

If you are interested in building Discord bots in Python and wish to explore more, you can check out this article: [https://builtin.com/software-engineering-perspectives/discord-bot-python](https://builtin.com/software-engineering-perspectives/discord-bot-python).

## Contributions

We highly appreciate contributions and suggestions to enhance the bot's capabilities. If you have any ideas or improvements, please feel free to fork this repository and submit pull requests. Your contributions will help us grow and improve the project, making it even more useful for job hunters on Discord.

Thank you for your interest in our Discord Bot Job Crawler! Happy job hunting!