# McMod
McMod is a free tool, that allows you to manage your Minecraft mods easily.
## Downloading and adding mods:
- To do: Add a mod hub inside McMod
- First, download the .jar file of the mod online.
- Second, open McMod and select your .minecraft folder.
 Third, press continue, enter custom name for your mod in "Mod name" field and press "Add Mod".
## Removing mods:
### You can only remove mods, that were installed with McMod
- To do: Nothing.
- First, open McMod and press Continue.
- Second, enter the custom name of the mod you wanna remove (There is a mod list shown below all the buttons, that shows custom names).
- Third, press Remove mod
## Adding already installed mods to McMod:
### For this, you need to have at least 1 mod installed with McMod and a selected .minecraft folder.
- To do: Add a feature to do this inside McMod.
- First, check if there is "data.json" file inside the folder of McMod. If not, please select .minecraft folder inside McMod and install at least 1 mod using McMod.
- Second, open "data.json" file using Notepad.
- Third, find "mods" value inside the file.
- Fourth, find the latest parameter inside "mods" value.
- Fifth, add a command on the last string, then make a new line.
- Sixth, write:
```
"{CUSTOM MOD NAME}": "{NAME OF THE FILE OF THE MOD}"
```
, but replacing {CUSTOM MOD NAME} with the custom name you want McMod to display and use and replacing {NAME OF THE FILE OF THE MOD} with the name of .jar file that the mod uses.
- Seventh, save the file, close the Notepad and check if the mod is display in the mod list in McMod.
## Changing .minecraft folder outside of McMod:
- First, check if there is "data.json" file inside the folder of McMod. If not, .minecraft folder is not selected.
- Second, open that file with Notepad.
- Third, find ".minecraft" parameter.
- Fourth, replace the value of ".minecraft" parameter with the path to .minecraft folder.
## Changing .minecraft folder outside of McMod when it's not selected:
- First, create a file named "data.json" in the folder of McMod.
- Second, open that file with Notepad.
- Third, paste these contents:
```
{
    ".minecraft": "{.minecraft FOLDER PATH}",
    "mods": {}
}
```
.
- Fourth, replace {.minecraft FOLDER PATH} with the path to .minecraft folder.
- Fifth, save the file, close the Notepad and check if the folder is now selected in McMod.
