# Welcome to ClickCrystals Script (CCS)

ClickCrystalsScript (or CCS) is a custom scripting language used to create modules, macros, auto farms, hotkey binds, and much more through the mod ClickCrystals.

Welcome to the Markdown` version of ClickCrystals’ scripting documentation.
In this Wiki, we’ll cover these aspects of scripting with ClickCrystals:
- More information
- Downloading and installing ClickCrystals
- Locating the .minecraft folder, and the .clickcrystals folder
- Reloading your scripts or the entire client
- Writing and running your own scripts

This documentation is written for versions of ClickCrystals `1.3.6` or above. Please note that there are versions of Minecraft that may be unsupported for this version of ClickCrystals.

## More Information
CCS is an interpreted script language, meaning that it determines what each execution does before it runs and does not require compilation. This allows ClickCrystals users to easily reload or run their scripts in game.

All ClickCrystal scripts are executed first thing upon game launch. This either includes the creation of new modules or other tasks such as saving the config or printing something into the console. If you want to execute scripts after launch, you can run the command `,ccs run ...`.

**All script files must have a file extension of `.ccs` or `.txt`.** If the file does not have either one of these extensions, they will be skipped.

[[Next -->]](./download.md)