---
tags:
  - documentation
---
# Git and Obsidian

Since Obsidian.md uses largely plaintext for editing, it works very well with git version control. This has a lot of advantages over other backup options, including:

1. Version and edit history.
2. The ability to easily revert changes
3. Branches (particularly useful for advanced collaboration with other writers)
4. And much, much more.

Setup and best practice is detailed below.

# Setting up a git repo for your vault

## Cloning the repo

As noted in the [[README]], this repository can be cloned from GitHub, and has been marked as a template repository. Once cloned, you will immediately have your own fresh git repository.

## Obsidian Git plugin

If you lack technical savvy but wish to use git as your backup option, or you don't want to deal with the traditional git workflow, you may want to check out the Obsidian Git plugin. If you do so and lack experience with git, it is **strongly recommended** that you read the documentation available [here](https://publish.obsidian.md/git-doc/Start+here).

[Obsidian Git by Denis Olehov](https://github.com/denolehov/obsidian-git) *MIT License*

## Initializing via terminal

If you have "installed" the vault by downloading the zip file, you can just open this vault at its root level in your terminal of choice, and type  `git init` (assuming you have git installed on your device already). You can then proceed via typical command line workflows, or open the repo in your favorite GUI client for git.


# Before your first commit...

Consider setting up a .gitignore file. You should add the following lines:

```
.obsidian/workspace.json
.obsidian/workspace-mobile.json
.trash/
.DS_Store
```

This has two benefits. The first is that size and layout options will not be preserved across devices, causing awkward issues when first pulling in updates from another device. The second is that these files/locations may see a lot of meaningless file updates, making your commits slightly messier.

While a small inconvenience to fix upon setup, you'll (hopefully) be opening this vault hundreds of times, and pushing hundreds of changes. Save yourself some time now.

# Commit often

Making regular commits is important for preserving your edit history and making sure that none of your work (even the bad stuff) is lost if edited/deleted. I tend to do it most often when I'm:

1. Before deleting files/content, as even if I hate the work I did, this will ensure I have the content preserved in some way forever through previous git commits.
2. When updating plugins or Obsidian itself, just in case an update breaks a plugin that I find useful.