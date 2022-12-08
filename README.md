## Installation

* npm
```sh
npm install npm@latest -g
```

1. Clone the repo
```sh
git clone https://github.com/damarasf/wa-openai.git
```
2. Install NPM packages
```sh
npm install
```
3. Copy .env file
```sh
cp .env.example .env
```
4. Enter your API keys and your custom prompt in .env file
```JS
OPENAI_API_KEY="<your secret key here>"

DEFAULT_PROMPT="<your custom prompt here>"
```
* API keys from OpenAI at https://openai.com.


## Example Prompts

Prompts should be written in the first person and are used to define your bots personality and ego. ie:

> I am a bot that responds to messages. I am a bit of a joker. I am a bit of a smart

The more detail you offer in your prompt, the better your responses will be.


## Usage

1. Run the bot:
```sh
npm run start
```
2. Open WhatsApp on your phone, select 'WhatsApp Web' from the settings menu, then scan the provided QR code.
3. Choose from the list of recent chats which you would like to activate the bot for. Use space key to select.
4. Sit back and watch the bot respond automatically to incoming messages from your selected contacts.

### Disclaimer
I fix the isues from Whatbot https://github.com/theshanergy/whatbot/issues/7
And i fix the openai bug
