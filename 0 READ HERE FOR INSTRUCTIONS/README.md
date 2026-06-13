# SAVE FILES BACKUPS
Backup save files for every major point in the game, and some more.

The first number in the name of the folders is the order in which they should be played.<br>
`AREA NAME`: First time entering that area<br>
`PRE X`: Before X<br>
`POST X`: After X

# HOW TO RESTORE A BACKUP
1: Select the backup you want to restore<br>
2: Press `CTRL` + `C`, then press `CTRL` + `V`<br>
3: Rename the folder that has just been created to `SaveGames`<br>
4: Press `WINDOWS KEY` + `R`<br>
5: Paste `%localappdata%/Stonemachia/Saved` in the window that just opened, then press `ENTER`<br>
<details><summary style="font-size: 17px; border-radius: 10px; background-color: rgba(0, 0, 0, 0.13); padding: 10px; margin-bottom: 15px">Click here if you want make sure the path you just opened is correct!</summary>

>The path of the folder that just opened should be `C:\Users\YourUser\AppData\Local\Stonemachia\Saved`<br>
>And the folder structure should look like this:<br>
>Save/<br>
>↳`Config`/...<br>
>↳`Crashes`/...<br>
>↳`Logs`/...<br>
>↳`SaveGames`/<br>
>&nbsp;&nbsp;↳`GlobalState.sav`<br>
>&nbsp;&nbsp;↳`PlayerState.sav`<br>
>&nbsp;&nbsp;↳`steam_autocloud.vdf`<br>
>&nbsp;&nbsp;↳`UserPreferences.sav`<br>
>↳`Stonemachia_PCD3D_SM6.upipelinecache` (optional)</details>
6: Drag the folder you just renamed to `SaveGames` into the folder that just opened with step 5<br>
7: Replace all the files it asks you to replace

# CREATING YOUR OWN BACKUPS
## Creating a backup
1: Press `WINDOWS KEY` + `R` <br>
2: Type `%localappdata%` and press enter <br>
3: Open the `Stonemachia` folder, then `Saved` <br>
4: Create a new folder here and name it something like `BACKUPS` <br>
5: Select the `SaveGames` folder (click it once) and then press `CTRL` + `C` <br>
6: Open the `BACKUPS` folder you just created, and press `CTRL` + `V` <br>
7: Optionally rename the folder you just pasted into something unique like `Before installing CustomFishingEncounter` <br>

## Restoring a backup
1: Open your `BACKUPS` folder <br>
2: Select the backup folder you want to restore <br>
3: If you renamed the folder to something unique, you must rename it back to `SaveGames`, then select it again <br>
4: Press `CTRL` + `C` <br>
5: Go back to the `Saved` folder (folder above BACKUPS) <br>
6: Press `CTRL` + `V` and replace everything if it asks you to <br>
