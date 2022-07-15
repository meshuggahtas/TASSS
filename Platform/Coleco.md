
%%TOC%%

Emulator used for this guide: BizHawk 2.3

! Emulator settings
Note: the Super Action Controller doesn't works in this version!
;Controller Settings:
* Turbo controller = Steering Wheel for a few games (6 at least)
* Super Action Controller = 4 extra colored buttons for 3 sport games but usable for any games
;Skip BIOS intro:
*Note: __Uncheck__ this if you are going to submit your TAS!
;Use the Super Game Module:
* Note: some extended RAM is missing in this version!
* Only specific fan games make any use of this

! Game workflow
;Colecovision logo:
*0~678 lag frames (game dependent)
*There are games which bypass the BIOS, skipping this long wait

! TASing tips
;Left+Right/Up+Down:
Most of the time just visual glitches, rarely usable...
* 2010 - The Graphic Action Game: Holding down both 4 buttons does some weird things. Nearly looks like a developer code as it's scrolls through the screen and nearly perfectly jumps to various slots in the action scenes.
* Bumpman - Gets stuck, isn't useful
* Donkey Kong - U+D to get 1 pixel inside the wall (probably only useful in level 3, but works in every level because of ladders)
* Mr Do's castle - unwinnable state holding U+D to climb further the stairs. Not useful.
* Roc N Rope - L+R while cimbing extends the rope infinitely (by wrapping around the screen). Going out of bounds vertically "crashes" the game so you need to get off the rope at the top of the screen. While it looks funny, unfortunately it doesn't saves time because of the additional wiggling (causing many lag frames) while climbing the extended rope.
* Subroc - Just visual glitches
* Tank wars - Pressing the down button with 2 other directional buttons changes it's state depending on the two directions. Not that useful because they will make you stationary forever.
* Wizard of id Wizmath - Position bug somewhat oob but not that useful in this game.

! Links
* [https://en.wikipedia.org/wiki/ColecoVision|Wikipedia ColecoVision]
* [https://gamefaqs.gamespot.com/colecovision|GameFAQs ColecoVision]

! TODO
* Missing emulator features? subframes?
* feed me with stray links (technical docs)
* investigate cart swapability.
* investigate RAM initialization.
