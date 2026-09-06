# Harrybot-testing-for-docker
figuring out how to use unraid docker

---

HarryBot is a small personal Discord bot written in Python.

It watches for messages sent by a specified Discord user and responds in the same channel with one message from a predefined list.

HarryBot was originally made for Harry as a prank and has retained the name ever since.

## What It Does

When the configured Discord user sends a message, HarryBot:

1. Detects the message.
2. Checks who sent it.
3. Sends the next message from its predefined response list.
4. Loops back to the beginning of the list after reaching the end.

The bot ignores messages sent by other users and ignores its own messages.

## Requirements

- Python 3
- `discord.py`
- A Discord bot application and token

Install the required Python package with:

```bash
python -m pip install discord.py
```

## Configuration

Before running HarryBot, configure:

* The Discord bot token
* The Discord username/user the bot should respond to
* The predefined response messages

### Bot Token

Keep your Discord bot token private.

Do not upload your token to GitHub or include it in a public copy of the source code.

## Running HarryBot

Run the bot with:

```bash
python harrybot.py
```

When successfully connected, the console will display:

```text
HarryBot has logged in.
```

## Discord Setup

HarryBot requires a Discord application created through the Discord Developer Portal.

The bot must be invited to the Discord server where it will be used and given permission to:

* View channels
* Read messages
* Send messages

The required Discord intents must also be enabled for the bot.

## Privacy

HarryBot does not intentionally store Discord messages or personal user data.

It reads incoming Discord messages only as necessary to determine whether the configured user sent them and to provide its response.

See [Privacy Policy.md](Privacy Policy.md) for the full Privacy Policy.

## Terms of Service

See [Terms of Service.md](Terms of Service.md) for HarryBot's Terms of Service.

## Disclaimer

HarryBot is a small privately operated project and is not affiliated with or endorsed by Discord Inc.

## License

This project is intended primarily for personal use.
