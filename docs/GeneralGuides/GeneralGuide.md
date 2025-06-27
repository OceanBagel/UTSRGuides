# Undertale Speedrunning General Guide

<img src='./Images/UTSRGuidesHeader.png'></img>

## Introduction to Undertale speedrunning

Undertale is generally regarded as a good game for speedrunning. The game has many different endings and ways to play, which adds variety and allows the game to have many unique categories. The game also does not require any unique hardware or anything special for it to be run and recorded, so almost anyone can speedrun the game on their computer.

### Difficulty

As a speedgame, Undertale can range in difficulty depending on the category.  Undertale’s glitch-heavy categories have multiple frame-perfect and pixel-perfect tricks that will need to be performed to get a good time. The menus are simple and limited only by the framerate, so menuing can be done very quickly. Movement is slightly more advanced. You can move in 8 different directions and sub-pixels may have an effect in some parts.

### Knowledge

Undertale contains a variety of different glitches and exploits that will be utilized in many different ways in order to save time. Knowing the exact locations of in-game triggers for events and cutscenes will be very important. Knowing the sequence and specific execution of certain skips will also be required. A general knowledge of some enemy attacks will greatly improve your survivability in boss battles.

### Time

Undertale does not require a lot of time in order to complete a speedrun. Most categories do not require you to play the game for more than two hours in order to complete the game. You will generally take 1 to 2 hours to complete a speedrun, unless you are learning, in which case it may take longer.

## Version Differences

Over the time that Undertale has been released, the game has been updated several times. This section will describe the differences between the various versions. You can see how to acquire the different versions in the next section.

### Version v1.001

This is the slowest version of the game to date. In v1.001, many glitches were patched out that made speedrunning the game slower. Thankfully, with the finding of a new glitch, none of these glitches matter anymore.

### Version v1.0

This was the first version of the game. Although this version has some extra glitches over the Linux v1.001 version, Mad Dummy Skip is impossible on this version, making it much slower in glitched categories. This version was the most commonly used version until the Linux version came out.

### Version Linux v1.001

This version of Undertale was released for Linux users, but with modifications to the file name of the data, it can be used on Windows. This version is unique compared to the others due to one small change. In v1.0 and v1.001 and v1.05+, you cannot press <kbd>Z</kbd> and <kbd>Enter</kbd> at the same time. Holding one down will cancel out the other. However, in Linux v1.001, you can press both <kbd>Z</kbd> and <kbd>Enter</kbd> at the same time, and they will not cancel each other out. This makes mashing text away faster and more consistent. It also makes certain glitches more consistent. This is the fastest version of the game in glitched categories.

### Versions v1.05, v1.06, and v1.08

These versions exist on Windows, Linux, and Mac. v1.08 is the latest version. There are a few versions after the initial v1.05 version, but they function similarly to v1.05. In these versions, the way key inputs are handled is different from the other versions. Some frame perfect inputs are now impossible. Mashing requires a much different method of mashing that is still overall slower than the v1.001 Linux methods of mashing. Standard punchcard overflows are also impossible. There are also considerably more input drops. However, there’s one big upside to this version: Japanese. You can choose to play in Japanese from the main menu. This causes some sections with unskippable text to be much, much faster due to there being less characters. Overall, these versions are faster in almost every category. However, many dislike this version as mashing is more frustrating and overflowing is no longer possible.

There are two differences between v1.05 and the future versions: The Bergentrückung cutscene and the Undyne on the mountain cutscene are both shorter by a few seconds. This makes v1.05 a bit faster.

TL;DR: Versions v1.05 is the fastest PC version for all main categories except Neutral because it has the option to play in Japanese. However, other versions are more desirable to run on due to better input handling. It’s up to you if you want to play on the fastest yet most frustrating version or a slower yet more technical and enjoyable version.

### Versions v1.09+, PS4 etc.

