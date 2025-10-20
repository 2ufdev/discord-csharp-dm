**DMall** is a Windows Forms application written in C# using **DSharpPlus** for Discord interactions. It allows sending direct messages (DMs) to all members of a Discord server.

> ⚠️ **Warning**: Using this bot to spam or mass-mention users may violate [Discord’s Terms of Service](https://discord.com/terms) and can result in your account or server being banned. Use only for legal and educational purposes.

---

## Features

* Connect to Discord using a **bot token**.
* Retrieve all members from a specific server.
* Automatically send DMs with custom mentions.
* Randomized delays between messages to avoid suspicious behavior.
* Stop sending messages at any time.
* Simple GUI with real-time logging.
* Optional **KeyAuth** integration for license verification.

---

## Prerequisites

* .NET Framework 4.7.2 or higher
* [DSharpPlus](https://github.com/DSharpPlus/DSharpPlus)
* An active Discord bot with a valid token
* Target Discord server ID

---

## Security and Limitations

* Discord bots have strict rate limits to prevent spam.
* Avoid sending mass messages to prevent your bot from being banned.
* KeyAuth is disabled by default but can be enabled to restrict access to the app.

---

## Development Notes

* `Form1.cs` contains all the main logic.
* `startdm_Click`: Starts sending messages.
* `stopdm_Click`: Stops sending messages.
* `Log(string message)`: Displays logs in the GUI.
* Messages are sent with mentions `<@userID>` to notify users.

---

## Contribution

Possible contributions:

* Improve Discord error handling.
* Add GUI options for message content and delay configuration.
* Optimize sending for large servers.

---

## License

Educational use only. Any misuse is the responsibility of the user.
