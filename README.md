# Soft Dorothy Software Projects
Disk images (intended for emulators) containing code and tools for building **Soft Dorothy Software** games.

<p align="center">
<img width="330" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/295e289562f222900652959fb653b5ffed056fe2/Images/SoftDorothy.png">
</p>

My desire was to recover the sources to my old **Soft Dorothy Software** games as well as the old build environment (THINK C, THINK Pascal, ResEdit) and create disk images suitable for the current early Macintosh emulators. The disk images here (zipped to save space) can be downloaded and you should be able to mount them in <a href="https://basilisk.cebix.net">Basilisk II</a>, <a href="https://sheepshaver.cebix.net">Sheepshaver</a> or <a href="https://www.gryphel.com/c/minivmac/">MiniVMac</a>. 

### Glider3Dev.dsk (Shareware version of Glider)

Unzip the file and then mount the `.dsk` with one of the emulators previously mentioned. The project, sources, resources and tools to build and compile Glider 3 are all there.

The shareware version of **Glider** (from 1.0 to 3.0, BNDL identifier: `sd01`) was where it all began for **Soft Dorothy Software**. <a href="http://macintoshgarden.org/games/duane-blehms-source-code">Duane Blehm</a>, a programmer from Ulysses, Kansas who wrote a number of cute shareware games under the moniker, HomeTown Software (the logo a little scarecrow icon), was my obvious inspiration. Instead of DorothySoft (maybe a kind of play on MicroSoft) I flipped the word order. The risqué fairy that became the logo I had scanned from a book of public domain artwork. Maybe you've had fun with friends thinking up outrageous band names — Soft Dorothy Software and the topless fairy was the outrageous "company" I came up with. I'm quite sure I thought no one would ever see it but me and a few friends.

The game, Glider, got a few things right and quite a bit wrong back in 1988 or whenever I wrote it (dates on files are now often meaningless as the files have moved between different file systems over the years). Maybe the whimsy of Glider scored with some people. I think the art was of a kind with the Macintosh itself — somewhat skeuomorphic before that had become a bad thing. I don't remember having set out to make a non-violent game but I admit I was somewhat proud of that.

<p align="center">
<img width="516" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/fafe3b30b41b040db55604eabc013fdcbec72f44/Images/Glider3Sprites.png">
</p>

It's hard now to enjoy playing the original shareware game with its minimal sounds, lazy animation. It was a mistake to have allowed the player to choose between two types of paper airplanes with such different characteristics. It turned out to be impossible to create a challenging house for both paper glider types. It would take me a while but I would slowly come to learn the lesson that you're not always doing the user a favor giving them more options, choices.

Nonetheless, this is where I really learned about how to create "off-screen bitmaps" and to do flicker free animation on the Macintosh. And regardless of the mistakes made, and perhaps because there were so few games for the Macintosh in those days, when I finally dared upload the game to one or two FTP sites, I was surprised to see it appear on its own at other FTP sites. Surprised even more so to start seeing a trickle of letters and sometimes checks arrive in the mail as shareware payment.

Living in the college ghetto in Lawrence, Kansas at the time, just getting a single $10 check in the mail meant my girlfriend and I could get a Pizza Shuttle pizza and two large Cokes that Friday night. In time we were getting Pizza Shuttle every week.

### GlyphaDev.dsk (Shareware, B&W version of Glypha)

This disk image contains everything to build and run the original, B&W game **Glypha**.

I wrote Glypha (BNDL identifier: `sd09`) as a kind of personal challenge. I wanted to take an existing video game that I was familiar with and see if I could write a kind of *tribute* to it on the Macintosh. I suspected that the Glider game I had written was to a degree designed around my abilities as a programmer. A tribute to an existing game would force me to rise to new challenges dictated by the game.

<p align="center">
<img width="435" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/bca7c4c76706cfc1202d6297be18ba22060f0f97/Images/GlyphaAbout.png">
</p>

I enjoyed coming up with original artwork for the game — perhaps in part inspired by Duane Blehm's <a href="https://archive.org/details/mac_Cairo_ShootOut">Cairo Shootout</a>. Playing it again it feels very claustrophobic — cramming all those sprites into such a small 512 x 342 window. Of course I could have made the sprites smaller but they felt to me to be as small as I could make them and still have a reasonable amount of detail for the player to see.

### StellaObscuraDev.dsk (Shareware version of Stella Obscura)

This disk image contains everything to build and run the shareware game, **Stella Obscura**.

