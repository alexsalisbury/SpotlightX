# SpotlightX
![The bar upon launch looks like this, and will disappear when you click off or press Esc:](https://i.imgur.com/ZsW1MnZ.png)

If you don't want to read a bunch of text, visit the [SpotlightX Site](https://torinfelton.github.io/SpotlightX/)


SpotlightX is a minimal, simplistic command bar that makes launching programs or searching things a lot easier than they are with the default Windows 10 search bar. In the future, I intend to go beyond the basic feature set of the Windows 10 search bar and make even more useful commands, while maintaining the simple look and feel of the program throughout (and trying to keep it lightweight).

The general motivation behind this was that sometimes the Windows 10 Search Bar can behave strangely and not do what the user would like, or doesn't have the shortcuts quickly available. For example, even if you type in the same few programs every day to launch, they take a while to be found and sometimes the first result that comes up is a Bing search instead of the program you have installed... SpotlightX doesn't do this, there is no weird determination of results or forcing Bing search down your throat, it just does what you need it to do and disappears after.

## Install

| Release Version | Download |
| --------------- |:-------------:|
| 0.0.1           | [Download](https://github.com/TorinFelton/SpotlightX/releases/tag/V0.0.1) |
| 0.0.2           | [Download](https://github.com/TorinFelton/SpotlightX/releases/tag/V0.0.2) |


## Commands & Basic Usage

#### Press TAB to autocomplete a command or program name to run

https://torinfelton.github.io/SpotlightX/help.html
  

## Current Features

- All shortcuts in the System's start menu & the user's start menu will be loaded and can be ran directly from the bar
- You can load in your own files to be able to run by adding the folder there in via the ```addpath``` and ```removepath``` commands (see above)
- Working tab-autocompletion based on available programs/commands
- Minimialistic Icons & No scary error messages
- Hotkey (Alt + S) to bring up SpotlightX, program runs quietly in the background without interruption and window disappears when not needed
- Search function for Google (though in future you'll be able to change search engine)
- Ability to launch windows settings from simplistic command ("settings <settingpage>"), all settings page names are autocompletable.
  The autocompletion for these setting names has used the ms-settings URI list for all locations [here](https://github.com/TorinFelton/SpotlightX/blob/master/CleanUI/CleanUI/config/ms-settings.txt)
- Ability to change background + text colour

## Goals/Upcoming Ideas

- Custom commands implemented via JSON (hopefully with a UI for the user to edit the JSON with)
- Custom actions for these commands to carry out (e.g run program, set setting, search something, etc.)
- (DONE) Ability to customise icons + style of bar (gradient, colouring, etc.)

# General Look


## Example autocompletion & program run
![When typing in the start of one of the start menu programs, it will autocomplete:](https://i.imgur.com/ei8wNCW.gif)
Typing and autocomplete are <b>not</b> slowed by the program, I have just slowly typed for demonstration.


Pressing enter will run the program, and close the window.

## Search Function + Icon
![Search Function](https://i.imgur.com/DaagPV3.png)

## Launch Settings Function
![Launch Settings Function](https://i.imgur.com/p7wMNS6.gif)
Typing and autocomplete are <b>not</b> slowed by the program, I have just slowly typed for demonstration.

## Error Icon
![Simplistic Error Message - to show invalid command input](https://i.imgur.com/TibVPGY.png)
