This section goes over some common technical help people need for TETR.IO.

# Configuration
Sometimes you're just trying to [squeeze some more optimization out of TETR.IO](https://tetr.io/about/performance/ "TETR.IO's own PERFORMANCE TIPS guide"), or you're trying to use specialized control settings and you're not sure how it all works. This section here aims to help you!

## TETR.IO->Discord Account Linking
If you're interested in linking your Discord account to your TETR.IO account, navigate to CONFIG > ACCOUNT > CONNECTIONS, as detailed in this `.gif` file: 

<img width="768" height="520" src="https://user-images.githubusercontent.com/64891705/153960535-b9c6b63e-a607-45df-992c-2fc6d5f2eeb7.gif">

This link is currently used to grant the "Supporter" role to TETR.IO supporters, and to provide account verification for [the Character System playtester application form](https://insider-applications.osk.sh/). If you have recently purchased or been gifted supporter, you shouldn't have to wait too long before the role is automatically given to you, so long as the *@TETR.IO* bot is online. If you're having trouble linking your account, and are using TETR.IO Desktop, try linking from the website version instead, as this is less prone to error.

## Controllers
TETR.IO includes full controller support, *even commanding dynamic vibrations for different actions,* be it from your modern browser, or from [the official TETR.IO Desktop client](https://tetr.io/about/desktop/). Just connect your controller of choice and bind it manually in the ingame config:

<img width="948" height="360" src="https://user-images.githubusercontent.com/64891705/153961020-037cf09d-6f73-4bc3-970a-eef4d19d7ced.gif">

If your controller isn't working, here's a couple of different pointers to direct your attention towards:
* First off, ensure any D/XInput redirection isn't active. **This includes software like Steam or JoyToKey.**
* Ensure the controller you're attempting to use is **the only controller connected.** TETR.IO only accepts input from so-called "port one", though, there are plans to remedy this issue. If you had other controllers plugged in, a **restart** of the pc may be required.

If neither of these troubleshooting steps work, here's some specialized software for specific controllers:
* **PS4/PS5's DualShock** lineup: use [DS4Windows](https://github.com/Ryochan7/DS4Windows/releases/tag/v3.0.18)
* **Nintendo Switch's Joy-Con or Pro Controller** controllers: use [BetterJoy's "ShowAsXInput" function](https://github.com/Davidobot/BetterJoy/releases)

# TETR.IO Desktop Specific Troubleshooting
*TETR.IO DESKTOP IS MULTIPLE ORDERS OF MAGNITUDE FASTER THAN THE BROWSER!*
*enjoy uncapped framerates, faster startup, discord integration and more with [the **official** desktop client](https://tetr.io/about/desktop/)!*
\- Ingame banner ad, 2021

### Dedicated Graphics
Are you using a laptop and getting poor performance with TETR.IO Desktop or browsers? If so, you'll want to ensure Windows is using your "dedicated" graphics card, as opposed to the less performant, yet more power efficient "integrated" graphics card Windows is likely selecting for you. You can override this autoselection by following this lengthy image guide:

![](https://cdn.discordapp.com/attachments/673305614318960671/851893786707230720/unknown.png)

* If you use TETR.IO Desktop, then you will find the executable in `%localappdata%\\Programs\\tetrio-desktop\\resources`
* If you use Chrome, you may find it in `%programfiles%\\Google\\Chrome\\Application\\chrome.exe`, `%programfiles(x86)%\\Google\\Chrome\\Application\\chrome.exe`, or `%localappdata%\\Google\\Chrome\\Application\\chrome.exe`
* And, if you're a Firefox kinda guy, then you will find Firefox's executable in `%programfiles(x86)%\\Mozilla Firefox\\` or `%programfiles%\\Mozilla Firefox\\`, depending on which architecture (32 or 64 bits respectively) your computer currently has installed

### Broken Installer
Is your TETR.IO Desktop installation getting stuck? Here's a workaround:
You can use a *good* archiving program, such as 7zip(<https://www.7-zip.org/download.html>), to manually extract the game's contents for a much more manual installation for now. Here's a quick video guide(really, just open the `.exe` as a compressed folder and drag stuff out!): 

<img width="805" height="540" src="https://user-images.githubusercontent.com/64891705/153961240-40cabccf-9c68-4fab-bd29-e2091ac6746c.gif">


### Installation Locations
If you use TETR.IO Desktop, then you will find all installed files in the following folders: Use `Windows+R` and paste the following paths into the **r**un dialog that opens
* `%localappdata%\Programs\tetrio-desktop`
(The `.exe`cutable and `Resources` folder is found here)
* `%localappdata%\tetrio-desktop-updater`
(Contains a single `.exe`cutable, which is a copy of the original TETR.IO Desktop installer you installed your current version of TETR.IO Desktop with. Run this file to clear any modifications you may have on the game)
* `%appdata%\TETR.IO`
(Contains one empty folder: "logs")
* `%appdata%\tetrio-desktop`
(Contains Electron related browser files. Two such examples: `Cache` and `Local Storage`)

# Replays
Loading replays is super easy, if not slightly obscure. It's asked so often I made this dedicated section to it, so don't fret if you're about to go "that's so simple!"
*(also see)*
* Tenchi's FAQ on
1. [Where replays are saved](https://tetrio.team2xh.net/?t=faq#replays-location)
2. [When replays are saved](https://tetrio.team2xh.net/?t=faq#replays-saved)
3. [Visual language within the replay timelines](https://tetrio.team2xh.net/?t=faq#replay-icons)

***

To view a locally saved replay, simply drag and drop the file from your file manager of choice into TETR.IO. If TETR.IO fails to load the replay, please ensure the replay is correctly named, specifically: 
* for solo replays of any sort, use the `.ttr` file extension
* for multiplayer replays of any sort, use the `.ttrm` file extension
* for solo custom game setting presets, use the `.ttp` file extension
* for TETR.IO config exports, use the `.ttc` file extension.

<img width="1075" height="549" src="https://user-images.githubusercontent.com/64891705/154011440-96a40b8c-e9e6-41ee-958d-87ee4af01a4c.gif">
<img align="right" width="430" height="213" src="https://user-images.githubusercontent.com/64891705/154011502-f5d7fd12-13c0-4107-be51-0fa6f760f499.gif">

If you load a `.ttrm` file, simply click on the individual rounds to watch that round's replay.

## Online Custom Room Replays
Replays taken in this context rely on some unconventional requirements, so don't blame yourself if that ever-so-required "DOWNLOAD REPLAY" button doesn't show up in here. Here's some requirements off the bat:
* The room **must** be a two player match, one versus one.
* Your client, not theirs, *should* be using LOW graphics or higher.
* If using MINIMAL, [the "SHOW DUELS SIDE BY SIDE" option **must** be enabled.](https://tetr.io/about/patchnotes/#chlog_5_2_0)
* You **must** persist from the start of the match, even in a FT5 (example) game, to the end of the match.
* Of course, you **must** download the replay from the results screen. There'll be a small button to the right, under the 2nd player's spot in the list.

# Mobile Support
First off, we have to break some news. [TETR.IO will never officially support mobile devices](https://discord.com/channels/673303546107658242/673305735811170305/901428890025738280)

That being said, there are still some ways to **play TETR.IO on phone**! Here's one quick rule, though: it **cannot be any iOS-based Apple device.** This is **absolute**, TETR.IO simply [will not load under WebKit](https://github.com/tetrio/issues/issues/425). Otherwise, you're welcome to try with any android device, but compatibility is *not* guaranteed as these are unsupported platforms!

To load TETR.IO on mobile, just visit <https://tetr.io/> on your mobile browser of choice. *That's it!* The real problem arises when you attempt to *control the game,* so there's a couple of different attacks you can use. The first would be simply connecting any conventional controller through bluetooth or usb, and binding that controller in TETR.IO's config natively.

The second workaround involves using what's known as a "bookmarklet", which is basically JavaScript code you run from a bookmark, to create **onscreen touch controls**. A specialized site to generate these bookmarklets may be found [here](https://you.have.fail/ed/at/tetrio/touchcontrols/). There's included instructions in this site once you've defined your controls.
