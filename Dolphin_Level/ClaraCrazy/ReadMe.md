# Change your Flipper level (ClaraCrazy / Dexv fixed ones)!

## NOTE: Changes in recent Official firmware require the file to start with a `.`

Github doesn't always like files that start with a period so please make sure it still starts with a period after download.

## How to change your level (upgrade or downgrade)

If your flipper level is moving too slow for you, there are ways you can fix that! Are you are the tinkering kind? See [DroomOne's](https://github.com/DroomOne/FlipperScripts) Python script. (All the files below were made with this script.)

If you would rather just "git'r'done" then grab one of the files here that correspond to the level you want.

All files are status "Wet" with `Butthurt` at 0. The corresponding level is at the end of the name.<br>
Files in the `AT_LEVEL` folder take you directly to the stated level with a message that you leveled up.<br>
Files in the `TOP_LEVEL` put you one step away so the next action you perform will cause you to level up.<br>
BONUS: The file `.dolphin.state.XXX` takes you to exactly 6969 XP (Level 25 with 6969/7100)

**Simply download the file named for the level you want (like `.dolphin.state.LVL30`).**

Now that you have downloaded the `.dolphin.state` file you want to a location you know, RENAME IT to just `.dolphin.state`<br>
Next, open up qFlipper and head to the file browser section to transfer your new file:

![File_browser](https://user-images.githubusercontent.com/57457139/169634442-38acca0a-94e0-4038-aa54-dd33ebdffa29.png)

You should see the internal and external (SD) there - double-click on `Internal Flash`:

![Int_Flash](https://user-images.githubusercontent.com/57457139/169634459-a9e87dac-d180-4e09-b047-86dc7cad49f9.png)

There's not a lot here, but the important file is! Enable hidden files and you should see a `.dolphin.state` file already present:

![Dolphin_State](https://user-images.githubusercontent.com/57457139/181995552-43311409-227a-4e70-a736-b5dcff6df3ac.png)

Right-click on it and select "Rename..."

![Rename_File](https://user-images.githubusercontent.com/57457139/181995473-8a41b499-7e14-40d6-b770-5428f5e76dd4.png)

Give it a name that you'll know what it is still and can go back. I picked `.dolphin.state.mine`:

![Renamed_File](https://user-images.githubusercontent.com/57457139/181995480-8c88a714-7b6f-4c90-8244-c1a5b2149ea6.png)

Great! Now drag and drop the `.dolphin.state` file you downloaded from this repo right into the same spot:

![Copy_New_File](https://user-images.githubusercontent.com/57457139/181995490-882fac5d-01f8-4174-9ac7-eef23e556058.png)

That's it! Now [restart Flipper](https://docs.flipperzero.one/basics/reboot) and enjoy your new level!

![6969](https://user-images.githubusercontent.com/57457139/209627160-8373f563-229f-4415-8765-68b0fa602200.png)

If you find yourself longing for your original friend as it was, it's easy to go back. Repeat the process above, but now DELETE<br>
the `.dolphin.state` file, then rename your `.dolphin.state.mine` (or whatever you picked) back to `.dolphin.state`.<br>
Finally, restart Flipper again and you should be back to where you started! (This can be done as many times as you like.)

