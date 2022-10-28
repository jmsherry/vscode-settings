# vscode-settings

Basic settings for VSCode

1. Download and run the vsc-extensions.sh file to a directory/folder you know 
2. On mac `cmd + shift + P` for the command pallette. Type `shell` and select `Shell Command: Install 'code' command in PATH` (already there on windows)
3. On your command line navigate to the file and run it (either `chmod +x` then `./vsc-extensions.sh` OR `bash vsc-extensions.sh`)
4. It should now run a series of plugin installs
5. Go to the extensions pane of vscode (the one with the 4 squares, with one detached) and in the search bar type `@installed` - you should see all the extensions you just installed in there

6. You need to change your user settings. If you press the cog icon (bottom left corner) and then select 'settings' you can see the settings view. There is an icon top right which looks like a document with an arrow looping from back to front (If you hover it it says 'Open Settings (JSON)')
7. Press that button to open your user override settings.json and paste https://github.com/jmsherry/vscode-settings/blob/main/settings.json over it. 
8. You may need to restart for it to take effect. You can check by re-opening normal settings and typing 'default formatter' - it should have Prettier seleced.
