<div>
  <div style="margin-left:auto;margin-right:auto;">
    <img src="https://cdn.discordapp.com/attachments/502649544622735362/520794535018627083/dm-bot.png"><br><br>
</div>

Hello glad you stumpled upon DM-BOT. You can freely modify, configure, produce this code. I only wish you respect my wishes and give credit where it is due. Thank you! If you have any questions or concerns visit my webpage > [LivelySource.tk](https://livelysource.tk)

## Requirements

- `git` command line ([Windows](https://git-scm.com/download/win)|[Linux](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)|[MacOS](https://git-scm.com/download/mac)) installed
- `node` [Version 8.0.0 or higher](https://nodejs.org)

You'll need your bot's token. This is obtained by creating an application in
the Developer section of discordapp.com. 

## Installing DM-BOT

Run this command within your folder.
You can simply shift + left-click to open the Powershell window.

`git clone https://github.com/livelysource/dm-bot.git`

then... 

- In the folder where you used the git command, run `npm install` to install it's dependencies,
- Rename  `config-example.json` to `config.json`
- Edit `config.json` and fill in all the required inputs.

## Using DM-Bot

To start DM-BOT, in command prompt or powershell(whichever you are using), run the following command:
`npm start`
If you wish to publish this on github, besure to include `config.json` in your `.gitignore` file.

## To Invite Your Bot!

To add the bot to your guild, you have to get an oauth link for it. 

You can use this site to help you generate a full OAuth Link, which includes a calculator for the permissions:
[Permission Calculator](https://finitereality.github.io/permissions-calculator/?v=0)

## Understanding How it Works

DM-Bot is using the [discord.js](discord.js.org) lib.
DM-Bot takes messages from the dm channel, then sends them to a server's specific channel.

To there you can reply to the message by copying the command's syntax provided. There you can fill in the `<message>` 
area!