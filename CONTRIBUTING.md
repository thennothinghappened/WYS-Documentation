## How to contribute!
 If you decide you wish to contribute to this project, that's great! If you have chose to add to the wiki and need help knowing what to do, use this quick step by step guide. **(if you just want to report a problem with the wiki but don't want/know how to fix it, please submit a bug report so I can address it.)**
 1. Switch your game branch to \[Sandbox] (important, or you can't decompile the code.)
 2. Decompile the game's source code using [UndertaleModTool](https://github.com/krzys-h/UndertaleModTool/suites/5994794812/artifacts/206790477) by opening the data.win.
 3. Go to Scripts > Unpack Assets > ExportAllCode.csx and choose an appropriate location.
 4. Open the folder in [Visual Studio Code](https://code.visualstudio.com/) or any other editor with the ability to search the contents of files. (in vscode, that's Ctrl + Shift + F)
 5. You can now search through every bit of code in the game! I've been going through global functions alphabetically, but you can start anywhere, as long as it starts with `gml_GlobalScript_`. Remember that each file can contain multiple functions!!! (if you miss this, that means I'll ask you to add your missing functions to your pull request before I can accept it!)
 6. Use [git](https://git-scm.com/) or [GitHub Desktop](https://desktop.github.com/) (I use git most of the time but having a GUI is especially useful on a project like this) to fork this repo, and add the functions to the Global Scripts folder using [!TEMPLATE.md](Global%20Scripts/!TEMPLATE.md) as a base *(Please check [GUIDE.md](GUIDE.md) first as it shows a real example)*. If you are unfamilar with Markdown, I suggest you look into that first so you can keep the nice formatting.
 7. Once you've documented some functions, or made edits to existing documentation if needed, *check the below information on pull requests*, then submit a pull request to have your documentation merged.

## Pull Requests
 So, you've got your new documentation ready. That's great! Here are the things you need to make sure you've done before submitting a pull request:
 1. Make sure your files end in the `.md` extension, otherwise they will have no formatting.
 2. Have you made sure to document every function in a file, or just the top one? (If the latter, your pull request will not be accepted until you fix this!)
 3. **Don't include any real code copied straight from the game.** For your demonstration, use modified code. Please do not paste the contents of the function in. *Our job is to describe the purpose of a function, not the contents of a function.*
 4. Are you sure your arguments are the correct data types? If not, that's okay, just make sure to put a TODO at the top of the file indicating this. The same applies to descriptions.

## Bug Reports
 If you find a problem with the wiki's information (that is not documented in a TODO) such as incorrect function names, arguments, wrong description for the function's purpose, or anything like that, please submit a bug report with the page in question and exactly what the issue is. This way I can fix it ASAP.


Thanks for reading!