These versions only exist on console versions, such as PS4, Switch, and Xbox. The Switch version in particular is significant due to two version-exclusive glitches, Lemon Bread Skip and Long Elevator Skip. Those are explained in more detail below. Note that you can plug in a keyboard into a PS4 or Switch and it will work fine with Undertale. However, some keyboards with RGB functions draw too much power and as a result will not work. One drawback to console versions is that unlike PC versions, you can’t preload the game when you need to reload. Because of this, console versions are generally slower to run than PC versions in any category that requires reloading the game. Of the five main categories, Genocide is the only category that doesn’t require reloading the game, so the Switch version saves about 20 seconds in that category. There is a method to do punch card overflows on the PS4 and Xbox versions, however, which can potentially allow for some additional time save for glitched categories on these consoles.

## How to change versions

You will need Steam for most of these methods. If you bought the DRM-free version of Undertale, then you should have received a Steam code. Go redeem the Steam code and get Undertale on Steam. This is also assuming you’re on Windows too. If you’re on Linux, the methods of acquiring the versions should be similar. If you're on a modern Mac, unfortunately there is no known way to play any older versions.

### Version v1.0

Right click "Undertale" in your library. Choose "properties." Select the "Betas" tab. Click on the box below "Select the beta you would like to opt into:" and choose "old_version_100". Steam should download the old version of the game.

### Version v1.001 Windows

Right click "Undertale" in your library. Choose "properties." Select the "Betas" tab. Click the dropdown in the top right corner and choose the one labeled "old_version_101 - old_version_101". Steam should download the old version of the game.

### Version v1.001 Linux

If you're using the Linux operating system, follow the same instructions above for "Version v1.001 Windows". On the Linux version of Steam, this beta downloads v1.001 Linux directly.

This version can be a bit tricky to acquire on a Windows PC, but it shouldn’t take too long. Follow these instructions:

