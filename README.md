# DiscordRPBlender

![Logo](https://raw.githubusercontent.com/An0n3m0us/DiscordRPBlender/master/images/DiscordRPBlender.png)

Discord Rich Presence for Blender 2.7+ and 2.8 (tested on 2.79 and 2.8 (render information in Internal and Cycles engine only))

[Images](https://github.com/An0n3m0us/DiscordRPBlender/wiki/Images)

DiscordRPBlender currently supports:
- Filename
- Amount of objects / Idle status / Render status (No idle status for Windows and Mac yet)
- Render time
- Time spent on project (not all-time just session time)
- Changing files without turning client off

[Changelog](https://github.com/An0n3m0us/DiscordRPBlender/wiki/Changelog)

### Installation

First, download the Discord App which is available for Linux, Windows, Mac and other devices.

1. Enable Game Activity status in the settings.

2. Download `discordrpblender.py` from this repository and place it wherever you like.

Next, install [discoIPC](https://github.com/k3rn31p4nic/discoIPC).

3. If you haven't got `pip` or `python`, then you can install it manually. Download [discoIPC.zip](https://github.com/An0n3m0us/DiscordRPBlender/raw/master/other/discoIPC.zip) then follow [this](https://raw.githubusercontent.com/An0n3m0us/DiscordRPBlender/master/other/discoIPC-manual-installation.mp4) video guide.

Lastly, [set up a Discord Application](https://github.com/An0n3m0us/DiscordRPBlender/wiki/Creating-a-Discord-Application)

4. On line **22** in the `discordrpblender.py` file, replace the 18 digit number with your clientID (from your Discord Application).

	4.1 Settings are on line **6**. Set them to either `True` or `False`.

5. Run Blender in the cmd/terminal like so: `blender -P PATHTOSCRIPT.py` (example: `blender -P /tmp/discordrpblender.py`)

### Credits

Credit to [k3rn31p4nic](https://github.com/k3rn31p4nic/) for the [discoIPC](https://github.com/k3rn31p4nic/discoIPC) module for Python.

Big thanks to eKross for testing DiscordRPBlender for 2.79 on Windows!

### License
[CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)

