# Streamer.Bot-DeathCounter
Death Counter for Streamer.Bot

To Import Code to streamer.bot, just right click on the Actions List, under the Actions tab and click Import. Download the file(DeathcounterImportFile.txt) then just click and drag the file from a file explorer window right into the import string area. A bunch of what looks like random text will show up and then other information will show up. Then just click Import.

Download the "DeathCounterNumber.txt" file or create a text file named "DeathCounterNumber.txt" and put a 0 in the first line, then link the file in Streamer.bot in the Sub-Actions that are "Write to file" or "Read Lines".

You will have to make commands in streamer.bot to control this. Make a command with the command !deaths and use the action "DeathCounter-Current". Then make a command for !deathreset and use the action "DeathCounter-Reset". Then to add to the death count create command !adddeath and use the action "DeathCounter-Add".

To make sure it is setup properly run the "!deathreset" command to make sure the "DeathCounterNumber.txt" file is setup properly!

If you have any questions, join the discord! https://discord.gg/Vwapq3V
