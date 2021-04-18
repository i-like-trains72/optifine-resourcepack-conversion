# shaders-with-sodium
This is a small repository designed to help users who want shaders with Sodium but without using Iris or vanilla Fabulous shaders .
If you don't know already, Sodium does NOT work with Optifine shaders. This can be overcome using [Iris](https://github.com/IrisShaders/Iris) but it requires a decent amount of technical know how.

**NOTE: Both [MCPP](https://github.com/LambdAurora/MCPatcherPatcher) and [Colormatic](https://github.com/kvverti/colormatic) are under the [LGPL License](https://github.com/LambdAurora/MCPatcherPatcher/blob/main/LICENSE) and [FabricSkyBoxes](https://github.com/AMereBagatelle/fabricskyboxes) is under the [MIT License](https://github.com/AMereBagatelle/fabricskyboxes/blob/1.16.x-master/LICENSE). All three binaries which I have provided are unmodified from the original source code.**

This repository is under the [LGPL license](LICENSE.txt), which you can see below. Before asking for support, please be aware of its terms.

Alright, onto the actual thing. NOTE: This guide assumes you know how to install mods on the **Fabric** modloader and load resourcepacks. I'll be including more complicated instructions that make this work slightly (for now) better, this will be geared towards people who have more technical know-how.  

If you want me to change something or you find an error, just make an issue and if you want to do something *big*, make a pull request please.

Also this guide assumes you have Sodium installed already. Additionally, if you want that sweet, sweet, connected glass, I'd *highly* recommend this [Gist](https://gist.github.com/DragonEggBedrockBreaking/c1ddf9c2543ad0d56b8e49f80c283b99)

Steps:
1) Download the latest release from the releases page.
2) Extract the .zip into a separate folder. Do NOT extract the resourcepack after extracting the release, it is a .zip by default and will not work if you extract it.
3) Go to your `minecraft/mods` folder and paste the mods from the extracted .zip into that folder. 
4) Go to your `minecraft/resourcepacks` and drop the resourcepack into the folder. 
5) That's it! You're done
6) Now launch your game
7) Load the resourcepack that I included (it should go over all the other ones no matter what. Some exceptions apply, just make an issue and ask me)
