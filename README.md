# README

This note explains how to interact and callaborate on the Generative Process within Obsidian.

## General Information
If you don't already have a Github account, please sign up for one. This will allow you to create a copy of the information and modify it without worrying that the edits are permanent. You will also need to install Git if you do not alread have it. Instrutions on this process are below.

### Quick start
Content is stored at the following loctations
- The Org is called "SoCoDoJo": https://github.com/SoCoDoJo
	- This a place where other artefacts besides Obsidian can be stored
- The repo called "Generativeprocess" is an Obsidian vault and contians all the notes from C1: https://github.com/SoCoDoJo/Generativeprocess

Forking the repo to your own profile is best practice. Updates made there will not affect anyone else unless a pull request is made to the org, at which point modifications you have made can be integrated. 

### Detailed setup
This guide assumes that you are essentially new to computer science and coming at this from ground zero. It is consequentially verbose and many of the steps are a one time process enabling you to set up your local environment. 

This guide was written based on the Windows installer as it was the use case we were working through, though Mac and Linux are probably very similar - if thats what you have and find any discontinuities, your encouraged to record the details and/or ping a peer within our group that can help (Josh for now). If you are using one of these operating systems, it would be great if you can help correct any inaccuracies - contributions in this way are very welcome. 

#### Installing Git (one time thing)
- Download and install Git from the following link: https://git-scm.com/downloads
	- If you are on a Mac you can optionally open up a terminal and type `brew install git`. This has advantages to an installer that will become apparent later in your journey if you choose to keep learning the inner workings of your machine (dotfiles). Either option is fine for now though, and the link is probably easier if your fresh.
- It will open up a wizard with many confusing options, safe options are documented. If you know what you are doing, feel free to select alternatives. If you don't just tick these boxes and you should be fine. This guide assumes you may contribute to other projects in the future and so recommendations take this into account. You can always change your configuration at a later date.
- Editor: Any, you will not use them for our purposes. VScode is recommend as an editor for junior developers, but this is not installed on your computer by default. Nano is a safe option.
- Branch naming: Select override and call it `main`
- Path dependencies: Git from command line and also third party software"
- SSH: bundled SSH
- HTTPS Transport back end: Use open SSL libraries
- (Windows install) Configuring line ending conversionss: "Checkout windows style, commit unix style line endings". This is probably MacOS when installing on a Mac, Linux for linux. 
- (Windows install) Configuring the Terminal emulator: "Use windows console window". On Mac this is probably "Use macOS Terminal".
- Default behaviour of Git pull: "default; fast forward or merge".
- Credential helper: "Git credential manager core"
- Enable file system caching: Yes.
- Enable symoblic links: No.
- Experimental options: None.
- Select install to finish the installation. 

#### Using Git and Github to download files
Assuming that you have a Github account as instructed in the General section please go to the repo where the notes are stored: https://github.com/SoCoDoJo/Generativeprocess

- Find the button in the top right corner of Github named "Fork" and click it to make a copy of the files to your own profile. This will become your own space. 
	- If asked if you want to fork the repository or branch, select repository. You want the whole thing.
- This should take you directly to the copied repo on your own page. If it doesn't go there.
- Find the green "code" button near the top right hand side and click it.
- You'll see a link and a copy icon to its right. Copy this to your clipboard.
- Open up a "Shell":
	- On Windows this is called a command prompt. You can do this by typing "Command Prompt" into the search bar. 
	- On Mac this is called the terminal. It can be found in the following directory : apps>utilities>terminal (or by seraching "Terminal" in Spotlight)
	- You need to make a personal decision where you wish to store the vault. Documents is not a bad place to do so. Useful commands to help navigate:
		- `pwd` lists your current location. It means path working directory.
		- `ls` and `ls -a` lists the contents of the folder your in. On windows its `dir`.
		- `cd` means change directory. Type this followed by a space and the folder you wish to open, or type `cd ..` to go back a level in the folder hierarchy. 
	- Once you are in the folder you wish to store the vault in, your going to download it.
	- Type `git clone`, space, and paste the link you copied from your github repo.
		- If you find an error here, its because you had a shell open when you started the Git install. Just quit the shell, reopen and try again. It shouldn't happen if you've followed this guide precisely, but its worth noting. 
	- Once the clone operation is complete you can close the shell. You'll be able to look in your documents folder (or alternative location) and see that the Obsidian Vault is there. You can now safely forget everything you've just been through, though some of these skills may be helpful in the future. 

#### Gettin notes into Obsidian
- Download Obsidian from: https://obsidian.md
- Open Obsidian. It will be blank for now. 
- to open the vault you just downloaded click "Open another vault" at the bottom of the ribbon on the left hand side.
- Select "Open folder as vault"
- Select the vault you downloaded and Obsidian will populate with notes.


#### Setting up automatic backups
- In the left hand ribbon select "Settings" and then click the title "Community Plugins"
- Turn off safe mode
- Click the "browse" button
- Search for "Obsidian Git"
- Click Install
- Exit back a step to the "settings" home page (or just enter the settings page again)
- Click the title "Community Plugins" and you'll now see "Obsidian Git" installed. Turn the switch on and you'll see Obsidian-git is now listed under the header of "Plugin options" on the left hand side of the window you currently have up (settings). Click "obsidian-git" to set up your backup preferences. Most options can be ignored but:
	- 2 min is a good number for auto pull and backup options. 
	- Pull updates on startup: on
	- Pull changes before push: on
	- Disable notifications: on (otherwise you get a pop up every 2 min)
	- Authorise git for obsidian with your computer password when it makes the first backup and prompts for this. 

YOU ARE NOW SETUP!

#### Other info
The structure of the vault currently has a lot of redundant  "index" pages (duplication over scale). This was just to demonstrate possibilities and we may wish to prune some of these. The structure we wish to embrace should be deliberatly pruned by Ronens dictation or if he wishes a consensus modality. 


#### Pull Requests
When you have a contribution that you wish to add to the SoCoDoJo repo you need to make a pull request. This is the equivelent of saying, "hey, I've made changes to your repo - do you want to add them?". This can be done in several ways but using the Github GUI is probably the easiest. 

- Make sure changes made in your vault have been pushed to your fork on github. Obsidian is setup to do this automagically but outside of our specific context it may not be 

