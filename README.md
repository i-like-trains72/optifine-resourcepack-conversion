# Shaders With Sodium
This is a relatively simple guide designed to help users who want "shaders" with Sodium but dont want to use Iris or Fabulous (vanilla) shaders. If you didn't know already, Sodium does NOT work with Optifine shaders. This can be overcome using [Iris](https://github.com/IrisShaders/Iris) but it requires a decent amount of technical knowledge, and Fabulous (vanilla) shaders can be very heavy on system resources. Screenshots are further down.

**NOTE: Both [MCPP](https://github.com/LambdAurora/MCPatcherPatcher) and [Colormatic](https://github.com/kvverti/colormatic) are under the [LGPL License](https://github.com/LambdAurora/MCPatcherPatcher/blob/main/LICENSE) and [FabricSkyBoxes](https://github.com/AMereBagatelle/fabricskyboxes) is under the [MIT License](https://github.com/AMereBagatelle/fabricskyboxes/blob/1.16.x-master/LICENSE). All three binaries which I have provided are unmodified from the original source code.**

This repository is under the [LGPL license](LICENSE.txt). Before asking for support, please be aware of its terms.

---

This guide assumes you know how to install mods on the **Fabric** modloader and how to load resourcepacks. I'll be including more complicated instructions that make this work slightly (for now) better, which will be geared towards people who have a higher level of technical understanding.  

If you would like me to change something or you find an error, just make an issue and if you want to do something *big*, make a pull request please.

Also, this guide assumes you have Sodium installed already. Additionally, if you want that sweet, sweet, connected glass, I'd *highly* recommend [this gist](https://gist.github.com/DragonEggBedrockBreaking/c1ddf9c2543ad0d56b8e49f80c283b99) by DragonEggBedrockBreaking.

Finally, I wanna mention that there's a program called MCPPPP that's basically MCPP but it's written in C++, and it is slightly more difficult to use. I'd recommend using it if and only if you know how to find the path to a folder, and don't mind the lack of a graphical interface. I'll be adding a guide on the more complicated part at a later date. 

---

Screenshots of what this actually looks like:
![huge_2021-04-18_17 37 48](https://user-images.githubusercontent.com/82773235/115161892-260a7b80-a06e-11eb-9249-0783c52ee721.png)
![huge_2021-04-18_17 43 11](https://user-images.githubusercontent.com/82773235/115161893-260a7b80-a06e-11eb-857f-bb46c40b7aef.png)
![huge_2021-04-18_17 43 30](https://user-images.githubusercontent.com/82773235/115161894-26a31200-a06e-11eb-8a59-2e037c6a6951.png)
![2021-04-18_17 33 51](https://user-images.githubusercontent.com/82773235/115161895-26a31200-a06e-11eb-85b2-5746064edd80.png)
![huge_2021-04-18_17 33 55](https://user-images.githubusercontent.com/82773235/115161896-26a31200-a06e-11eb-96c7-bd22ec230f29.png)
![huge_2021-04-18_17 37 20](https://user-images.githubusercontent.com/82773235/115161897-273ba880-a06e-11eb-852d-f71edab8b4b8.png)

Those screenshots are with the resourcepack I included.
Here are some screenshots with the resourcepack I included and a second one:
![huge_2021-04-18_17 48 28](https://user-images.githubusercontent.com/82773235/115162025-0162d380-a06f-11eb-8671-1c00154b807a.png)

Fun note: The mountains are *blue*, I have no clue why. If I had to guess, it's due to MCPP having some bugs with conversion but I still think it looks quite good. 
![huge_2021-04-18_17 54 10](https://user-images.githubusercontent.com/82773235/115162065-3f5ff780-a06f-11eb-8622-7e74c93585ef.png)

This next screenshot is using the more technical way that should make things look slightly better
(I haven't gotten around to taking it yet)



---

### Steps:
1) Download the latest release from the releases page.
2) Extract the .zip into a separate folder. Do NOT extract the resourcepack after extracting the release, it is a .zip by default and will not work if you extract it.
3) Go to your `minecraft/mods/` folder and paste the mods from the extracted .zip into that folder.
4) Now is a good time to install [ModMenu](https://www.curseforge.com/minecraft/mc-mods/modmenu) if you haven't already. You'll    
5) That's it! You're done with the hard part
6) Now launch your game
7) Load the resourcepack that I included (it should go over all the other ones no matter what. Some exceptions apply, just create an issue report and ask me)
8) need it to configure one of the mods.
9) Go to your `minecraft/resourcepacks/` and drop the resourcepack into the folder. 
10) Load the resourcepack and enjoy!
This next bit is OPTIONAL. I highly recommend turning on Clear Skies and enabling block flickering if you want it to look better. 
12) Hit ESC on your keyboard and go to Mods. Search for Colormatic. In the top right, there'll be a small icon that looks like this ![image](https://user-images.githubusercontent.com/82773235/115439311-70aa0600-a1dc-11eb-85ed-2a3a3e092cfc.png)
13) Now click on it and go to the 'Fog & Sky' button.
14) Click Clear Skies if you want to remove the horizontal banding at the sky's horizon. 
15) If you don't want block flickering (light from torches/lanterns/etc. will flicker), go to 'Lighting' and disable it.
16) You can experiment more, and once you're done changing it to your hearts' content, click Save & Quit and go back to the game

---

And you're done! Go get yourself a choccy milk and congratulate yourself. 

Well...if you're reading this you want the technical version, right? To do this, you need to be reasonably tech savvy; but you need these skills: if you know how to find the path to a folder, and don't mind the lack of a graphical interface to use the program.
1) Close your MC if it's running. You don't need to unload or reload the resourcepacks.
2) Grab MCPPPP from [here](https://github.com/supsm/MCPPPP) and follow the instructions on it.
**NOTE: Leave MCPP in the mods folder.** Due to some issues with MCPPPP, certain conversions are a little funky and MCPP will still do the bits that MCPPPP can't do. If you do not notice a difference right now, that's okay. You will see a difference once MCPPPP is more fleshed out
3) Once you've finished converting the resourcepack(s), load up your game
4) Load the resourcepack if you unloaded it.
5) Now you can go to step 12 of the easy guide and do that to configure your game more

That's it! You're done and now you have some yellowy torch light and soft blue lighting outside. 
