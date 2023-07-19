# WebGPT Discord Bot

The WebGPT Discord Bot is a script that integrates a chatbot powered by ChatGPT into a Discord server using the Discord.py library. The bot provides users with the ability to interact with the chatbot and receive responses to their questions or prompts. It also incorporates the DuckDuckGo search engine to provide up-to-date web search results.

## Prerequisites

- Python 3.7 or higher
- Discord.py library
- duckduckgo_search library

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies by running the following command:
`pip install -r requirements.txt`

## Usage

1. Obtain a Discord bot token from the Discord Developer Portal.
2. Open the script file `webgpt_discord_bot.py` and replace the `TOKEN` variable with your Discord bot token.
3. Run the script by executing the following command:
`python webgpt_discord_bot.py`
4. Invite the bot to your Discord server using the OAuth2 URL generated in the Discord Developer Portal.

## Commands

The WebGPT Discord Bot responds to the following command:

- `/ask <prompt>`: Ask the chatbot a question.

The chatbot will generate a response based on the provided prompt using ChatGPT and provide up to 5 web search results from DuckDuckGo.



