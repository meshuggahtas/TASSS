Lynx

Emulator used for this guide: BizHawk 2.3

# Emulator settings
;None:

# Missing emulator features
- ComLynx - 2 or more Lynxes connected for multiplayer games
- Debugging tools (trace logger and debugger)
Note: [http://handy.sourceforge.net/index.htm|Handy emulator] ([Bizhawk/AtariLynx|Lynx core used by BizHawk]) has these tools

# Input combinations
;Option 1 + Pause = 1+p = Restarts the game:
- Returns to second title screen after 0~50 lag frames (game dependent)
- Usable after first title screen; sometimes only in-game (game dependent)
;Option 2 + Pause = 2+p = Flips the screen and reverses controls:
- Your input will be reversed!
- Simply flipping the screen won't save time

# Game workflow
;First title screen:
*Teaser screen displayed for 172~186 frames (game dependent)
*Pressing a button makes the screen go black but still need to wait for a fixed amount of time
*For entertainment purposes, don't make it disappear so fast
*Avoid holding down a button, it will probably delay your next first non lag frame!

;Second title screen:
*Most games contains an animated title screen aswell, usually skippable / speed up (game dependent)

;Menu screen:
*Games' manual usually details what buttons you need to press to advance from here
*Try A/B/Option 1 with or without spaces (A,B,1...) for starting / speeding up (game dependent)
*For entertainment purposes, don't disable the music

# TASing tips
;Disabling music (most games):
*Some games can run faster with music disabled, saving you from lag frames (game dependent)
*Right at the menu screen you can disable music usually with Option 2 (2); sometimes you need to pause the game first (game dependent)
;Invisible lag frames (most games):
*Most games have lag frames not flagged as a lag frame
*When this happens, usually only the pause and the two input combination has any effect
;Left+Right/Up+Down: There's only two known examples of this:
*Basketbrawl: [https://imgur.com/fAY34fZ|only the graphics glitch out, probably doesn't affects the gameplay TASing wise]
*Xybots: [https://imgur.com/mzQ5TCD|severe glitches can occur as illegal opcodes being executed]
**Pressing UD or LR and some other buttons (not all combinations) either crashes the game or let's it restart after a few seconds. I'm not sure but I think there was a Lynx version without a "middle pivot" http://www.old-computers.com/museum/photos/atari_lynx2_1.jpg 
**Unlike in BizHawk, Handy 0.95  windows contantly popping up "C6502::Update() - Illegal opcode (33) at PC=$0065."

# Links
- [https://en.wikipedia.org/wiki/Atari_Lynx|Wikipedia Atari Lynx]
- [https://gamefaqs.gamespot.com/lynx|GameFAQs Lynx]
- [http://www.monlynx.de/lynx/lynxdoc.html|Lynx technical documentation]

# TODO
- Missing emulator features: __needs investigation__: sub frames input on console?

# Miscellaneous notes
- Cart swapping is not investigated at all. No information about having a "cart lock" (plastic piece preventing cart swapping).
