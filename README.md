Winnsy Bot | Advanced Discord Giveaways
Winnsy Bot is a powerful and advanced giveaway bot for Discord, built on Discord.js v14. It focuses on rich features, high security, full customization, and is entirely powered by Slash Commands.

<a href="https://discord.com/oauth2/authorize?client_id=850836703949750282"> <img src="https://img.shields.io/badge/Add%20to%20Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Add to Discord" /> </a>

🔒 Copyright & License
Please note that Winnsy Bot is a private, closed-source project.

The source code is not available for public use, modification, or distribution. This repository is for informational and documentation purposes only. All rights are reserved.

🚀 Core Features
Winnsy Bot is packed with advanced features that go beyond standard giveaway bots.

📈 Persistent Giveaways: The bot loads all active giveaways from the database on restart, ensuring no giveaways are lost.

🖱️ Flexible Participation: Server managers can choose the entry method:

Buttons (Default): The modern, clean, and default method.

Reactions: The classic emoji reaction method.

This can be set as a server-wide default or customized for each giveaway.

🔒 Security & CAPTCHA:

CAPTCHA Protection: Enable a math-based CAPTCHA on a server-wide level to stop bots from entering.

Bot Protection: A simple toggle to prevent other bots from participating.

Valid Winner Check: The bot automatically verifies that the winner is still a member of the server before announcing them.

💎 Premium System:

DM Winners: Automatically send a congratulations DM to winners.

Auto-Delete: Automatically delete the giveaway message 24 hours after it ends.

Custom Entry Messages: Customize the ephemeral message users see when they enter a giveaway (supports plain text or embeds).

⚙️ Advanced Requirements:

Required Role: Set a specific role that users must have to enter.

Minimum Account Age: Set a default minimum account age (e.g., 30d, 6m) for the server.

Prevent Previous Winners: Block users who have won past giveaways in the server from participating.

🔑 Granular Permissions:

Instead of relying on "Manage Messages," you can define specific Giveaway Manager Roles (/settings giveaway-roles).

Users with "Administrator" permission can always manage giveaways.

📊 Comprehensive Logging:

The bot logs every action (command used, giveaway created, ended, edited, setting changed) to a dedicated log channel.

All logs are also stored in the database.

🎨 Full Customization:

Customize giveaways with a color, image, and thumbnail.

Customize the participation theme (button emoji and label) from the server settings.

📋 Available Commands
Winnsy Bot uses 100% Slash Commands for a modern and integrated Discord experience.

👑 Giveaway Commands (/giveaway)
/giveaway create: Create a new giveaway with options for duration, prize, winner count, and all advanced requirements.

/giveaway end: End an active giveaway early.

/giveaway reroll: Reroll new winners for an ended giveaway.

/giveaway delete: Delete an active or ended giveaway.

/giveaway list: Show a list of all active giveaways in the server.

/giveaway info: Get detailed information about a specific giveaway.

/giveaway edit: Edit the details of an active giveaway (prize, winners, duration, etc.).

/giveaway users: View and manage the participants of a giveaway (includes removing users).

⚙️ Settings Commands (/settings)
/settings view: View all of the bot's current settings for this server.

/settings log-channel: Set the channel where all bot logs will be sent.

/settings min-account-age: Set the default minimum account age required to enter giveaways.

/settings auto-delete 💎: (Premium) Enable or disable auto-deletion of ended giveaways.

/settings dm-winners 💎: (Premium) Enable or disable sending DMs to winners.

/settings bot-protection: Enable or disable the setting that blocks other bots from entering.

/settings captcha: Enable or disable CAPTCHA verification for giveaway entry.

/settings reset: Reset all bot settings to their default values.

/settings giveaway-roles: Manage which roles have permission to create and manage giveaways.

/settings edit-entry-message 💎: (Premium) Customize the ephemeral entry message.

/settings theme: Configure the default giveaway theme (button or reaction) and customize button labels/emojis.

🤝 Support
Need help or have questions about the bot?

Join the official Support Server for assistance! https://discord.gg/4TmMSF7w5z
