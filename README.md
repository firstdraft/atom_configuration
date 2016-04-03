# Atom Configuration

We're going to be using the plain text editor Atom for all of our code-writing in this course. In this guide, I'll show you the tweaks that I use to make it as helpful as possible.

First, [download Atom](https://atom.io/) and install it.

## Settings

After you've installed Atom, launch it, and then

 - Mac: Atom menu > Preferences
 - Windows: File menu > Settings
 
Here are the settings that I like to use:

	- Uncheck “Exclude VCS Ignored Paths”
	- Set a font size if you like.
	- Check “Scroll Past End”
	- Check “Show Indent Guide”
	- Check “Soft Wrap”
	
## Packages

Next, find the "Packages" tab on the left. Packages are plugins that add extra functionality to Atom, and developers are releasing new ones all the time.

Atom comes with some packages includes, which we need to tweak a little:

 - **MANDATORY:** Search for the package "autosave".
 
     **After it comes up, click its "Settings" button. There should be a checkbox there to "Enable". This is different from the package itself (in the search results) being enabled or disabled. Check the "Enable" box inside of the package settings.** We may not have done this step together in class.
     
     This package makes it so that whenever you switch from Atom to Chrome, all of your changes to any open files are automatically saved. This is a huge help when we start working on 2, 5, or even 10 files at once.

 - Search for the "git-diff" package and in its settings check "Show Icons".
 - Search for the "tree-view" package and in its setting check "Auto Reveal".

Furthermore, lets install some third party packages from the community. Click the "Install" tab on the left sidebar, and search and install:

 - Sublime-Style-Column-Selection by bigfive
 - less-than-slash by mrhanlon
 - atom-wrap-in-tag by sanusart
 - emmet by emmetio
  
## Themes

If you like, you can select a different theme. I use the built-in Atom Light in class. There are also lots of [community-provided themes](https://atom.io/themes/list?direction=desc&sort=downloads).

## Add Additional Keyboard Shortcuts

 - In Keybindings, find the section for your platform in [this gist](https://gist.github.com/BinaryMuse/621bf3e66a66876e4d78#file-sample-keybinds-cson) and paste it in.
 - Also, paste this:

        'body':
          'cmd-ctrl-w': 'tabs:close-all-tabs'