1. Make sure you've run Undertale through Steam at least once.
2. Install 1.001 Windows through Steam by opening Steam, right-clicking Undertale. going to Properties, Betas, then clicking the dropdown in the top right corner and selecting the one labeled "old_version_101 - old_version_101". Allow Steam to update the game before continuing.
3. Disconnect your copy of 1.001 Windows by going to `C:\Program Files (x86)\Steam\steamapps\common\Undertale` and copying every file except for the ones named `UNDERTALE.exe`, `data.win`, and `steam_api.dll`, then creating a new folder somewhere else and pasting the copied files into the new folder. NOTE: the game path must only contain ASCII characters, so it cannot contain characters such as Japanese characters, Cyrillic characters, or characters with accent marks. This includes your username, if you created the new folder within your user folder.
4. Open the Steam console by navigating to [steam://nav/console](steam://nav/console) in a web browser.
5. Enter the following command into the Steam console: `download_depot 391540 391544 3991795236625517204`
6. Press Enter, then wait for the game to download. When the game finishes downloading, navigate to the folder `C:\Program Files (x86)\Steam\steamapps\content\app_391540\depot_391544\assets` and copy the file named `game.unx`. Then navigate back to the folder you created in step 3, paste the `game.unx` file, and rename `game.unx` to `data.win`.
7. Copy the file named `UNDERTALE.exe` from [this zip file](https://www.speedrun.com/static/resource/795rz.zip "speedrun.com - 1.001 Linux on Windows runner and installation instructions") and paste it into the folder created in step 3.
8. Run the game from the newly copied `UNDERTALE.exe`, which you will need to use to run the game instead of the Steam shortcut. Check that you've successfully installed 1.001 Linux by playing until you create save data and then searching the folder `%localappdata%` for a folder named `UNDERTALE_linux_steamver`. This is the save folder for 1.001 Linux, and if it was created with your save data then that means you've successfully installed 1.001 Linux on Windows.

If you’re playing on a Linux OS, you can obtain this version by simply following the same instructions as 1.001 Windows above.

### Version v1.05

This version can only be legitimately acquired through the use of the Steam console. Due to this, there is a patch available to convert 1.08 to 1.05.

1. Download v1.08 through Steam. Put all the files from the Undertale Steam folder (usually found at `C:\Program Files (x86)\Steam\steamapps\common\Undertale`) into a new folder.
2. Delete the file called `steam_api.dll` that’s inside the folder.
3. Download [the 1.05 patch](https://www.speedrun.com/static/resource/bjdp7.zip "speedrun.com - Downpatch 1.08 to 1.05").
4. Open the website [https://www.marcrobledo.com/RomPatcher.js/](https://www.marcrobledo.com/RomPatcher.js/ "marcobledo.com - RomPatcher") (or another patching tool like Floating IPS) and do the following:
- ROM file: Choose the file named `data.win` in the copy of the game files
- Patch file: Choose the file `108_to_105_undertale.bps`
- Check to make sure you see a green check mark next to the CRC32 line. If you see the green check mark then move on to the next step. If you see red text and a warning "Source ROM checksum mismatch" then don't proceed to step 4. This means you're patching the wrong files and you'll need to get an unmodified copy of Undertale 1.08 Windows from Steam.
- Click "Apply patch" and then save the patched file in your game folder, overwriting the existing `data.win`.

You’re done! Just launch the game through the file called `UNDERTALE.exe` inside the folder.

If you instead want to download v1.05 directly through the Steam console instead of using the patch, follow these instructions:

1. Make sure you've run Undertale through Steam at least once.
2. Install 1.08 Windows through Steam by opting out of any betas, if applicable. Allow Steam to fully install the game before continuing.
3. Disconnect your copy of 1.08 by going to `C:\Program Files (x86)\Steam\steamapps\common\Undertale` and copying every file except for the ones named `data.win` and `steam_api.dll`, then creating a new folder somewhere else and pasting the copied files into the new folder. NOTE: the game path must only contain ASCII characters, so it cannot contain characters such as Japanese characters, Cyrillic characters, or characters with accent marks. This includes your username, if you created the new folder within your user folder.
4. Open the Steam console by navigating to [steam://nav/console](steam://nav/console) in a web browser.
5. Enter the following command into the Steam console: `download_depot 391540 391541 1584494420689681079`
6. Press Enter, then wait for the game to download. When the game finishes downloading, navigate to the folder `C:\Program Files (x86)\Steam\steamapps\content\app_391540\depot_391541` and copy the file named `data.win`. Then navigate back to the folder you created in step 3 and paste the `data.win` file.
8. Run the game from `UNDERTALE.exe` in the newly created folder, which you will need to use to run the game instead of the Steam shortcut.

How to see if you have v1.05: the main menu should say "Undertale v1.05" at the bottom.

### Versions v1.06+

There is no time difference between version v1.06 and any future PC versions of the game. The current PC version of the game is v1.08. To acquire this version, just download the game through Steam like normal.

## Disconnecting from Steam

If you’re using a Steam version of Undertale, starting up the game will load Steam by default and have it check for updates. This makes reloading the game slower and can result in your game version being “updated” if the version you’re using doesn’t match what Steam thinks you should have. A way around this is to disconnect the game from Steam, which can be done by following the instructions below.

Navigate to the following folder: `C:\Program Files (x86)\Steam\steamapps\common\Undertale`

If you downloaded v1.0: Use 7zip or similar software to extract the `UNDERTALE.exe` file into a new folder. Do not extract it into the Steam folder. Go into the new folder and delete a file called `steam_api.dll`. Launch Undertale from the `UNDERTALE.exe` inside the folder, not from your library on Steam.

If you downloaded v1.001, take the files out of the Steam folder and put them into a new folder. Go into the folder and locate a file called `steam_api.dll` and delete it.

For v1.001 Linux on Windows, if you followed the instructions for acquiring it above, your `steam_api.dll` file should already be deleted.

For v1.05, if you followed the instructions for acquiring it in the previous section, your `steam_api.dll` file should already be deleted.

If you downloaded v1.06+, take the files out of the Steam folder and put them into a new folder. Go into the folder and locate a file called `steam_api.dll` and delete it.

## Exploits and Glitches

### Punch Card Exploit (PCE)

The punch card exploit is a game-breaking exploit that defines Neutral and True Pacifist. To perform this exploit, you will need to acquire a punch card, which you can get from the nice cream man in Waterfall. The Punch Card can be used in many different ways, but the term "PCE" is generally only used to refer to cutscene skips using the punch card. Knowing how to do these can save minutes off your run.

To perform this trick, you will first need to know the exact pixel for a cutscene trigger. You will then need to menu buffer (pressing <kbd>Ctrl</kbd> and an arrow key on the same frame to move 1 pixel with the menu open) onto the pixel. Next, open and close a punch card. You’ll be able to move while the cutscene is going.

### Wrong Warps

Wrong warping is the act of using a punch card or closing a text box on a room transition, which teleports you to the ‘default position’ of the room. The default position varies between rooms, but in rooms with save points it’s generally right next to the save point.

To perform this trick, you will first need to know the exact pixel for a room transition trigger. You will then need to get on that pixel, walk up to a wall, and open your menu. Press <kbd>Z</kbd> twice while preparing to hold arrow keys. You will need to hold one arrow key in the direction of a wall, and another arrow key in the direction of the room transition. Press <kbd>Z</kbd> once more to use the Punch Card, and release the arrow keys. You are now in the room transition, and will need to close the Punch Card before the room finishes transitioning or a softlock will occur. The Punch Card can be closed with <kbd>Z</kbd>, <kbd>X</kbd>, <kbd>Enter</kbd>, or <kbd>Shift</kbd>, so mashing those keys will prevent a softlock.

A wrong warp can fail in three different ways. If the wrong warp occurs and a softlock also occurs, it means that the Punch Card was not closed. If the room transition occurs but a wrong warp does not happen, it means that the arrow keys were not released. If the room transition does not start, it means that either you are not on the correct pixel to wrong warp or you were not holding the arrow keys when you opened the punch card.

### Overflows (Text Storage)

Text storage is a glitch where you gain movement while a text box is open, which gives the appearance of the text leaving the text box. This can be useful in many ways, mainly due to the fact that a text box with text storage acts almost exactly like a punch card, allowing you to perform cutscene skips and wrong warps.

Although text storage in itself hasn’t been patched in recent versions, overflows will not work in versions 1.05 and up. This is due to the input system not allowing 2 consecutive presses of the same key type (<kbd>Z</kbd>/<kbd>Enter</kbd>, <kbd>X</kbd>/<kbd>Shift</kbd>, <kbd>C</kbd>/<kbd>Ctrl</kbd>). However, this limitation can be bypassed on PS4 and Xbox versions by using the console’s pause menu as a buffer between in-game frames, allowing overflows to be possible on these versions.

To perform this trick, walk up to an object. Next, open your menu, go to the punch card and select “use”. Then, press <kbd>Z</kbd> or <kbd>Enter</kbd>. 1 frame later, press the opposite key. If you have succeeded, your punch card will be open over the text box. Close the punch card, and you will gain movement with the text box open. Since this game runs at 30 frames per second, you only have a 1/30th of a second to time it, so it will take some practice to get consistent at.

You can also perform wrong warps with text storage. Simply walk up to a room transition, holding an arrow key next to the nearest wall, and close the text box once you reach the transition. Make sure to let go of the arrow keys beforehand or else the wrong warp will fail.

### Punch Card Advance (PCA)

Punch card advance is a name for a weird phenomenon where opening and closing a punch card during a textbox will grant you movement once the text box is closed. This helps in cases where closing the text box normally locks your movement.

To perform this trick, simply open and close a punch card while a text box is open. Make sure you haven’t skipped the text yet, as the text box must remain open once the punch card is closed. This is one of the more minor tricks, but it has several uses in the route alongside other PCEs.

### Wallhumping

Wallhumping is what happens when both the up and down arrow keys are pressed at the same time while directly below a wall. This can be useful in certain situations such as when interacting with a switch on the wall, and in certain rooms, this can also save time by increasing your speed, most notably the room in Waterfall with a view of Asgore’s castle. While wallhumping, encounter steps continue to accumulate, so this is an easy way to walk in place while grinding for encounters.

### Long Elevator Skip

Long Elevator Skip is a Switch exclusive skip performed by simply walking in and out of the long elevator. Instead of watching the several second long cutscene, you will be teleported instantly to New Home. This saves a significant amount of time in Genocide, and a little in Neutral and True Pacifist. This skip is not considered a glitch as the mechanic was programmed intentionally to work this way, so Long Elevator Skip is allowed in glitchless speedruns.

### Lemon Bread Skip

Lemon Bread Skip is a skip that results from Lemon Bread’s hitbox being smaller in the Switch version than in other versions of the game. It can be performed by simply walking above and past Lemon Bread. This saves a significant amount of time in True Pacifist. There is another Xbox-exclusive version of this skip. To perform this, simply die to Lemon Bread and advance past the Game Over screen and Lemon Bread will no longer block the way.

### Persistence Glitch

The persistence glitch is a way to store the state of a room so that the room will be the same when you return. Persistence is used normally throughout the game for when you enter a battle, which allows the room to return to the state it was in before the battle. Normally persistence is unset upon returning to the room, but by leaving the room on the frame the battle is entered, the new room is unset as persistent while the old room becomes permanently in a persistent state. This has some useful properties, most notably the ability to progress to the post-battle Mad Dummy cutscene after setting the room to persistent and then dying to reload. Persistent rooms will remain persistent until they’re either unset after a battle or the game is restarted (including completing a Neutral ending to return to the title screen).

## Debug Mode

### Information

By editing a certain value in your data.win, you can activate Undertale’s Debug Mode. In the Debug Mode, you are able to teleport, save anywhere, load the save anywhere, trigger battles, and many other things. The primary use of Debug Mode for speedrunning purposes is to, ironically enough, practice glitches and perfect your ability to perform them. Debug mode lets you teleport to any room and save in that room, allowing you practice any time saves that may be in that room. Along with this, you can quickly load the game to try a skip again.

However, you must know that using Debug Mode for a regular run is NOT allowed. It is still disallowed even if you don’t use the Debug Mode’s features. In order to submit a run to the leaderboards or to do a proper speedrun, you must do your runs on the regular, non-edited data.win. To avoid accidentally running Debug Mode, you will want to keep the edited data.win in a seperate folder with a different name, just to make sure you don’t mix up your two data.win’s.

### How to set up

Debug mode isn’t very hard to acquire.

You will first need to disconnect Undertale from Steam (if you already did this, skip this line). Go to the Disconnecting from Steam section to figure how to do so.

Next, locate your data.win. This file will be in your Undertale folder. You will need a hex value editor, like HxD. After finding your data.win, open it up with your hex editor, and change this value from 00 to 01:

Version 1.0 - 725B24

Version 1.001 (Non-Linux) - 725D8C

Version 1.001 Linux - 725DDC

Version 1.05+ - 7748C4

You can use Control + G to search for the specific value.

If you're trying to enable debug mode on a modded version of Undertale (such as the Automasher Mod), these hex addresses may not work. Alternatively, you can enable debug mode using UndertaleModTool.

### General use

There are quite a few different things you can do in Debug Mode, but only a few are really useful for speedrunning. Here’s a list of the more relevant keyboard shortcuts.

Insert and Delete - Teleports you from room to room. Insert advances you forward, Delete takes you back a room.
S - Prompts you to save the game. Can be used anywhere. You can also use this to un-softlock yourself.
L - Load your save.
V - Shows collisions.
F - Makes the game run at 200 fps (or your monitor’s refresh rate - see the note below)
P Outside of battle - Makes the game run at 30 fps if it is already 200 fps, or makes the game run at 200 fps otherwise.
W - Makes the game run at 10 fps.
Backspace (Hold down) - Increases your movement speed.
F7 - Gives you 500 gold.
F9 - Stops all sound.
F10 - Turns off collisions with walls and lets you move even when in a cutscene or screen transition.
R + 6 - puts you in the room after the first save point in Ruins.
T + 6 - puts you in the first room of Snowdin.
W + 6 or F11 - Teleports you to the beginning of waterfall. Teleport a few rooms forward and you’ll be at the nice cream stand.
F + 6 - puts you right at the water cooler room.
E + 6 - puts you right outside New Home.
Y + 6 - puts you at the start of True Lab
1 during battles - Halves game speed.
2 during battles - Doubles game speed.
Delete during battles - Increases HP to 999.
O + P during battles - Enables sparing.
A and S during Asgore’s battle - Decreases (A) or Increases (S) the turn counter. Useful for practicing a certain move during the battle.
NOTE: Going below 0 or above 22 during Asgore’s battle will crash the game.
Four things to note:

If you increase the game’s fps past your monitor’s refresh rate, it will lock in at your refresh rate. However, you can unlock the fps by disabling vsync in your graphics card settings and then running the game in fullscreen.
Teleporting into a room will cause your subpixel alignment to be different than if you just walked into the room.
In Hotland, you will always see Gaster’s followers. In regular play you likely won’t see them.
Asgore’s and Mad Dummy’s battles will be altered slightly. Asgore will have a turn counter. Mad Dummy’s health number will be visible.

### Boss Practice

By using the ‘Home’ key in Debug, you can initiate a battle depending on what your ‘battle group’ is set to. Every battle in Undertale is assigned a specific battle group number. You can edit a value in the data.win to change your battle group, so that whenever you hit your Home key, you will begin the battle on the spot. This is useful for practicing difficult battles. Here’s the values you have to change to set the battle group:

Version 1.0 - 9EB444

Version 1.001 (Non-Linux) - 9F553C or 9EB414

Version 1.001 Linux - 9EB918

Version 1.05 - BD7CE4

Version 1.05a - BD7D2C

Version 1.06 - BD8200

Version 1.08 - BD7810

Here are some useful values you can set the battle group to:

Asgore battle: 65

Asriel battle: FF

Sans battle: 5F

Undyne the Undying battle: 5C

Remember: You are not allowed to use Debug Mode for a normal run. Debug mode is not allowed for speedruns. It is only a tool for practicing skips.

## Practice Mod

Another way to practice is by using the [practice mod](https://github.com/fixylol/UndertalePracticeMod/releases). it provides stuff such as savestates, flag/inventory editing, enabling debug mode & so much more. if you want to practice undertale speedruns, this is the mod for you.

## Preparation before a speedrun

You’ll need to do a few things before you're ready to speedrun Undertale.

### Read the rules

There are a bunch of rules for what can be submitted to the leaderboard in order to keep a level playing field for all runners. Before you start, you'll want to read both the game rules and the category rules by going to the [Undertale speedrun.com page](https://www.speedrun.com/undertale), navigating to the category you want to run, and clicking "Show rules". Most of the game rules are fairly straightforward, but it's still good to be familiar with them to avoid a rejected run submission. Also make sure to pay attention to the category rules, including the start and end points and the category requirements.

### Completely reset your game

If you’ve played Undertale before, then you likely already have a save file. Before beginning any runs, you’ll need to delete that save file. However, unlike most games, when you select “Reset” in the main menu, Undertale isn’t completely reset. Instead, it “pseudo-resets” your game. Characters will still remember you even after you reset. This results in dialogue and other things being different from when you were first running the game.

In traditional speedrunning, a speedrun is supposed to represent a completion of a goal, starting from the very beginning of the game. Basically, you’re supposed to start as if you just got the game. So, because of this, we will require you to completely reset the game. This process isn’t very difficult, you will just need to go diving into some folders in your computer.

Open a new Windows Explorer window (Using Windows Key + R) and enter “%localappdata%\UNDERTALE” into the search bar. Delete ALL the files inside that folder. If you use a controller, you may keep a file called “Config” if you have it. You can find the local app data folder by searching for %localappdata% on your computer.

If you’re using v1.001 Linux, then the save folder will be called “UNDERTALE_linux_steamver”. You can find it by searching for “%localappdata%\UNDERTALE_linux_steamver”.

As already stated, in traditional speedrunning, you have to start the game from the very beginning, meaning the game hasn’t been progressed at all. In Undertale, even if you reset from the main menu, things will be altered from the first playthrough. Characters will remember you and have altered dialogue, and some cutscenes will be skippable. The altered dialogue results in longer or shorter dialogue. This means that people who don’t completely reset will have an advantage over those who don’t. This is why we require you to true reset.

The only categories that have an exception to this rule are the New Game+ categories. These categories require no full resetting whatsoever. If you don’t want to delete your saves, consider running these categories.

### Remove Any Modifications

As already stated in the Debug Mode section of the guide, using Debug Mode is not allowed in speedruns. To acquire Debug Mode, you must edit a value manually within the game. Editing your files is not allowed. Along with this, Debug Mode opens the window for potential cheating or run assistance. Even if you have Debug Mode enabled and don’t use any of the features, the game will still be manipulated and the game will show hidden values during certain fights, which gives an unfair advantage. Before doing a run, you must make sure you are using the regular, unedited data.win. There are very few exceptions to this, so make sure you read through the rules before you start.

### Half Speed Automasher

One of the exceptions for editing data.win is the half speed automasher mod.
The half speed automasher adds the abilty to mash at 7.5 tbps, half of the fastest speed to mash text, by just holding a hotkey (space by default, see readme.txt in the automasher zip file to see how to change that hotkey).
The goal of the half speed automasher is to increase the accessibility of Undertale speedrunning by allowing people who would be unable to mash for accessibility reasons to be able to use an automasher during normal runs.
You can find the link to the half speed automasher, as well as installation instructions [here](https://www.speedrun.com/static/resource/t5gqu.zip?v=7ef12e1 "Link").

## Categories

This section will cover the categories that currently have category guides on the UTSR Guides page. If you're planning on running a category that's not listed here, you can check the top runs on speedrun.com, the Guides section of the Undertale speedrun.com page, or ask in the UTSRC Discord server.

### Main Categories

#### Neutral

Neutral, commonly referred to as Any%, is the shortest of the 5 main categories. It is the most optimized, so at a top level it can be very difficult, but it’s also one of the easier categories to learn.

#### True Pacifist

True Pacifist, also known as TPE, is very similar to Neutral. It’s longer, contains more punch card skips (mainly in True Lab), and the final boss Asriel is one of the most difficult bosses to be completed optimally.

#### Genocide 

Genocide, also known as Geno, is very different from the other categories. Where the other categories are based primarily on execution of frame-perfect tricks, Geno is based primarily on grinding and RNG. It’s generally considered one of the easiest categories to start out with, although Undyne the Undying and Sans can be difficult boss fights.

#### Neutral Glitchless 

Neutral Glitchless is very similar to Genocide, except you abandon the route at Muffet and then continue on to fight Asgore and Flowey. It’s the easiest category to start out with, but it’s also the least run and most players consider it their least favorite.

#### TPE Glitchless

True Pacifist Glitchless, also known as TPE Glitchless, is by far the longest main category, clocking in at just under 2 hours. This category has the least amount of skips of the five main categories, so most of the run is about completing fights and puzzles as quickly as possible and skipping text optimally.

### Misc Categories

### Category Extensions

#### Early Punch Card

Early Punch Card is a Category Extension where you start at the beginning of ruins with a save file with the Punch Card in your inventory. This category allows the player to perform glitches similar to the Neutral and TPE route, but in other parts of the game. This guide covers both the Early Punch Card Early Game category and the Early Punch Card Neutral category.

## UTSR Guides Discord server

If you want to discuss this guide or suggest any changes or improvements, feel free to join the [UTSR Guides Discord server](https://discord.gg/gCRCk3TcGd).

## Credits

For a list of contributors to the UTSR Guides, see the Github repo.

This guide is based on the Undertale General Guide, which in turn was based on Rhombu’s Undertale Speedrunning Guide. The following is a list of past contributors to these guides:
- WinterStormSRL
- OceanBagel
- willyjwillyj
- Shay
- Silver
- TommyeAsY
- Galaxtic
- RichConnerGMN
- WizardVapes
- UberCat
- Jean Poilu
- Vireth
- mrlink2k
- Rhombu
- Valnar
- Jade Vanadium
- Lobo2me
- Cookiepocalypse
- JDLinkMaster101
- Narry
- TGH
- ThaRixer
- Anty-Lemon
- Arnold0
- Xandertje10
- Drakodan
- Firepaw
- Sayuri

This guide was created using GitHub Pages and Docsify, as well as [docsify-darklight-theme](https://github.com/boopathikumar018/docsify-darklight-theme).

Finally, thank you to Toby Fox for making such a great game!