Admittedly Stella Obscura (BNDL identifier: `sd18`) was an experiment, a novelty — not really a game anyone would want to play for more than perhaps a few minutes. I am not sure there was anything quite like it though. I wanted to try to create a 3D game that was actually, visually, in stereo. Lacking color on my Macintosh Plus, a red/cyan anaglyph game was not in the cards. A stereo pair, separate left and right images like the vintage stereographic images though might be possible. 

<p align="center">
<img width="513" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/723aa35e2b254e2277a172fbd5c47a681665bae5/Images/StellaViewerInstructions.png">
</p>

Your eyes naturally want to converge to look at a screen inches in front of them — the old stereoscopes had optics to make this easy. Lacking that, I came up with an odd-ball construction you could make out of a Saltine cracker box that provided some guidance for your eyes. A separating wall down the center of the box meant your left eye saw only the left image, your right eye the other.

### PararenaDev.dsk (Shareware version of Pararena)

A disk image containing the source and build environment to build the shareware game, **Pararena** (BNDL identifier: `sd18`).

It's obvious that the 1970's film, Rollerball, had an influence on the game, but that's not where it started. Instead it began as a demo I threw together where I wanted to simulate the physics of a number of balls rolling about in a parabolic dish. I am not sure if this was an extension of my playing around with ball collisions when I was considering a billiards computer game or if I was thinking about some kind of Marble Madness like game. Regardless, I wrote enough code to display a parabolic dish very much like the one in Pararena, but there were just balls rolling about, colliding, after having been given an initial random velocity and direction.

It was cool enough in terms of the physics modelling, but could there be a fun game in it? You never know until you try. And when pondering what game I could make out of it, Rollerball did in fact come to mind.

What resulted was probably the most difficult to play game that I wrote. My understanding is that most people didn't enjoy it though. Sometimes in writing games you throw things at the wall and they just don't stick (but for perhaps a could of ardent fans).

### MacTuberlingDev.dsk (Shareware version of Mac Tuberling)

Another disk image containing the source and build environment to build the shareware game, **Mac Tuberling** (BNDL identifier: `sd28`).

I'm not sure why I wrote this. Perhaps KidPix had come out and I was intrigued by its cuteness. In any event I deliberately made a young kids application that, like Mr. Potato Head, let the user drag mouth parts, eye parts, etc. onto a pixelated spud.

<p align="center">
<img width="514" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/6df87a584ab56870ec15840722fe7c5243b010b7/Images/MacTuberling.png">
</p>

It was fun to create the artwork but ultimately a fairly simple app to write. I knew the Soft Dorothy logo was going to be an obstacle for parents and so, for this title only, opted for a graphic of the character Ozma from the *Wizard of Oz* series of books.

Playing with it now I guess the thing that makes me smile are the digitized sounds of a women saying things like "Nose" and "Spectacles" when the user clicks on and drags these items from the "parts palette". I must have picked up a MacRecorder about then and the woman's voice is clearly that of my girlfriend, Kim.

### GlyphaII.dsk (Shareware, color version of Glypha)

The project, sources and resource file for **Glypha II** (BNDL identifier `sD09`). THINK Pascal and ResEdit are included on the disk image as well. As with the other files, GlyphaII.dsk needs to be unzipped and then mounted with one of the early Mac emulators listed earlier.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/5fb25ed444c855425479c3b8577312ed1c83052a/Images/GlyphaIIScreenshot.jpg">
</p>

Most of the files indicate a date of around May or June 1991. The fall of 1991 was when I believe I released the first commercial game, **Glider 4.0**, via Casady & Greene Inc. (C&G). C&G wanted a color game (of course) but I had only a B&W Macintosh Plus up until this point. They gave me an advance against future royalties that I used to buy a IIsi color Macintosh computer and a color display.

Even though I now had color computer I was still new to color programming. It seemed crazy to me that my first foray into color would also be my first commercial game. So in fact I took my shareware game, Glypha, and decided to port that to color before ever beginning on the commercial Glider. The rationale of course was that I could cut my teeth on a free app, "ship it" (post it to various FTP sites) and get feedback as to whether I was crashing anyone's computers while I began what would be Glider 4.0 for C&G.

The good news was that Glypha II ran fine — as did Glider 4.0 when it shipped later that year. Something I did not know then was the degree to which C&G would test Glider 4.0 on all the hardware they had available before pressing thousands of floppy discs. I need not have ben as anxious as I was.

