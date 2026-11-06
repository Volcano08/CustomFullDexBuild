# CustomFullDexBuild

Hey everyone! I found FullDex a little while back and decided to add a few QoL features that I wanted. Mainly, I wanted the ability to play multiple hacks based on the same game. For example, Heartfelt Gold and Iridium are both based on HeartGold. In the original version, both would be assigned `heartgold.sav`, meaning they'd overwrite each other's save files. I've fixed that, so saves are now named after the ROM, just like most emulators do.

I also made the same change for cheat files and images. Cheat files go in a `cheats` folder, while images go in an `icons` folder. You'll generally have to create both of these folders yourself in the same directory where your `roms` folder is located.

I also added the ability to rename your games within FullDex, so everything doesn't just show up as "HeartGold" when you're actually playing a bunch of different hacks.

As of right now, I can only compile Linux AppImages, but I've uploaded the modified source code here. So, if you want to run this on Windows, it's totally possible! You'll just need to download the source code and have a Pokémon SoulSilver (USA) ROM, since the build process uses it to grab the encounter tables.

If you run into any trouble, feel free to ask any AI for help. It should be able to walk you through the process if needed.

Have fun, everyone!

Update: I was able to compile the other versions, including Windows and Mac, but I can only test the Linux AppImage.
