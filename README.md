# WYS-Documentation
 This repo exists with the goal of providing adaqute documentation for modders on the functions in [Will You Snail](https://store.steampowered.com/app/1115050/Will_You_Snail/).

## Getting Started
 The file tree of this project is split into global scripts and object scripts. Currently the plan is only to document *functions* (that means anything that starts with `function` or `= function()`, not entire events.)

## Help Wanted!
 Currently this is a barebones repo, but I'm working on it.
 Any help in the documentation process, or cleaning up and providing more useful descriptions would be greatly appreciated.
 If you decide to contribute to this repo, please refer to the GUIDE.md file to outline how a page should be structured for consistency, (you can also use !TEMPLATE.md for a barebones to copy-paste from.) then submit a pull request to either add functions which are undescribed, or better describe an already existing one. Anyone who does this will be added to a list of contributors below and receive my thanks :)

## How to contribute!
 If you decide you wish to contribute to this project, that's great! If you have chose to add to the wiki and need help knowing what to do, use this quick step by step guide. *(if you just want to report a problem with the wiki but don't want/know how to fix it, please submit a bug report so I can address it.)*
 1. Switch your game branch to \[Sandbox] (important, or you can't decompile the code.)
 2. Decompile the game's source code using [UndertaleModTool](https://github.com/krzys-h/UndertaleModTool/suites/5994794812/artifacts/206790477) by opening the data.win.
 3. Go to Scripts > Unpack Assets > ExportAllCode.csx and choose an appropriate location.
 4. Open the folder in [Visual Studio Code](https://code.visualstudio.com/) or any other editor with the ability to search the contents of files. (in vscode, that's Ctrl + Shift + F)
 5. You can now search through every bit of code in the game! I've been going through global functions alphabetically, but you can start anywhere, as long as it starts with `gml_GlobalScript_`. Remember that each file can contain multiple functions!!! (if you miss this, that means I'll ask you to add your missing functions to your pull request before I can accept it!)
 6. Use [git](https://git-scm.com/) or [GitHub Desktop](https://desktop.github.com/) (I use git most of the time but having a GUI is especially useful on a project like this) to fork this repo, and add the functions to the Global Scripts folder using `!TEMPLATE.md` as a base. If you are unfamilar with Markdown, I suggest you look into that first so you can keep the nice formatting.
 7. Once you've documented some functions, or made edits to existing documentation if needed, submit a pull request to have your documentation merged.

 Thanks for reading!

## Contributors
 - thennothinghappened (thennothing#4011)
 - kenan238 (kenan238#6162)
 - Kiffolisk
