# Soft Dorothy Software — Early Shareware Projects
Disk images (intended for emulators) containing code and tools for building the early **Soft Dorothy Software** shareware games.

<p align="center">
<img width="330" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/295e289562f222900652959fb653b5ffed056fe2/Images/SoftDorothy.png">
</p>

My desire was to recover the sources to my old **Soft Dorothy Software** games as well as the old build environment (THINK C, THINK Pascal, ResEdit) and create disk images suitable for the current early Macintosh emulators. The disk images here (zipped to save space) can be downloaded and you should be able to mount them in <a href="https://basilisk.cebix.net">Basilisk II</a>, <a href="https://sheepshaver.cebix.net">Sheepshaver</a> or <a href="https://www.gryphel.com/c/minivmac/">MiniVMac</a>. 

Some of the shareware games went through a number of revisions but I have made no effort to capture each here. I feel fortunate to have been able to recover *any* of the source files and so I was not too fussy as to which version of a game is represented. Generally, changes between versions were minor. In fact these days I would only have bumped the "dot" of the release number (but what did I know back in then).

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothy-SharewareProjects/blob/cf7d91c8176f3082834a73b59d4ce29552055129/Images/PararenaDevDsk.jpg">
</p>

Running the games under emulators can reveal the lack of "throttling" in the game code. I know in MiniVMac you can dial the speed of the emulator down to represent the original hardware speed — and in that mode the games play just fine (or at least play just as they did back in the day).

Below, in order of release date, are the disk images included in this repository.

### Glider3Dev.dsk (Shareware version of Glider)

Unzip the file and then mount the `.dsk` with one of the emulators previously mentioned. The project, sources, resources and tools to build and compile **Glider** are all there.

The shareware version of **Glider** (**`BNDL identifier: sd01`**) was where it all began for **Soft Dorothy Software**. <a href="http://macintoshgarden.org/games/duane-blehms-source-code">Duane Blehm</a>, a programmer from Ulysses, Kansas who wrote a number of cute shareware games under the moniker, HomeTown Software (the logo a little scarecrow icon), was my obvious inspiration. Instead of going with DorothySoft (a play on MicroSoft) I flipped the word order. The risqué fairy that became the logo I had scanned from a book of public domain artwork. Maybe you've had fun with friends thinking up outrageous band names — Soft Dorothy Software and the topless fairy was the outrageous "company" that I came up with. I'm quite sure I thought no one would ever see it but me and a few friends.

The game, **Glider**, got a few things right and quite a bit wrong back in 1988 or whenever I wrote it (dates on files are now often meaningless as the files have moved between different file systems over the years). Maybe the whimsy of **Glider** resonated with some people. I think the art was of a kind with the Macintosh itself — somewhat skeuomorphic (before that had become a bad thing). I didn't deliberately set out to make a non-violent game but I was pleased that **Glider** did in fact avoid that common game trope.

<p align="center">
<img width="516" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/fafe3b30b41b040db55604eabc013fdcbec72f44/Images/Glider3Sprites.png">
</p>

It's hard now to enjoy playing the original shareware game when the commercial version (**Glider 4.0**) probably improved upon every aspect of it. I made many mistakes too for example allowing the player to choose between two types of paper airplanes with very different characteristics. It turned out to be impossible to create a challenging house for *both* paper glider types. It would take me a while but I would slowly come to learn the lesson that you're not always doing the user a favor giving them more options, more choices.

Nonetheless, this is where I really learned about how to create "off-screen bitmaps" and to do flicker-free animation on the Macintosh. And regardless of the mistakes made (and perhaps because there were so few games for the Macintosh in those days) when I finally dared upload **Glider** to one or two FTP sites, I was surprised to see it appear on its own at several other FTP sites. Surprised even more so to start seeing a trickle of letters (and sometimes shareware checks) arrive in the mail.

> Only older readers will remember the early internet before the World Wide Web came along. Using a command-line (text) interface, FTP (File Transfer Protocol) was the means by which you found, downloaded and otherwise shared files on the internet. More like BBS's than the modern Web, you came to know which university servers around the world (or even a few military sites) had shareware and freeware titles for the Macintosh.

Living in the "college ghetto" in Lawrence, Kansas at the time, just getting a single $10 check in the mail meant my girlfriend and I could get a Pizza Shuttle pizza and two large Cokes that Friday night. In time we were getting Pizza Shuttle about every Friday.

### GlyphaDev.dsk (Shareware, B&W version of Glypha)

This disk image contains everything to build and run the original, B&W game **Glypha**.

I wrote **Glypha** (**`BNDL identifier: sd08`**) as a kind of personal challenge. I wanted to take an existing video game that I was familiar with and see if I could write a kind of *tribute* to it on the Macintosh. I suspected that the **Glider** game I had written was to a degree designed around my abilities as a programmer. A tribute to an existing game would force me to rise to new challenges dictated by the game.

<p align="center">
<img width="435" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/bca7c4c76706cfc1202d6297be18ba22060f0f97/Images/GlyphaAbout.png">
</p>

I enjoyed coming up with original artwork for the game — perhaps in part inspired by Duane Blehm's <a href="https://archive.org/details/mac_Cairo_ShootOut">Cairo Shootout</a>. Playing **Glypha** again it feels very claustrophobic — cramming all those sprites into such a small 512 x 342 window. Of course I could have made the sprites smaller but they felt to me to be as small as I could make them and still have a reasonable amount of detail for the player to see.

> The early Mac OS used bundle identifiers (a 4-character code) to associate things like the icon for an application with the application itself. Bundle identifiers need to be unique from one another, so I began a pattern with **Glider** of using `sd__` where the last two places were digits that began with 01 for Glider (`sd01`) and were incremented for each game. In this way, the icon for **Glypha** (which used `sd08`) would not appear in the Macintosh Finder for **Glider**.

