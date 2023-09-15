</p>
<p align="center">
    <a href="https://discord.gg/cBCbZjhVJU">
        <img src="https://img.shields.io/discord/308323056592486420?logo=discord"
            alt="S.F.H. Discord"></a>

# What is Skript Files Hub?
Skript Files Hub (Also known as S.F.H.) is a Skript file that lets you download files easily into your scripts folder.
All you have to do is load the data in and check the GUI to check any of the Skripts.
# How to upload your files onto the skript?
If you want a file on the list, you must create a link to a raw version of the file, recommended to do this in either using [GitHub](https://github.com/) or [Pastebin](https://pastebin.com/). But first, you need to follow this format.
<details>
<summary>Click to check format</summary>

```
@ Info
	Name: [name of file here]
	Owner: [your name here]
	Description:
	- You can put as many
	- lines in here
	- up to 10
	Version: [server version]
	Dependencies: # NOT REQUIRED, YOU CAN REMOVE THIS PART
	- Skript-reflect
	- SkBee
	# You don't have to set dependencies, this is just incase your
	# file requires any other plugin.
	Item: [item you want displayed ingame here]

@ Code
<your code here>
```

</details>

<details>
<summary>Click to check example</summary>

```
@ Info
	Name: Example
	Owner: KingDooms
	Description:
	- This is a test file
	- used in the SFH discord
	- for people to take use of.
	Version: 1.19.4
	Item: Nametag

@ Code
command /insertingthismightwork:
	permission: *
	trigger:
		send "worked" to player
```

</details>
# Installation 
Download it from releases
Plugins required:
- [Skript 2.7 or newer](https://github.com/SkriptLang/Skript)
- [SkBee](https://github.com/ShaneBeee/SkBee)
- [Skript-Reflect](https://github.com/TPGamesNL/skript-reflect)


