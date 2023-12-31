# RJ386773-MTL
MTL of https://www.dlsite.com/maniax/work/=/product_id/RJ386773.html

# How to contribute
TLDR 3 steps.

    Fork the repository.
    Make the changes.
    Submit a pull request to the project owner.

If everything looks good and doesn't break things I'll merge it in.

Longer Version:

Things that are needed:
* An editor of some kind. (I recommend [VSCode](https://code.visualstudio.com/))
* The Game
* [Git (Duh)](https://git-scm.com/downloads)
* Motivation to learn

1. Fork the repo using the fork button at the top.
2. Open the terminal in your game folder by shift + right clicking and clicking Terminal. Then clone the repo using the following:

`git clone [FORKURL]`

3. Grab everything inside that folder that just got created and paste it in the main game directory, replace all. Use `git status` and make sure its clean. Now you are all setup, all you need to do is play the game and look for any changes that need to be made. Stuff like spelling errors, wrong names, inconsistencies, spacing issues, etc.
4. When you do find a change that needs to be made, do the following to make things easy. Right click on the `data` folder and click `open with VScode`. If you dont see that option see [this](https://dev.to/matheusgomes062/how-to-open-your-files-with-vs-code-from-the-context-menu-on-windows-5fi9) or you can just open vscode and drag it in.
5. Use the FIND functionality to search for what you are trying to fix. For example if a character's name is wrong, type that into the search menu and start looking, then make the change. Try not to mess with any scripts or variables you might see. If you can't find it in `data` try `js` folder instead.
6. After you are satisfied with your changes it's time to put in a PR. Use `git add -A` to add changes then Use `git commit -m 'MESSAGE HERE'` to save your changes. then do `git push` to push them to your fork. If everything works your fork should update with the changes.
7. Go to Pull Requests > New Pull Requests. Look at the arrow, your fork should be pointing to the original repo (mine). Add in details on what you fixed and Submit. If everything looks good I'll merge it in and you would have successfully contributed.

Got questions? Just shoot me a message, more than happy to walk you through any of the tools.
