# ChatGPT
My implementation of the official ChatGPT API

# Features
I've added a few things to make it more useful in the CLI:
- Typing 'copy' will copy the last output from the bot
- Typing 'paste' will paste your clipboard as a query - this way you can craft prompts in a text editor for multi-line queries
- '@', 'sel', or 'select' will allow you to select lines to delete (handy if the chat is getting a bit long and you want to save on costs)
- '!', 'del', or 'delete' will clear the chat log and start fresh

# Installation
You will need to have the most updated OpenAI python package (pip install --upgrade openai).
You will need Pyperclip for copy/paste functions (pip install pyperclip)
Paste your OpenAI key into line 3 of the script where it says 'yourkeyhere'

