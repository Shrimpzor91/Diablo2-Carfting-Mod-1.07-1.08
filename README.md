# Diablo2-Crafting-Mod-1.07-1.08
This mod to your game should enable the crafting recipies that are in the 1.07 and 1.08 versions of Diablo 2 LOD. However, these recipies are extremely buggy in 1.07 and should be used at your own risk.



How to install:

cubemain.txt is the text file that Diablo 2 uses to generate the parameters for crafting. I have modified the file to enable all recipies, and have also fixed specific recipies that were broken. "See my youtube serries for details" https://www.youtube.com/watch?v=hIcx_vuRo9E

In order to apply the modified crafting table you must have a working version 1.07 or patch 1.08 Diablo 2 installation. In order to use this mod, do the following:

1.) Find your Diablo 2 installation and locate the folder where are the mpq files live (if you are using a version switcher find where your patch.mpq file for the respective patch). Create a set of nested folders named data -> global -> excel. This mimics the structure that cubemain.txt would be in if you opened Diablo's actuall patch file. Place my modified cubemain.txt file in there and make sure you do not change the name.

2.) Next we need to politely ask Diablo to check for this file on startup. We do this by running the game using the -direct -txt commands. You can do this by making a shortcut of diablo, going to properties and added this after the path (outside the quotes). Alternatively, version switchers like Cactus (reccomended), have a "flags" section when setting up the profile. You can put -direct -txt there.

When the game launches using these two commands it will first check for text files when attempting to create the binaries it uses for reference tables. This will essentially launch the game with my cube modifications, without affecting your existing mpq files in any way. No replacement is neccesary and if something goes wrong, you can simply launch the game normally.

**Warning:**
This is currently in beta testing. All the crafted recipies work but you probably shouldn't use anything that gives - enemy resist or +x per character level mods on your main characters. I haven't tested these and they may give errors that corrupt save files. I don't know for sure what will happen. If you do want to test these items, do it with hero editored characters you are willing to risk.
