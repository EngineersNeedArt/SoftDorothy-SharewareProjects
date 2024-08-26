# Soft Dorothy Software Projects
Disk images (intended for emulators) containing code and tools for building **Soft Dorothy Software** games.

<p align="center">
<img width="330" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/295e289562f222900652959fb653b5ffed056fe2/Images/SoftDorothy.png">
</p>

My desire was to recover the sources to my old **Soft Dorothy Software** games as well as the old build environment (THINK C, THINK Pascal, ResEdit) and create disk images suitable for the current early Macintosh emulators. The disk images here (zipped to save space) can be downloaded and you should be able to mount them in <a href="https://basilisk.cebix.net">Basilisk II</a>, <a href="https://sheepshaver.cebix.net">Sheepshaver</a> or <a href="https://www.gryphel.com/c/minivmac/">MiniVMac</a>. 

### GlyphaII.dsk

The project, sources and resource file for **Glypha II**. THINK Pascal and ResEdit are included on the disk image as well. As with the other files, GlyphaII.dsk needs to be unzipped and then mounted with one of the early Mac emulators listed above.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/5fb25ed444c855425479c3b8577312ed1c83052a/Images/GlyphaIIScreenshot.jpg">
</p>

Most of the files indicate a date of around May or June 1991. The fall of 1991 was when I believe I released the first commercial game, **Glider 4.0**, via Casady & Greene Inc. (C&G). C&G wanted a color game (of course) but I had only a B&W Macintosh Plus up until this point. They gave me an advance against future royalties that I used to buy a IIsi color Macintosh computer and a color display.

Even though I now had color computer I was still new to color programming. It seemed crazy to me that my first foray into color would also be my first commercial game. So in fact I took my shareware game, Glypha, and decided to port that to color before ever beginning on the commercial Glider. The rationale of course was that I could cut my teeth on a free app, "ship it" (post it to various FTP sites) and get feedback as to whether I was crashing anyone's computers while I began what would be Glider 4.0 for C&G.

The good news was that Glypha II ran fine — as did Glider 4.0 when it shipped later that year. Something I did not know then was the degree to which C&G would test Glider 4.0 on all the hardware they had available before pressing thousands of floppy discs. I need not have ben as anxious as I was.

### Glider4Dev.dsk

**Glider 4.0** was the first game I had published commercially. I had seen a few games published by Casady & Greene, Inc. (C&G) and reached out to them to see if they were interested in Glider. I suggested I could write a commercial Glider to support color and that the game would have a "house" (the game levels) with some forty or so rooms (the shareware game had only ten or fifteen rooms as I recall). They agreed and so advanced me enough cash to buy a color Macintosh and a color display.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/f188aaed99fccf01c4140afe1641e17ed16a959e/Images/BasiliskIIScreenshot.jpg">
</p>

I believe I more or less finished Glider 4.0 around the beginning of the fall of 1991. That fall I was in my last year of an Education degree at the University of Kansas. I student taught that last year and I recall telling my high school students that I had a game coming out, ha ha.

The "houses" for Glider are like a collection of *levels*. I determined pretty quickly that creating a "level editor" for Glider would make it much easier for me to create the promised house of forty or more rooms. And so the creation of both **Glider 4.0** and a **House Editor** began more or less at the same time.

I could have kept the House Editor as an internal tool but I realized that if users could create and share their own house creations, it would add to the appeal to Glider. I think i was thinking about something similar to the Pinball Construction Set game.

I found out very quickly though that work on the House Editor in fact involved more work than Glider itself. It turned out that "idiot proofing" the editor required a lot of sanity checking and busy work. As an example, when a user adds a bouncing ball to a room, there is a Get Info dialog that allows you to edit various paramters of the ball such as the **Length of travel**. When a user entered a value I had to make sure it was not negative, not too large for the room. These kinds of sanity checks are all over in the code and required a lot of busy effort.

<p align="center">
<img width="752" src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/e13d52bbfb8e2eb1e904a019a68b3ddd9c84a19a/Images/GliderEditorScreenshot.jpg">
</p>

Glider 4.0 went on to win a coveted MacWorld Game Hall of Fame award. I graduated with my Education degree but as a result of Glider's success I decided to put off teaching at least for the time being. The game programming gig would likely be brief and teaching would still be there in any event.

### Pararena2Dev.dsk

As with the other disk images, unzip Pararena2Dev.dsk and mount with one of the early Macintosh emulators listed above. THINK C, and  ResEdit are included on the disk so that you have everything needed to build and run Pararena 2.0

**Pararena 2.0** was the second game I wrote that was published by Casady & Greene Inc. (C&G). It came about after the success of Glider when C&G asked, "What else you got?" I had my doubts about Pararena but the shareware version had something of a small but dedicated fanbase. I imagined that in addition to color, perhaps I could add enough additional features to make it more commercially viable. The dates on the original files suggest the game was written in July of 1992, roughly a year after Glider 4.0 was written. 

<p align="center">
<img src="https://github.com/EngineersNeedArt/SoftDorothyProjects/blob/59bf9d9edea64fb81bb62747d7a361da1dcd5bf8/Images/PararenaRejectedSplashScreen.png">
  <br>
<em>Casady & Greene rejected this splash screen.</em>
</p>

Pararena 2.0 was to be another first for me — I was intending to write it in the C language rather than in Pascal (which all my other games had been written in). Once again my shareware game, Glypha, became my testing ground. I rewrote Glypha in C and "shipped" it before beginning my first commercial C application. And again, Glypha written in C was well received and Pararena 2.0 shipped with no problems due to my having learned a new programming language.
