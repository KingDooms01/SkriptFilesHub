</p>
<p align="center">
    <a href="https://github.com/KingDooms01/SkriptFilesHub/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/KingDooms01/SkriptFilesHub?color=0088ff" />
    </a>
    <a href="https://github.com/KingDooms01/SkriptFilesHub/releases">
      <img alt="Issues" src="https://img.shields.io/github/v/release/KingDooms01/SkriptFilesHub?style=flat" />
    </a>
    <a href="https://discord.gg/cBCbZjhVJU">
        <img src="https://img.shields.io/discord/1150768660328226836?logo=discord"
            alt="S.F.H. Discord"></a>


# What is Skript Files Hub?
Skript Files Hub (Also known as S.F.H.) is a Skript file that lets you download files easily into your scripts folder.
All you have to do is load the data in and check the GUI to check any of the Skripts. 
It adds the command /skriptfileshub (or /sfh), which pops up a gui, allowing you to choose any file to download onto your scripts folder. (IF NOTHING IS SHOWN, RELOAD THE SFH FILE).
# How to upload your files onto the skript?
If you want a file on the list, you must create a link to a raw version of the file, recommended to do this in either using [GitHub](https://github.com/) or [Pastebin](https://pastebin.com/), then making a file with the format below. ou also have to [join the discord (click here for link)](https://discord.com/invite/cBCbZjhVJU) in order to create a ticket and request to upload a file.
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

[Click here for a video for more info on how to upload file](https://youtu.be/Nr2W8QCvcq8)

# Installation
Download it from releases
Plugins required:
- [Skript 2.7 or newer](https://github.com/SkriptLang/Skript)
- [SkBee](https://github.com/ShaneBeee/SkBee)
- [Skript-Reflect](https://github.com/TPGamesNL/skript-reflect)


