# LFDM Discord Bot

Discord bot made for the LFDM Discord Server

## Installation

Use the package Discord.js and tcp-ping to make this bot fonctionnal

On Linux
```bash
apt install node
npm install discord.js
npm install tcp-ping
```

## Usage

For run this Discord bot, just enter this command

```bash
node main.js
```

You can change prefix, Discord bot token, version and many other settings in the config.json

```javascript
    "prefix": "Your Prefix",
    "token": "Your Token",
    "version": "Your Version",
    "server_ip": "Your Server IP",
    "server_port": "Your Server Port",
    "name_server": "Your Server Name",
    "broadcast_channel": "Your Broadcast Channel ID"
```
## Features

### !info

Make the !info command to get some infos about the server

![info command](https://i.imgur.com/J2jG5jc.png)

### Auto message when server is up/down

The robot will automatically send you a message in the broadcast channel when the server crashes or restarts

![automessage up](https://i.imgur.com/t96943C.png)
![automessage down](https://i.imgur.com/CX8zE0N.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