Last year, for fun, I rewrote Glypha again to run on the Steam Deck, modern Mac OS, Windows. I called it <a href="https://store.steampowered.com/app/2318420/Glypha_Vintage/">Glypha: Vintage</a>.

### Glider4Dev.dsk (First commercial version of Glider)

**Glider 4.0** (BNDL identifier `GLID`) was the first game I had published commercially. I had seen a few games published by Casady & Greene, Inc. (C&G) and reached out to them to see if they were interested in Glider. I suggested I could write a commercial Glider to support color and that the game would have a "house" (the game levels) with some forty or so rooms (the shareware game had only ten or fifteen rooms as I recall). They agreed and so advanced me enough cash to buy a color Macintosh and a color display.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/f188aaed99fccf01c4140afe1641e17ed16a959e/Images/BasiliskIIScreenshot.jpg">
</p>

I believe I more or less finished Glider 4.0 around the beginning of the fall of 1991. That fall I was in my last year of an Education degree at the University of Kansas. I student taught that last year and I recall telling my high school students that I had a game coming out, ha ha.

The "houses" for Glider are like a collection of *levels*. I determined pretty quickly that creating a "level editor" for Glider would make it much easier for me to create the promised house of forty or more rooms. And so the creation of both **Glider 4.0** and a **House Editor** began more or less at the same time.

I could have kept the **House Editor** (BNDL identifier `GLed`) as an internal tool but I realized that if users could create and share their own house creations, it would add to the appeal to Glider. I think i was thinking about something similar to the Pinball Construction Set game.

I found out very quickly though that work on the House Editor in fact involved more work than Glider itself. It turned out that "idiot proofing" the editor required a lot of sanity checking and busy work. As an example, when a user adds a bouncing ball to a room, there is a Get Info dialog that allows you to edit various parameters of the ball such as the **Length of travel**. When a user entered a value I had to make sure it was not negative, not too large for the room. These kinds of sanity checks are all over in the code and required a lot of busy effort.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/e13d52bbfb8e2eb1e904a019a68b3ddd9c84a19a/Images/GliderEditorScreenshot.jpg">
</p>

Glider 4.0 went on to win a coveted MacWorld Game Hall of Fame award. I graduated with my Education degree but as a result of Glider's success I decided to put off teaching at least for the time being. The game programming gig would likely be brief and teaching would still be there in any event.

Additionally, AOL (America On-Line) had become a thing about that time and Glider 4.0 houses that people had created with the house editor started being uploaded and downloaded. I was surprised to see the small community that built up. Even a fan newsletter for a time. If creating houses was not your thing, Glider could still get a longer shelf-life by downloading and playing houses that others had created.

### Pararena2Dev.dsk (Commercial version of Pararena)

As with the other disk images, unzip Pararena2Dev.dsk and mount with one of the early Macintosh emulators listed above. THINK C, and  ResEdit are included on the disk so that you have everything needed to build and run Pararena 2.0

**Pararena 2.0** (BNDL identifier `RenA`) was the second game I wrote that was published by Casady & Greene Inc. (C&G). It came about after the success of Glider when C&G asked, "What else you got?" I had my doubts about Pararena but the shareware version had something of a small but dedicated fanbase. I imagined that in addition to color, perhaps I could add enough additional features to make it more commercially viable. The dates on the original files suggest the game was written in July of 1992, roughly a year after Glider 4.0 was written. 

<p align="center">
<img src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/59bf9d9edea64fb81bb62747d7a361da1dcd5bf8/Images/PararenaRejectedSplashScreen.png">
  <br>
<em>Casady & Greene rejected this splash screen.</em>
</p>

Pararena 2.0 was to be another first for me — I was intending to write it in the C language rather than in Pascal (which all my other games had been written in). Once again my shareware game, Glypha, became my testing ground. I rewrote Glypha in C and "shipped" it before beginning my first commercial C application. And again, Glypha written in C was well received and Pararena 2.0 shipped with no problems due to my having learned a new programming language.

Some thing I added to hopefully give it more commercial-game gravitas was an "instant replay" that showed, TV-style, the seconds leading up to a scored goal. I also added several computer opponents that varied from novice to expert-level players. There were tournaments and awards you could try to attain within the game. And finally there was a rudimentary network option where two Macintoshes, connected by a null-modem cable (and if they were lucky) could play a game head-to-head, human vs. human.

Despite all of the above though, Pararena 2.0 never made even 10% of what Glider 4.0 had made. It was not going to be possible to live on the royalties if game sales followed in Pararena's footsteps. I reminded myself though that I still had the Education degree and could always begin my teaching career.
