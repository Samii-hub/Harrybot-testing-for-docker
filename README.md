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
