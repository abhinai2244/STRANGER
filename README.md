# Overview

The strangerbot-master project is a Telegram bot called StrangerBot. Its purpose is to connect two random users and allow them to chat anonymously with each other. Here are the key details based on the README.md:

Purpose
Random Chat Matching: Matches two random users on Telegram and provides them with a private chat interface.
Key Features
Facilitates anonymous communication between strangers.
Random user matching to initiate conversations.
Requirements
MySQL: Used as the database backend to manage user interactions and possibly store chat data.
Telegram API Key: Required to authenticate the bot with Telegram.
Installation
Written in the Go programming language, and requires Go installed for building the bot.

Usage
Set the following environment variables:
MYSQL_USER
MYSQL_PASSWORD
MYSQL_DATABASE
TELEGRAM_BOT_KEY
Run the bot using the command strangerbot.
License
The project is licensed under the Apache 2.0 license, allowing modification and distribution under its terms.


This is the source of StrangerBot, the bot on Telegram that matches two random
users and allows them to chat with each other.

# License
StrangerBot is licensed under the Apache 2.0 license.

# Installation
Currently there are no binaries available as direct download yet, you should
build it yourself using Go.

If you have go installed, you can install strangerbot like this:



# Usage

Make sure you have MySQL installed, and retrieved an API key from Telegram.

## Example

Make sure you have the following environment variables set:

```
MYSQL_USER
MYSQL_PASSWORD
MYSQL_DATABASE
TELEGRAM_BOT_KEY
```

You can then run start StrangerBot by running  in your terminal.

#owner:Abhinai  telegram id :@clutch008 
dm for the commands
