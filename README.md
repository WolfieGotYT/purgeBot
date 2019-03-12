# purgeBot
A Discord bot to delete messages.

## List of all commands
**help**                         `~help` view all commands <br />
**purge**                      `~purge [count]` clears a defined number non-pinned messages in given channel. <br />
**purgeChannel**        `~purgeChannel` enables/disables purging for all future messages in given channel. <br />
**eval**                         `~eval [code]` evaluates given d.js code. _Bot Owner Only_. <br />
**exit**                          `~exit` shuts bot down. _Bot Owner Only_ <br />
**reload**                      `~reload [command]` reloads the given command. _Bot Owner Only_. 

## Config.JSON
```json
{
    "token": "",
    "command_prefix": "~",
    "owner_id": "",
    "permission_level": "ADMINISTRATOR",
    "servers": {
        "RL": {
            "serverID": "",
            "channelID": ""
        },
        "WGA": {
            "serverID": "",
            "channelID": ""
        }
    }
}
```
