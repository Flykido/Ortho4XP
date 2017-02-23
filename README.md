Ortho4XP is a scenery generator for the X-Plane flight simulator, written by _**Oscar Pilote**_

It is a really amazing tool and just like many others, I got addicted to it :)

**Please be aware that THIS IS NOT THE OFFICIAL Ortho4XP Repository**

A few resources for the original Ortho4XP :
- The [Ortho4XP Forum](http://forums.x-plane.org/index.php?/forums/forum/322-ortho4xp/) on "the Org"
- A [Discord server](https://discord.gg/78nD2) dedicated to Ortho4XP, with many people from the streaming community
- The original Ortho4XP's [git repository](https://github.com/oscarpilote/Ortho4XP)
- The original Ortho4XP's [dropbox](https://www.dropbox.com/sh/cjjwu92mausoh04/AACt-QzgMRwKDL392K_Ux3cPa?dl=0)

## Unofficial Flykido's Ortho4XP
This repository contains both my own changes to this fantastic tool, and those that other people kindly sent me : everyone is welcome to join the effort !

Indeed, I volunteer to aggregate any change you'd like to see integrated in the next Ortho4XP release : I will eventually submit them, along with my own ones, to Oscar.

Until then, everything is freely available in this repository, here are the branches of interest :
- [master](https://github.com/Flykido/Ortho4XP) : tracks Oscar's official releases : this one should work out of the box, there isn't any modification from the official release, except for the directory structure (the python is left unchanged). Also, I rebuilt the history of [Oscar's past releases](https://github.com/Flykido/Ortho4XP/releases) : you can access them through the Ortho4XP-vX.YY git tags.
- [master-fixes](https://github.com/Flykido/Ortho4XP/tree/master-fixes) : in the event of an annoying bug in the latest Ortho4XP release (Murphy's never far...) and someone has a correction for it, my aim is to put the hotfix here as soon as possible. This branch does not contain any of the new features, only bugfixes.
- [integration](https://github.com/Flykido/Ortho4XP/tree/integration) : this is were the new features are merged. This branch may or may not work for you, this is a poorly tested (for now) development version. Despite that obligatory warning, I firmly intend to keep it as stable as possible at all times.
- **other branches**: do not even look at them, unless you know what you're doing. They're only here for backup purposes. Oh, and *never branch* from them !

You'll find a detailed explanation of the [git workflow](https://github.com/Flykido/Ortho4XP/wiki/Git-Workflow) I follow in the wiki.

Finally, I'd also like to improve the overall code quality along the way :
- first based on pycharm buitin analyzer (pep8 checker, etc.)
- then on external tools analysis : starting with quantifiedcode, but I'm not settled on a particular tool yet
  => see the [first results here](https://www.quantifiedcode.com/app/project/gh:Flykido:Ortho4XP)
