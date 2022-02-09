# Personalization
This section largely goes over some of the confusing aspects users run into while customizing their account or game visuals.

## Profile Customization
Registered users can customize their ingame appearance through a variety of ways, both paid and unpaid. Here's some common missteps people fall in:

### Registration
Welcome to TETR.IO! While you can play with a far less involved "anonymous" account,(see below for details) a fully registered account is your only ticket into the TETRA LEAGUE, saved 40 LINES and BLITZ records, access to a customizable profile card and userpage(such as profile pictures: refer to FAQ entry below), and more!

![](https://cdn.discordapp.com/attachments/673303546564968566/897041837213224980/register.png)

**To create a TETR.IO account**, first, navigate to https://tetr.io/. You will be greeted with the registration dialog immediately, provided you aren't already logged in(1). From here, 
1. enter your chosen username(1.1) and click the JOIN button(1.2). 
2. **If the username is taken, you will be prompted for its password(2)**: in this case, back out and choose another username(2.1). 
3. If the username is unoccupied, you will be prompted to either "STAY ANONYMOUS" or "REGISTER"(3). 
4. After selecting REGISTER, you will be asked to supply an optional email, as well as the password you will lock your account with(4).

Please note that you are only allowed one registered account as per the alt policy found at <https://tetr.io/about/rules/>! Choose your name wisely: future name changes are only available with the purchase of TETR.IO supporter.

#### Logging Into Your Account
Logging into your registered account is easy, if not slightly obscure. The registration form doubles as a login questionnaire, so, if you know your username and password, just follow these steps!

![](https://cdn.discordapp.com/attachments/673303546564968566/897061029782102026/register.png)

1. When prompted to "ENTER A USERNAME TO JOIN"(1), enter in your registered account's username(1.1) and choose JOIN(1.2).
2. You'll see a section(2) asking for your password at this stage(2.1), enter that in and click LOGIN(2.2). That's it!
##### Resetting a Password
If you've forgotten your password, click I FORGOT(2.3). You'll be brought to an extra question asking you for the email tied to this account(3). Ensure you enter your email **exactly as you entered it while registering!** Case sensitivity doesn't matter, but do try a couple different emails before throwing in the "i musta not entered an email" hat!

#### Anonymous Registration
While impeded by several limitations, "anonymous" accounts are integral to TETR.IO's original concept of being "about as easy to join as a standard .IO game". They're also normally exempt from [the alt policy](https://tetr.io/about/rules/#ap), so you could have an secondary anonymous account as a registered user for controller play, for instance. All you need to make one is a *single* click on the JOIN button, if you don't mind having a non-descriptive username. Anonymous accounts *can* have customized usernames however, provided the username isn't already used by a registered account:

![](https://cdn.discordapp.com/attachments/673303546564968566/897051673556582420/registeranon.png)

1. Simply enter a username(1.1) into the prompt you see while not logged into <https://tetr.io/>(1), then click JOIN(1.2).
2. **If the username you chose is already in use,** you'll be prompted for whoever owns that account's password(2). Please proceed to back out of this login attempt(2.1).
3. If the chosen username is free, simply click STAY ANONYMOUS to keep the username in an anonymous state(3)!

### Profile Pictures
Registered TETR.IO user accounts may set their profile pictures for free from the relevant account settings category. The attached video shows you how to access this category, available from the ingame CONFIG option: 

https://user-images.githubusercontent.com/64891705/153128669-9fee4e10-694d-4d12-b4f0-b79e13022538.mp4

#### My Profile Picture Isn't NSFW!
TETR.IO profile picture and banner uploads are automatically scrutinized, in accordance with [rule 8](https://tetr.io/about/rules/#r8/), by an open source library, which in turn is powered by machine learning. The specific names of these projects are [nsfwjs](https://github.com/infinitered/nsfwjs) and [tensorflow](https://github.com/tensorflow/tensorflow), both of which are listed at the very top of [TETR.IO's open source acknowledgements](https://tetr.io/about/acknowledgements/). This means, at times, the automated detection process can incur a false-positive and deny you your rights to upload your otherwise safe for work imagery. There are ways around this system, but to disclose them here would be to make that information more accessible to bad actors. **Just try another image.**
Also see(from https://nsfwjs.com/):
> Humans are amazing at visual identification. NSFW tries to error more on the side of things being dirty than clean. It's part of what makes failures on NSFW JS entertaining as well as practical.

*(although do note if you decide to use the interactive checker included in this site, it may be several more revisions up-to-date compared to TETR.IO's checking)*

### Reporting a TETR.IO User
If you would like to report any TETR.IO user for breaking [the TETR.IO Community Rules](https://tetr.io/about/rules/), please use the ingame reporting systems instead of, say, public Discord channels!

As a registered user, simply click on a suspicious, rude, or otherwise problematic user's username or usercard, or, type said user's username into the ingame TETRA CHANNEL's search bar, accessible by clicking the *third* menu option, to access their "profile card". Once this card is open, simply click this arrow, and then click this report icon to begin the guided process of including details. If you report while in a room, chat logs will be automatically included. 

![](https://cdn.discordapp.com/attachments/813901028394795078/894379053367304222/unknown.png)

## Custom Assets
Looking to add your own backgrounds/skins to the game? Here's how to do it!

### Built-in Backgrounds
**Q:** How do I set a custom background?

**A:** Assuming you have a local file on your computer you'd like to use, just upload that file to **[catbox.moe](https://catbox.moe/)**. As of writing, it's free for use and simply works with TETR.IO's CORS header-requirements. 

#### Troubleshooting
If your image is already hosted on the net*(Catbox included)*, and you have a *(nonfunctional ingame)* link to use with TETR.IO's ingame background option, consider debugging that link with [this interactive checker](https://you.have.fail/ed/at/tetrio/backgrounds/).
If this site is showing that the link *should work*, please proceed to hard-reload the game with **CTRL+F5** *(yes, even on the desktop client)*. After this point, navigate into a SOLO 40 LINES match to confirm the background loading.

![](https://files.catbox.moe/65j4a2.png)

### Custom Skins
**Q:** Where do you get custom skins from?

**A:** Custom blockskins are generally discovered through the
* [you.have.fail/ed/at/tetrioplus](https://you.have.fail/ed/at/tetrioplus/) repository of skins
* [Curated gallery on Tenchi's site](https://tetrio.team2xh.net/?t=skins)
* [Jstris Customization Database](https://docs.google.com/spreadsheets/d/1xO8DTORacMmSJAQicpJscob7WUkOVuaNH0wzkR_X194/edit#gid=1212216734)
* As all outlined in [this wiki page dedicated to finding content](https://gitlab.com/UniQMG/tetrio-plus/-/wikis/finding-content)

You'll want to load these with the third party TETR.IO PLUS addon, exclusive to [the TETR.IO Desktop app](https://tetr.io/about/desktop/) or the Firefox web browser.

TETR.IO PLUS's project page, as well as **downloads for the modification**, may be found [here](https://gitlab.com/UniQMG/tetrio-plus/-/wikis/home "TETR.IO PLUS's GitLab repository's wiki").

## Stock Assets
Interested in getting a copy of TETR.IO's default assets? Here's where you get that!

### Music

*TETR.IO's* soundtrack is currently entirely provided by various musicians under the royalty free [*HURT RECORD* label](<https://www.hurtrecord.com/>) -- that is to say, each soundtrack *should* be stream-safe, provided you show the onscreen watermark centered near the bottom, displaying the currently playing 
song during the very start of gameplay. *Refer to [HURT RECORD's terms of service](https://www.hurtrecord.com/about/terms.html) for specific terms of use.*

Interested in listening to or downloading the soundtrack for personal use? There's [a YouTube mirror here](https://www.youtube.com/playlist?list=PLaFmyK0hSlVD_a98eL1BcGMOTblz8kQ0h) as well as [an up-to-date Google Sheets list here](https://docs.google.com/spreadsheets/d/1R_tpfLo_qUfNG2vQG3uqQ5fbjT01VefZVgB7RH2lOzM/edit), *both provided by EricICX.*

### Fonts
Here's a list of all of TETR.IO's fonts, as well as where you can download them and install them. Just right click these files in the File Explorer to do that.
* HUN-din: https://tetr.io/res/font/hun2.ttf?v=9
* ProFontWindows: https://tetr.io/res/font/pfw.ttf
* Config: https://tetr.io/res/font/cr.ttf: 
* Franklin Gothic already comes with Windows, though you're specifically looking for Franklin Gothic Medium

![](https://cdn.discordapp.com/attachments/674421736162197515/914184675071770664/unknown.png)

### Sound Effects
All of TETR.IO's sound effects are stored in a single "sound effect atlas" found [here](https://tetr.io/sfx/tetrio.ogg). There's an issue with this file though; all sound effects are split only by time and not by file names, so it's likely this file isn't the one you want. If you would like a copy of all of the TETR.IO sounds split up, *albeit with an ever so slightly lower quality,* please download [this `.zip` file](https://cdn.discordapp.com/attachments/673303546564968566/919778936475508776/tetrio-sound-effects.zip).

# Troubleshooting
This section goes over some common technical help people need for TETR.IO.

## Configuration
Sometimes you're just trying to [squeeze some more optimization out of TETR.IO](https://tetr.io/about/performance/ "TETR.IO's own PERFORMANCE TIPS guide"), or you're trying to use specialized control settings and you're not sure how it all works. This section here aims to help you!

### TETR.IO->Discord Account Linking
If you're interested in linking your Discord account to your TETR.IO account, navigate to CONFIG > ACCOUNT > CONNECTIONS, as detailed in this video: 

https://user-images.githubusercontent.com/64891705/153129007-acd4ffbe-5695-414f-ac53-032eb6e827f1.mp4

This link is currently used to grant the "Supporter" role to TETR.IO supporters, and to provide account verification for [the Character System playtester application form](https://insider-applications.osk.sh/). If you have recently purchased or been gifted supporter, you shouldn't have to wait too long before the role is automatically given to you, so long as the *@TETR.IO* bot is online. If you're having trouble linking your account, and are using TETR.IO Desktop, try linking from the website version instead, as this is less prone to error.

### Controllers
TETR.IO includes full controller support, *even commanding dynamic vibrations for different actions,* be it from your modern browser, or from [the official TETR.IO Desktop client](https://tetr.io/about/desktop/). Just connect your controller of choice and bind it manually in the ingame config:

https://user-images.githubusercontent.com/64891705/153129098-18b408bd-3533-42c3-af68-08507e51bed8.mp4

If your controller isn't working, here's a couple of different pointers to direct your attention towards:
* First off, ensure any D/XInput redirection isn't active. **This includes software like Steam or JoyToKey.**
* Ensure the controller you're attempting to use is **the only controller connected.** TETR.IO only accepts input from so-called "port one", though, there are plans to remedy this issue. If you had other controllers plugged in, a **restart** of the pc may be required.

If neither of these troubleshooting steps work, here's some specialized software for specific controllers:
* **PS4/PS5's DualShock** lineup: use [DS4Windows](https://github.com/Ryochan7/DS4Windows/releases/tag/v3.0.18)
* **Nintendo Switch's Joy-Con or Pro Controller** controllers: use [BetterJoy's "ShowAsXInput" function](https://github.com/Davidobot/BetterJoy/releases)

## TETR.IO Desktop Specific Troubleshooting
*TETR.IO DESKTOP IS MULTIPLE ORDERS OF MAGNITUDE FASTER THAN THE BROWSER!*
*enjoy uncapped framerates, faster startup, discord integration and more with [the **official** desktop client](https://tetr.io/about/desktop/)!*
\- Ingame banner ad, 2021

#### Dedicated Graphics
Are you using a laptop and getting poor performance with TETR.IO Desktop or browsers? If so, you'll want to ensure Windows is using your "dedicated" graphics card, as opposed to the less performant, yet more power efficient "integrated" graphics card Windows is likely selecting for you. You can override this autoselection by following this lengthy image guide:

![](https://cdn.discordapp.com/attachments/673305614318960671/851893786707230720/unknown.png)

* If you use TETR.IO Desktop, then you will find the executable in `%localappdata%\\Programs\\tetrio-desktop\\resources`
* If you use Chrome, you may find it in `%programfiles%\\Google\\Chrome\\Application\\chrome.exe`, `%programfiles(x86)%\\Google\\Chrome\\Application\\chrome.exe`, or `%localappdata%\\Google\\Chrome\\Application\\chrome.exe`
* And, if you're a Firefox kinda guy, then you will find Firefox's executable in `%programfiles(x86)%\\Mozilla Firefox\\` or `%programfiles%\\Mozilla Firefox\\`, depending on which architecture (32 or 64 bits respectively) your computer currently has installed

#### Broken Installer
Is your TETR.IO Desktop installation getting stuck? Here's a workaround:
You can use a *good* archiving program, such as 7zip(<https://www.7-zip.org/download.html>), to manually extract the game's contents for a much more manual installation for now. Here's a quick video guide(really, just open the `.exe` as a compressed folder and drag stuff out!): 

https://user-images.githubusercontent.com/64891705/153129140-d0398a14-c584-4226-b125-92ff46dcb9b0.mp4

#### Installation Locations
If you use TETR.IO Desktop, then you will find all installed files in the following folders: Use `Windows+R` and paste the following paths into the **r**un dialog that opens
* `%localappdata%\\Programs\\tetrio-desktop`
(The `.exe`cutable and `Resources` folder is found here)
* `%localappdata%\\tetrio-desktop-updater`
(Contains a single `.exe`cutable, which is a copy of the original TETR.IO Desktop installer you installed your current version of TETR.IO Desktop with. Run this file to clear any modifications you may have on the game)
* `%appdata%\\TETR.IO`
(Contains one empty folder: "logs")
* `%appdata%\\tetrio-desktop`
(Contains Electron related browser files. Two such examples: `Cache` and `Local Storage`)

## Replays
Loading replays is super easy, if not slightly obscure. It's asked so often I made this dedicated section to it, so don't fret if you're about to go "that's so simple!"

To view a locally saved replay, simply drag and drop the file from your file manager of choice into TETR.IO. If TETR.IO fails to load the replay, please ensure the replay is correctly named, specifically: 
* for solo replays of any sort, use the `.ttr` file extension
* for multiplayer replays of any sort, use the `.ttrm` file extension
* for solo custom game setting presets, use the `.ttp` file extension
* for TETR.IO config exports, use the `.ttc` file extension.

https://user-images.githubusercontent.com/64891705/153129180-a8ea5a31-0eee-428d-b920-e20173ae619b.mp4

If you load a `.ttrm` file, simply click on the individual rounds to watch that round's replay.
### Online Custom Room Replays
Replays taken in this context rely on some unconventional requirements, so don't blame yourself if that ever-so-required "DOWNLOAD REPLAY" button doesn't show up in here. Here's some requirements off the bat:
* The room **must** be a two player match, one versus one.
* Your client, not theirs, *should* be using LOW graphics or higher.
* If using MINIMAL, [the "SHOW DUELS SIDE BY SIDE" option **must** be enabled.](https://tetr.io/about/patchnotes/#chlog_5_2_0)
* You **must** persist from the start of the match, even in a FT5 (example) game, to the end of the match.
* Of course, you **must** download the replay from the results screen. There'll be a small button to the right, under the 2nd player's spot in the list.

## Mobile Support
First off, we have to break some news. [TETR.IO will never officially support mobile devices](https://discord.com/channels/673303546107658242/673305735811170305/901428890025738280)

That being said, there are still some ways to **play TETR.IO on phone**! Here's one quick rule, though: it **cannot be any iOS-based Apple device.** This is **absolute**, TETR.IO simply [will not load under WebKit](https://github.com/tetrio/issues/issues/425). Otherwise, you're welcome to try with any android device, but compatibility is *not* guaranteed as these are unsupported platforms!

To load TETR.IO on mobile, just visit <https://tetr.io/> on your mobile browser of choice. *That's it!* The real problem arises when you attempt to *control the game,* so there's a couple of different attacks you can use. The first would be simply connecting any conventional controller through bluetooth or usb, and binding that controller in TETR.IO's config natively.

The second workaround involves using what's known as a "bookmarklet", which is basically JavaScript code you run from a bookmark, to create **onscreen touch controls**. A specialized site to generate these bookmarklets may be found [here](https://you.have.fail/ed/at/tetrio/touchcontrols/). There's included instructions in this site once you've defined your controls.

# Mechanics
This section goes over some of the less understood mechanics surrounding TETR.IO.

## TETRA LEAGUE
TETRA LEAGUE is TETR.IO's premier matchmaking system featured for free for all registered accounts above level 10. While gameplay is very straightforward, 1v1 against another player of similar skill, the exact mechanics behind what the various mechanical values are and how the system itself works are often pondered.
*also see:*
* Tenchi's FAQ on 
1. [how the game decides what rank you are](https://tetrio.team2xh.net/?t=faq#decide-rank)
2. [being unranked after playing ten placement matches](https://tetrio.team2xh.net/?t=faq#placement)
3. [matchmaking with players far from your TR](https://tetrio.team2xh.net/?t=faq#rank-match)
4. [inconsistent ranks](https://tetrio.team2xh.net/?t=faq#inconsistent-ranks)
and likely many more
* [The Tetris Wiki on the TETRA LEAGUE](https://tetris.wiki/TETR.IO#TETRA_LEAGUE)

### Rating Deviation
RD is the number *after* the **±** symbol in your Glicko rating value. "RD" stands for **R**ating **D**eviation. It is a measurement of "How uncertain the Glicko-2 system is of your rating. Lower is better." (according to ingame hover text)

RD *generally* goes down after playing a match. It is possible to *gain* RD after a match, however. RD limits itself to a value of "60", according to osk, however, some players have  even attained 58 RD. The upper limit of RD is 349, after which, RD will be unable to go any further.

RD accumulates at a static rate of "1 RD per day, after a week of inactivity." You can tell whether or not your RD is currently "decaying" by navigating to your TETRA CHANNEL Userpage, found at `https://ch.tetr.io/u/your-username-here` and viewing the Glicko number, looking for an arrow which points in this direction: ↗️

### Rank Cutoffs
Interested in seeing the TETR.IO rank requirements? You may attain this information from [Tenchi's dynamic "TETR.IO STATS" project](https://tetrio.team2xh.net/?t=ranks), however, do note rank cutoffs are very volatile, and that this site only updates at a rate of once per every 6 hours, so this site does **not** host up-to-date or official information!

For some aforementioned up-to-date official information, feel free to visit your TETRA CHANNEL userpage found at `https://ch.tetr.io/u/your-username-here` and inspect the TETRA LEAGUE section. While only vaguely stated, and only shown if ranked, a "progress bar" will be shown below your stats, indicating your global placement, the placement required to reach the next rank, and the placement required to *keep your current rank.*

## Handling
Handling controls how your pieces interact with your sustained input to any of the movement keys. They have a dedicated section in the titular HANDLING section of the ingame CONFIG. Below are some short descriptions of these values.
*also see:*
* [25Pi25's YouTube video](https://www.youtube.com/watch?v=rKQZdRu6_g0 "How to properly set your TETR.IO Handling!") summarizing how to set your handling.
* [This instinctual `.gif` file](https://cdn.discordapp.com/attachments/813901028394795078/871859207605985300/DAS_and_ARR.gif) everyone keeps sharing to which I cannot attribute to anyone at this point.

### Auto Repeat Rate
**[A]**uto **[R]**epeat **[R]**ate(lower is faster: 0 is instantaneous): This slider controls how quickly pieces move around while holding the left or right movement keys. It's well known that an "optimal" ARR is 0: when ARR is this value, pieces teleport instantly upon DAS charge, allowing for extremely fast play. Good [finesse](https://tetrio.team2xh.net/?t=faq#finesse "Tenchi's FAQ on finesse") is a must-have if using this handling, however!

### Delayed Auto Shift
**[D]**elayed **[A]**uto **[S]**hift(lower is faster): This slider controls how long you hold the left or right movement keys before engaging ARR. To put it simply: 
* DAS is how long you hold L/R before the piece goes brrrr
* ARR is how *quickly* the piece goes brrrr. 

Optimal DAS values largely differ from player to player, so experiment around with different ones! *(hint: you may test your current handling settings from the TEST button in the top right of the HANDLING section)*

### ﻿DAS Cut Delay
**﻿[D]﻿**AS **﻿[C]﻿**ut **﻿[D]﻿**elay(higher is slower: 0 disables the system): An experimental and complicated handling setting, DAS Cut Delay hasn't seen much use in professional play. DAS Cut Delay introduces a set of pauses to active DAS, every time one of the two following actions occur:
1. A piece is rotated: 

https://user-images.githubusercontent.com/64891705/153129233-0d06d8c6-1965-4b86-981c-251031bad08c.mp4

2. A piece is spawned: 

https://user-images.githubusercontent.com/64891705/153129261-d556937d-910c-4b80-b12d-7622f5ae7049.mp4

If either of these actions occur, **﻿DAS is "paused"﻿**, or "cut" for the amount of frames DCD is configured to. It primarily targets 0ARR play, and aims to make certain finesse moves possible while keeping DAS charged, as well as reducing possible misdrops. 
[➔ A common value for it would be around 1 or 2 frames.](https://tetr.io/about/patchnotes/#chlog_5_0_0﻿)

### Soft Drop Factor
**[S]**oft **[D]**rop **[F]**actor(higher is faster: ♾️ is instantaneous): This slider controlshow quickly your piece will soft drop, given you are holding the soft drop key. It doesn't necessarily multiply current gravity, as you can still soft drop in zero gravity.(0 times anything, even infinity, equals 0)
An optimal value for this would be ♾️, as stacks that require partial soft drops to tuck pieces in is just *not a good stack.* If this functionality is a dealbreaker for you, limiting yourself to 20X or lower, then you have bigger issues to worry about.

#### Sonic Drop
To execute a "hard drop without placing the piece", such as those extremely fast T-Spins, turn this slider in the CONFIG to ♾️! Then, use your soft drop key as normal: the piece will rocket down to the bottom instantly now!

![](https://cdn.discordapp.com/attachments/673303546564968566/897711015981113404/unknown.png)

## Super Rotation System
"SRS", or, as this anagram expands to, "**[S]**uper **[R]**otation **[S]**ystem", is the driving force behind how the game handles rotations that intersect the stack. This system has some seemingly inconsistent and unconventional behaviors, especially for certain tucks, so here's some illustrations on such spins.
*also see:*
* The Tetris Wiki on
1. [TETR.IO's 180 kicks](https://tetris.wiki/TETR.IO#180_Kicks)
2. [SRS+](https://tetris.wiki/TETR.IO#SRS.2B)
3. [SRS in general](https://tetris.wiki/Super_Rotation_System)
* [The Hard Drop Wiki on SRS](https://harddrop.com/wiki/SRS)

## ZS Spins
Z and S tucks can be confusing to new players, since they rely on impulsively developed rotation systems which carry somewhat unconventional definitions of symmetry; this system, known as SRS, is likely why you're failing to execute successful Z or S spins.

**To execute a wall-less Z spin**, starting from the spawn position, press the **counter clockwise** rotation key, then soft drop and press the **counter clockwise** rotation key once more: (here's an easy way to remember this, assuming you have the default guideline controls: press the **"z"** key twice to **z** spin)
If there is any walls spanning across both sides, as shown in the second half of this gif, simply reverse the rotations and *press the neutral **clockwise** rotation key twice*, instead.

**To execute a wall-less S spin**, starting from the spawn position, press the **clockwise** rotation key, soft drop, and press the **clockwise** rotation key once again: (many new players default to *only* rotating clockwise, as the only feasible key to rotate is the up arrow key, next to all other movement keys. This is why S spins may appear "easier" to a new user.)
Assuming two walls exists, such as the one shown in the second half of this gif, simply reverse the rotations and *press the opposite **counter clockwise** rotation key twice*, instead.

![](https://files.catbox.moe/yau2oj.gif)

![](https://files.catbox.moe/cvoofj.gif)

## /set Command Usage
The ingame `/set` command has plenty of valid use case scenarios, but at the end of the day, it still is what you make out of it. That said, here's a bunch of reference to make the most out of this command, without straining your hands typing a preset out manually!
### Automatic Solutions:
First, we'll go over automated solutions, from least intrusive to most:
* [Zudo](https://kagar.in/ "Zudo's homepage")'s [Autohost project](https://gitlab.com/Zudo/autohost/ "Source repository -- unrecommended for casual users") includes several commands for room presets. Please refer to this [ingame bot](https://ch.tetr.io/u/autohost)'s [documentation to get started](https://gitlab.com/Zudo/autohost/-/wikis/Get-Started). Once you have your room configured the way you like, use the command `!savepreset <name>`  to save it as a preset. You can then load the settings in the future with `!preset <name>`, or delete them with `!delpreset <name>`. There are a handful of built-in presets that you can view by simply running `!preset`.
* [Zutatensuppe](https://github.com/Zutatensuppe "Zutatensuppe's Github profile")'s custom JavaScript bookmarklet: a quick how-to guide is included both [here](https://github.com/Zutatensuppe/tetrio-preset) and [here](https://www.reddit.com/r/Tetris/comments/r3o5w3/preset_tool_for_custom_multiplayer_room_settings/), alongside source code for the bookmarklet itself.
* [aznguy.mp4](http://aznguy.com/ "aznguy.mp4's homepage")'s console solution: paste the following code into your browser's devtools, accessible by using `F12` in most scenarios(including TETR.IO desktop), to dump your current room's properties into the console. This is a bit of a blunt solution, and it will include lots of extra definitions that would otherwise be assumed(as default settings), so only use this as an inbetween while creating `/set` presets from scratch!
```js
var configs = document.getElementsByClassName("room_config_item")
var cmd = '/set '

for(let i = 0; i<configs.length; i++) {
    var v = configs[i]
    var datIdx = v.getAttribute('data-index')
    if(datIdx&&datIdx.match(/.{4}./)) {
        cmd+=${datIdx}=${v.value=='on'?v.checked+0:v.value};\

    }
}
console.log(cmd)
```

### Manual reference
Here's some pointers if you'd like to avoid the automated solutions and instead create your own:
* [aznguy.mp4](http://aznguy.com/ "aznguy.mp4's homepage")'s list of `/set` attributes: as pinned in #tetrio on the official TETR.IO Discord server, it's also available [on Tenchi's FAQ](https://tetrio.team2xh.net/?t=faq#commands).
* [ZaptorZap](https://github.com/ZaptorZap/tetriofaq "ZaptorZap's github profile")'s `.txt` file of complete `/set` presets: it's always nice to learn by example, so here's a five for one deal! Download it [here](https://cdn.discordapp.com/attachments/763146093655359488/917684858099232798/tetrio_multiplayer_rule_presets.txt) (if you have suggestions for new presets, feel free to direct message ZaptorZap#0405 about them!)
As well as these resources, here's some more specific advice: note that `/set` presets **are bound by TETR.IO's 513 character chat limit**. If a `/set` preset calls for more than this limit, either split it up into two halves or try to truncate defaults settings out.

## In general
### Fire
The "fire bar" effect triggers when you build up enough "fire points" to cause it. You can accumulate fire points by clearing a large spike, keeping a large back to back chain up, or, by koing people (koing people is the most effective way to build fire points.). You also steal fire points from the people you've ko'd; you can see how filled your ko'd user's fire bar was by looking at the little percentage sign next to their name. This whole system is entirely cosmetic, and can be disabled from the settings.

### Character System
First revealed in mid-November 2020 and developed since, the prototyped "Character System" is planned to be TETR.IO's "Beta" feature.
* For Character System conversation, please check out the *#Official Character System Thread* in [the TETR.IO Discord server](https://l.tetr.io/discord). It forks off from #lobby.
* Otherwise, [this supplementary FAQ](https://docs.google.com/document/d/1gRX1lorozF2NeJqgdkGyqrqkD-dD0wjYRimNQHGPj0w/edit) created by [TwoQuantumBits](https://2qb.carrd.co/ "TwoQuantumBits's webpage") may be of use.
* The above links to [this in-depth up-to-date documentation](https://docs.google.com/spreadsheets/d/1LjoLa3cXIp9vhmNoadk2PWRyFHFnYlOfnavs3Ga2gis/edit#gid=353436719) created by [SigmaZero](https://www.youtube.com/channel/UC9Qal7IJul-6iC3YvYZ4Q1A "SigmaZero's linked YouTube page") on the system.
* If you're still skeptical to the validity of these pages, [here's documentation by osk himself](https://characters.osk.sh/). **Please note that this documentation is wildly out of date!**

### Badges
Badges are simple graphics placed on a specific and registered user's userpage or player card signifying that user's achievements. If you're looking for your first badge, go for [the "Secret Grade" badge](https://tetris.wiki/TETR.IO_Badges#Secret_Grade)! You can attain this badge with the solo custom game mode, with gravity disabled. If you take your time, you'll likely get it first try!

# Glossary of terms
The TETR.IO community, like any community, has several "inside phrases" other new users may not be informed of. The list that follows is likely incomplete, but it covers the most common terms you might not otherwise understand.
*Also see:*
* [Tenchi's Glossary of most anagrams](https://tetrio.team2xh.net/?t=faq#glossary)
* [The Tetris Wiki's universal, if not self-consiously dated, glossary](https://tetris.wiki/Glossary)
* [The Tetris Wiki on TETR.IO Trivia](https://tetris.wiki/TETR.IO#Trivia)
* [The Hard Drop Wiki's glossary](https://harddrop.com/wiki/Glossary)
* [four.lol](https://four.lol/)'s search bar (for example, terms such as `tki`, `mko`, `tst`, `dpc`, and even `sd-pc` are valid searches in this site)
* TETR.IO itself contains lots of hover text, **especially** in the CONFIG and [the TETRA CHANNEL](https://ch.tetr.io/)'s various pages

## "Plonker"
"Plonking" refers to the act of **intentionally tanking garbage lines**, sometimes *noticeably slowing down or stalling to do so*, in order to send reverse-spikes fueled by an enemy's garbage. This garbage abuse is made possible thanks to TETR.IO's "change-on-attack" garbage generation, guaranteeing each line from an individual attack generates in a singular, consistent column, as decided by RNG. A "plonker" may be vaguely defined by a given user's high VS:PPS ratio.(one staple of VS Score involves its factoring of garbage lines cleared - this is why VS score is considered over raw APM) In effect, a plonker is the opposite of a strider: **plonkers play matches slowly, pay close attention to incoming garbage, and keep a low field.**

## "Strider"
Originally a Jstris meme requiring an incredibly specific 40 LINES sprint time (one under 26.179 seconds), your inability to "be a pepegon", a versus skill which must be disproportionate to your sprint time, the ability to "hit the stride", and optionally the display of the 🇮🇲 flag on your profile;
*a strider in today's terminology is used to vaguely define players based on their high PPS:APM ratio.* To shorten this down a little: **a strider typically plays fast and inefficient,** essentially existing only in delayless games such as TETR.IO. "stride" and "strider" are normally used interchangeably, with "striding" usually being the temporal verb to describe any player's gameplay for a given match/round/replay as fast and inefficient.

## Zen Levels
ZEN levels are usually accompanied by little symbols around TETR.IO. These symbols represent the numerical ZEN level in modified roman numerals. Here's a graphic detailing them all:

![](https://cdn.discordapp.com/attachments/673303546564968566/930368624286375956/unknown.png) 

Once the maximum numeral has been attained, which is unlikely to happen as [the closest player](https://ch.tetr.io/u/blb) is still 490,605 levels off of that goal, it will loop for infinity.