> If you're wondering why `sd02` through `sd07` are missing between **Glider** and **Glypha** it is because there were six titles that I began and ultimately shelved. Stay tuned and I will be creating a repository of some of the "Lost Games".

### StellaObscuraDev.dsk (Shareware version of Stella Obscura)

This disk image contains everything to build and run the shareware game, **Stella Obscura**.

Admittedly **Stella Obscura** (**`BNDL identifier: sd18`**) was an experiment, a novelty — not really a game anyone would want to play for more than perhaps a few minutes. I am not sure there was anything quite like it though. I wanted to try to create a 3D game that was actually, visually, in stereo. Lacking color on my Macintosh Plus, a red/cyan anaglyph game was not in the cards. A stereo pair, separate left and right images like the vintage stereographic images though might be possible. 

<p align="center">
<img width="513" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/723aa35e2b254e2277a172fbd5c47a681665bae5/Images/StellaViewerInstructions.png">
</p>

Your eyes naturally want to converge to look at a screen inches in front of them — the old stereoscopes had optics to make this easy. Lacking that, I came up with an odd-ball construction you could make out of a Saltine cracker box that provided some guidance for your eyes. A separating wall down the center of the box meant your left eye saw only the left image, your right eye the other.

### PararenaDev.dsk (Shareware version of Pararena)

A disk image containing the source and build environment to build the shareware game, **Pararena** (**`BNDL identifier: sd21`**).

It's obvious that the 1970's film, Rollerball, had an influence on the game, but that's not where it started. Instead it began as a demo I threw together where I wanted to simulate the physics of a number of balls rolling about in a parabolic dish. I am not sure if this was an extension of my playing around with ball collisions when I was considering a billiards computer game or if I was thinking about some kind of Marble Madness like game. Regardless, I wrote enough code to display a parabolic dish very much like the one in **Pararena**, but there were just balls rolling about, colliding, after having been given an initial random velocity and direction.

<p align="center">
<img width="600" src="https://github.com/EngineersNeedArt/SoftDorothy-SharewareProjects/blob/cf97f4e9f7a9f5dcb93dcbcd2590a911ebf91245/Images/PararenaTestDish.jpg">
</p>

It was cool enough in terms of the physics modeling, but could there be a fun game in it? You never know until you try. And when pondering what game I could make out of it, Rollerball did in fact come to mind.

What resulted was probably the most difficult to play game that I wrote. My understanding is that most people didn't enjoy it though. Sometimes in writing games you throw things at the wall and they just don't stick (but for perhaps a clutch of ardent fans).

### MacTuberlingDev.dsk (Shareware version of Mac Tuberling)

Another disk image containing the source and build environment to build the shareware game, **Mac Tuberling** ((**`BNDL identifier: sd28`**).

I'm not sure why I wrote this. Perhaps KidPix had come out and I was intrigued by its cuteness. In any event I deliberately made a young kids application that, like Mr. Potato Head, let the user drag mouth parts, eye parts, etc. onto a pixelated spud.

<p align="center">
<img width="514" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/6df87a584ab56870ec15840722fe7c5243b010b7/Images/MacTuberling.png">
</p>

It was fun to create the artwork for **Mac Tuberling** but ultimately a fairly simple app to write. I knew the Soft Dorothy logo was going to be an obstacle for parents and so, for this title only, opted for a graphic of the character Ozma from the *Wizard of Oz* series of books.

Playing with it now I guess the thing that makes me smile are the digitized sounds of a women saying things like "Nose" and "Spectacles" when the user clicks on and drags these items from the "parts palette". I must have picked up a MacRecorder about then and the woman's voice is clearly that of my girlfriend, Kim.

### GlyphaII.dsk (Shareware, color version of Glypha)

The project, sources and resource file for **Glypha II** (**`BNDL identifier: sD09`**). THINK Pascal and ResEdit are included on the disk image as well. As with the other files, `GlyphaII.dsk` needs to be unzipped and then mounted with one of the early Mac emulators listed earlier.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/5fb25ed444c855425479c3b8577312ed1c83052a/Images/GlyphaIIScreenshot.jpg">
</p>

Most of the files indicate a date of around May or June 1991. The fall of 1991 was when I believe I released the first commercial game, **Glider 4.0**, via Casady & Greene Inc. (C&G). C&G wanted a color game (of course) but I had only a B&W Macintosh Plus up until this point. They gave me an advance against future royalties that I used to buy a IIsi color Macintosh computer and a color display.

Even though I now had color computer I was still new to color programming. It seemed crazy to me that my first foray into color would also be my first commercial game. So in fact I took my shareware game, **Glypha**, and decided to port that to color before ever beginning on the commercial **Glider**. The rationale of course was that I could cut my teeth on a free app, "ship it" (post it to various FTP sites) and get feedback as to whether I was crashing anyone's computers while I began what would be **Glider 1.0** for C&G.

The good news was that **Glypha II** ran fine — as did **Glider 4.0** when it shipped later that year. Something I did not know then was the degree to which C&G would test **Glider 4.0** on all the hardware they had available before pressing thousands of floppy discs. I need not have ben as anxious as I was.

### Lastly

Last year, for fun, I rewrote **Glypha** again to run on the Steam Deck, modern Mac OS, Windows. I called it <a href="https://store.steampowered.com/app/2318420/Glypha_Vintage/">Glypha: Vintage</a>.

I have begun but not yet completed a follow-on to this repo, <a href="https://github.com/EngineersNeedArt/SoftDorothy-PublishedProjects">Soft Dorothy Software - Early Published Projects</a>.
