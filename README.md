# ChannelBan

This bot watches a channel and bans users if they post in it (with configurable role exclusions).

This bot requires the **Server Members** and **Message Content** intents.

In guilds it requires **View Channels**, **Read Message History**, **Moderate Members**, and **Ban Members**.

To run:

```
cd channelbans/
cp .env.example .env
```

edit `.env` with all the values specified in the comments.

`pipenv` is recommended.

```
pipenv install
pipenv run bot
```
