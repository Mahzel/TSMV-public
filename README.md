# TSMV public
TSMV and relevant plugins release channel.

For the Run8Plugin to load, you might have to unblock the dll files in the \plugins\Run8 Plugin folder.
Right clic them, select properties, and at the bottom of the window select "unblock".
This is a windows security feature that prevent live-loading of unsigned dlls downloaded from the internet.
Until I can found a signature framework to sign the binaries, this might be a required step for every update of the dlls.

NamedTrack and HUMP panels are work in progress features. There will be bugs in them.

# Run8Plugin
This plugin is developped to run with Run8 V3.
## Configuration
- Set Run8 root folder (where the exe resides)
- Select region (Parse will fail if you do not own the region). Optionally in the bottom window, select the sub-region you want to display/hide.
- Select a save file. HIGHLY RECOMMENDED : use the auto-save function at 2 minutes interval and select the auto-save world file for a 2 minutes refresh of the data.
- Select the mode :
  - Offline : Only use world save data or database data.
  - Live : Use the dispatcher API (REQUIRES DS authorisation) and fuse with world save file if available.
 
## Interaction
- You can right clic the map for a contextual menu. Some pins allow for further interaction / details
- Industry / Traffic and right clicking a routing point allows you to configure those files from the app.
  - Industry and Traffic will save as a different file from the default file as to not overwrite it.
  - Otto routing points will overwrite your xml in place.
  - BACKUP YOUR FILES BEFORE MAKING ANY MODIFICATION
- Industry can be exported to an OrderBuilder importable file. Refer to the OB documentation to import. BACKUP YOUR OB FILES BEFORE IMPORTING.

## Bugs and suggestion
- Use the GitHub issue tracker to report bugs and suggestion. Avoid using Discord.
- Run8Studios is not affiliated with this project. No need to contact them for any bugs/issues that might arise while using this program and plugin.

I hope you enjoy using it and that you find it usefull.
If you wan't to support me or development you can subimit bugs and suggestions or [Buy Me A Coffee](https://buymeacoffee.com/mahzel)
