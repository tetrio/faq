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
Interested in seeing the TETR.IO rank requirements? You may attain this information from [Tenchi's dynamic "TETR.IO STATS" project](https://tetrio.team2xh.net/?t=ranks), however, do note rank cutoffs are very volatile, and that this site only updates at a rate of once per every 6 hours, so this site does **__not__** host up-to-date or official information!

For some aforementioned up-to-date official information, feel free to visit your TETRA CHANNEL userpage found at `https://ch.tetr.io/u/your-username-here` and inspect the TETRA LEAGUE section. While only vaguely stated, and only shown if ranked, a "progress bar" will be shown below your stats, indicating your global placement, the placement required to reach the next rank, and the placement required to *keep your current rank.*

## Handling
Handling controls how your pieces interact with your sustained input to any of the movement keys. They have a dedicated section in the titular HANDLING section of the ingame CONFIG. Below are some short descriptions of these values.
*also see:*
* [25Pi25's YouTube video](https://www.youtube.com/watch?v=rKQZdRu6_g0 "How to properly set your TETR.IO Handling!") summarizing how to set your handling.
* [This instinctual `.gif` file](https://cdn.discordapp.com/attachments/813901028394795078/871859207605985300/DAS_and_ARR.gif) everyone keeps sharing to which I cannot attribute to anyone at this point.

### Auto Repeat Rate
__[A]__uto __[R]__epeat __[R]__ate(lower is faster: 0 is instantaneous): This slider controls how quickly pieces move around while holding the left or right movement keys. It's well known that an "optimal" ARR is 0: when ARR is this value, pieces teleport instantly upon DAS charge, allowing for extremely fast play. Good [finesse](https://tetrio.team2xh.net/?t=faq#finesse "Tenchi's FAQ on finesse") is a must-have if using this handling, however!

### Delayed Auto Shift
__[D]__elayed __[A]__uto __[S]__hift(lower is faster): This slider controls how long you hold the left or right movement keys before engaging ARR. To put it simply: 
* DAS is how long you hold L/R before the piece goes brrrr
* ARR is how *quickly* the piece goes brrrr. 

Optimal DAS values largely differ from player to player, so experiment around with different ones! *(hint: you may test your current handling settings from the TEST button in the top right of the HANDLING section)*

### ﻿DAS Cut Delay
__﻿[D]﻿__AS __﻿[C]﻿__ut __﻿[D]﻿__elay(higher is slower: 0 disables the system): An experimental and complicated handling setting, DAS Cut Delay hasn't seen much use in professional play. DAS Cut Delay introduces a set of pauses to active DAS, every time one of the two following actions occur:
1. A piece is rotated: 

https://cdn.discordapp.com/attachments/673303546564968566/775479818942021672/2020-11-09_22-59-41.mp4

2. A piece is spawned: 

https://cdn.discordapp.com/attachments/673303546564968566/775480550471237702/2020-11-09_23-02-29.mp4

If either of these actions occur, **﻿DAS is "paused"﻿**, or "cut" for the amount of frames DCD is configured to. It primarily targets 0ARR play, and aims to make certain finesse moves possible while keeping DAS charged, as well as reducing possible misdrops. 
[➔ A common value for it would be around 1 or 2 frames.](https://tetr.io/about/patchnotes/#chlog_5_0_0﻿)

### Soft Drop Factor
__[S]__oft __[D]__rop __[F]__actor(higher is faster: ♾️ is instantaneous): This slider controlshow quickly your piece will soft drop, given you are holding the soft drop key. It doesn't necessarily multiply current gravity, as you can still soft drop in zero gravity.(0 times anything, even infinity, equals 0)
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

**To execute a wall-less Z spin**, starting from the spawn position, press the __counter clockwise__ rotation key, then soft drop and press the __counter clockwise__ rotation key once more: (here's an easy way to remember this, assuming you have the default guideline controls: press the **"z"** key twice to **z** spin)
If there is any walls spanning across both sides, as shown in the second half of this gif, simply reverse the rotations and *press the neutral __clockwise__ rotation key twice*, instead.

**To execute a wall-less S spin**, starting from the spawn position, press the __clockwise__ rotation key, soft drop, and press the __clockwise__ rotation key once again: (many new players default to *only* rotating clockwise, as the only feasible key to rotate is the up arrow key, next to all other movement keys. This is why S spins may appear "easier" to a new user.)
Assuming two walls exists, such as the one shown in the second half of this gif, simply reverse the rotations and *press the opposite __counter clockwise__ rotation key twice*, instead.

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
