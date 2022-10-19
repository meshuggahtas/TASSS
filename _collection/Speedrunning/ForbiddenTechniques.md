- Real-life hazards are public information from users reporting it, they might be fake!

# Not present in BizHawk 2.3.1

## Info

Potential techniques requiring a so far not implemented feature.

- Already present features with not perfect emulation are omitted (example: N64 core).

- Rule conflicting techniques relying on a missing feature are also omitted (example: adapters).

## Subframe inputs

A platform/game that polls for input from the console/controller multiple times within a single frame

- [https://github.com/TASEmulators/BizHawk/issues/973|GitHub Request: Subframe inputs where games poll for input multiple time in a frame #973]

- Development in progress: [=forum/t/20758|SubNESHawk]!

- Only NES currently: [=forum/p/479712#479712|Alyosha's post about core compatibility/extendibility]

- [=forum/p/478592#478592|Older posts about potential problems]

- Potential techniques:

## NES DPCM glitch

  - NTSC NES and Famicom games that use [https://wiki.nesdev.com/w/index.php/APU_DMC#Conflict_with_controller_and_PPU_read|DPCM and non-redundant controller reading]

  - Relevant TASes:

    - [=userfiles/info/52430841117850526|SMB3 in 126 polls by Masterjun] (Same strategy as total_'s but different inputs)

    - [=userfiles/info/52514549789799992|NES SMB3 by total_ & Ilari @ ADGQ 2017 (SubNESHawk movie by total_)]

    - [https://youtu.be/EHfw-BEuRO8?t=4436|SMB3 in 2 seconds by total_ & ais523] ([http://fuzyll.com/2016/the-smb3-input-polling-glitch/|Fuzyll's explanation of the movie]) - 143 polls according to the input file

    - [https://www.youtube.com/watch?v=ydxyXgVaNGI|Gimmick by negative_seven using total_'s script modified]

  - [https://forums.nesdev.com/viewtopic.php?f=6&t=16117|(Incomplete) "List of NES and Famicom games that use raw PCM (7-bit, etc)"]

  - [https://www.youtube.com/watch?v=JGT0FM3yh-w|Battletoads DPCM demonstration (of toggling PCM on/off, not a speedrun)]

  - Number of possible titles: No known values, my estimation is ~80.

  - SMS pause spamming [=forum/p/452590#452590| at each interrupt (NMI, VBlank)]

  - Number of possible titles: Can not be estimated, requires elaborate (automated) testing, probably less than a hundred.

  - Subframe resetting for RPGs to corrupt (usually) save files: 

  - [2047M]

  - [3692M]

  - Number of possible titles: Can not be estimated, probably a thousand.



# Plugging/unplugging controllers

Nearly all platforms allow to plug or unplug controllers while the console is powered on / game is playing

Potential techniques:

  -  Exploiting online features

  - PS4 Call of Duty Black Ops 4 - [https://www.youtube.com/watch?v=cCgPOZvBukw|XP lobby glitch]

  - Number of possible titles: No known values, probably a few hundred

  -  Duplicate items by trading to a new local player

  - PS4 Portal Knights - [https://www.youtube.com/watch?v=ERMzfIJShfw|Item duplication]

  - Number of possible titles: No known values, probably a few thousand

  - AI joining when unplugging controllers

  - SNES Secret of Mana [=forum/p/476666#476666]

  - Xbox Shrek 2

  - Number of possible titles: No known values, probably a few hundred

  - Other

  - PS2 Mortal Kombat: Deadly Alliance - [https://youtu.be/aTCHLcsWCNw?t=19|Moving freely after round won by unplugging and plugging back controller]

  - Wii U Super Smash Bros. - [https://www.youtube.com/watch?v=9Hys_KdBXIU|Controlling 8 players with 1 controller]

  - Number of possible titles: Cannot be estimated (too many platforms and no list of games with unplugging/plugging effects/requirements), probably a few thousand



# Connectivity

2 or more platforms/consoles connected together



Somewhat relevant [https://github.com/TASEmulators/BizHawk/issues/325|GitHub GBA Link Play #325]

Development in progress: [=forum/p/479504#479504|GBHawkLink by Alyosha!]



AppleTalk

  - Apple II

Microdrive

  - ZX Spectrum



ComLynx cable

  - Only Lynx

  - Number of possible titles: 36

WSWAN Link cable

  - Only WSWAN

Game Link Cable (different generations) - [https://en.wikipedia.org/wiki/Game_Link_Cable|Wiki]

  - GB, GBC, GBA

  - [https://gamefaqs.gamespot.com/gba/916598-game-boy-advance/faqs/34105|Compatibility on GameFAQs]

  - Number of possible titles: At least 200 (GB+GBC) and 20 (GBA).



Sega Genesis Zero Tolerance System Link Cable

  - Only GEN and only the game Zero Tolerance

Gear-to-Gear Cable

  - Only GG

  - Number of possible titles: At least 100.

PlayStation Link Cable - [https://en.wikipedia.org/wiki/PlayStation_Link_Cable|Wiki]

  - Only PSX

  - Number of possible titles: At least 50.

Taisen Cable

  - Only Sega Saturn

  - Number of possible titles: 10.



Neo Geo Pocket/Dreamcast Setsuzoku Cable

  - DC, NGP

  - Number of possible titles: 7.

Neo Geo Pocket Link Cable

  - Only NGP

  - Number of possible titles: At least 50.



Not implemented cores with networking:

  - Arcade

  - Various

  - WiFi/Network cable for...

  - Windows

  - DOS

  - Linux

  - MSX

  - Only Nintendo DS 

  - Only Wii

  - GameCube – Game Boy Advance link cable - [https://en.wikipedia.org/wiki/GameCube_%E2%80%93_Game_Boy_Advance_link_cable|Wiki]

  - GBA, GC

  - Number of possible titles: At least 50.



Checked (and bolded platforms with missing connectivity):

Arcade, Apple II, C64, MSX, ZX Spectrum

Windows, DOS, Linux

2600, 7800, Lynx

INTV, Coleco, 

NES, SNES, GB/GBA, GC, DS, N64, VBoy, Wii

GG, Genesis, Saturn (TODO: maybe 32x and CD too ?), 32x, CD, SG-1000, SMS

PSX

NGP, WSWAN

PC-FX, TG-16, PCE, SGFX

Uzebox



# Non existing Cores

Platforms without Emulator

Might be placed somewhere else?

!!! Missing home-console emulations

!! 2nd gen

[https://en.wikipedia.org/wiki/Vectrex|Vectrex]



!!! Missing handheld emulations

!! 4th gen

[https://en.wikipedia.org/wiki/TurboExpress|TurboExpress] (portable TurboGrafx 16)

[https://en.wikipedia.org/wiki/Gamate|Gamate]

[https://en.wikipedia.org/wiki/Watara_Supervision|Supervision]

[https://en.wikipedia.org/wiki/Mega_Duck|Mega Duck / Cougar Boy]



!! 5th gen

[https://en.wikipedia.org/wiki/Sega_Nomad|Sega Nomad] (portable genesis)

[https://en.wikipedia.org/wiki/Game.com|Game.com]

[https://en.wikipedia.org/wiki/Design_Master_Senshi_Mangajukuu|Design Master Senshi Mangajukuu]

[https://en.wikipedia.org/wiki/R-Zone|R-Zone]


----

!! Techniques conflicting with rules



# Info

Potential and theory techniques disobeying TASvideos' rules (as of 2019/03/09).



Special exceptions like Rygar auto hold buttons post-TAS are excluded.

Movie publishing related problems independent of using not allowed techniques are excluded too (example: educational games or triviality).



# No tampering with the files the game is composed of

Rule: [MovieRules#NoTamperingWithTheFilesTheGameIsComposedOf]



Emphasis on That means no renaming/copying/deleting/replacing/editing files that affect game-play. 

[https://kb.speeddemosarchive.com/Rules#Fundamental_rules|SDA has a similar rule], ...interacting with the game other than through the gameplay itself is not allowed. This rule covers ... active methods (such as removing or altering a game disc/cartridge/file while the game is running).



Potential techniques:

Using built-in consoles accepting commands

  - [https://www.youtube.com/watch?v=J0n-TIrpkDA|Half-Life: Done Enormously Warped] uses console commands (scripts (.cfg files) were written beforehand as they consist of binds for spamming wait commands and for stopping the individual segments (stop the demo, save the game), etc...).

  - Many PC games expose low-level operations such as ejecting the disk, creating or deleting files, making it very hard to generalize a rule for this kind of activity.

  - Using consoles usually requires to activate a cheat/developer/debug mode beforehand.

  - More examples: PC Quake, PC Morrowind, PC Source engine games

  - Number of possible titles: very high, few thousands.

Editing files (on platforms with the ability to edit part of a game)

  - Many PC games allow you to edit in-game variables stored in a .ini/.cfg (human readable format) file.

  - More examples: Duke Nukem 3D, Half-Life, Skyrim.

  - Number of possible titles: low, maybe a few hundreds.

Theory techniques:

Repacking game data 

  - Manipulating files to make more optimized to the game engine, shortening game load without changing the process of the gameplay

  - PC Doom 3 games unpacking files from .zip files on the fly, so de-/compression speed affects loading time.

  - [=forum/p/481068#481068|YaLTeR's example of .gcf files for PC Source engine games]

  - Number of possible titles: very low?

Changing files from the outside of playing the game

  - Modifying file permissions, for example, to don't allow reading cinematic files

  - Deleting specific files (executable related) but levels (game related)

  - Ejecting disk while installing, aborting the process to have an any% of game files

  - [=forum/t/14067|Copying memory card content] to skip prompts about overwriting a save file.

  -  The GameCube example has this flaw mentioned: This is not a legal GameCube operation since it cannot be booted into it's memory card manager, and run the game at the same time. 

  - Most platforms requires an (first/third party) external device and/or a different software that's usually specifically made to edit files. TASVideos movies don't allow to power off and on the platform in the middle of the TAS.

  - Number of possible titles: very high, few thousands.



# Password related

Rule: [MovieRules#NoSkippingToTheEndWithAPassword]



Judge: [=forum/p/468596#468596|Mothrayas' last post says: No.]



It's understandable that passwords are a "beneficial cheat codes", used to skip portions of the game and/or with better statistics.

 Potential techniques

  - Generated passwords

  - Some games allow you to generate a password as a form of saving your progress instead of relying on hardcoded passwords. This means there are games where you could generate a password that results in something that wasn't expected.

  - SNES Prince of Persia: [=forum/p/474160#474160|if you die and abuse the bug of ability to generate password while dead, you can get nearly the final stage's password].

  - Password bugs

  - Using passwords' side-effect to lower difficulty and skip challenges.

  - Rejected TAS using a password's unintended side-effect to skip to credits: [3568S]

  - Rejected (for something else) TAS using a rejected password's effect to gain benefits: [5175S]

Number of possible titles: very low, probably a hundred.



# Arbitrary initial RAM

Rule: [MovieRules#NoRandomizedOrUnverifiedCustomInitialRamState]



Platforms/games that forgoes initializing initial memory

There is only 1 TAS which is allowed to use after providing video footage of doing it on a real console: [2487M]

  - The only relevant category other than the former ([Movies-C3061Y|Uses uninitialized initial state]) is [Movies-C4015Y|Starts from a saved state or SRAM] but as my questions being answered below, this isn't allowed.

Nach's very detailed and very long research: [/HomePages/Nach/MemoryInit]

  - My subjective view is that I disagree with the current rule reference and Nach's reasoning. [=forum/t/20046|My posts about this in this thread].

Rejected for arbitrarily initialized RAM [5266S] / [5387S] / [5883S]

  - [=forum/t/15716|SNES thread for known games with uninitialized RAM]

  - [=forum/t/16127|Another SRAM thread]

  - [https://wiki.nesdev.com/w/index.php/Game_bugs#Reliance_on_RAM_values|Some NES games relying on specific RAM values].

Number of possible titles: possibly more hundreds.



# Arbitrary images

Rule: [MovieRules#RomImageMustBeIntegral]



Platforms and games that require external medium%%%



The current rules doesn't allow any ordinary CDs to be used even if the game explicitly says and waits for.

Rejected but otherwise it would be acceptable: [6033S]



Number of possible titles: Probably a hundred.



# Arbitrary audio

Rule: [MovieRules.html#DesmumeMovies]



Platforms/games that require an audio input.



According to the current state of rules, there are no real restrictions apart from being not copyrighted



Latest discussion: http://tasvideos.org/forum/viewtopic.php?p=483149#483149



Number of possible titles: Probably a hundred.



# Arbitrary environment

TODO: First focus on DOS problems

TODO: Later add relevant PC fps problems



# Missing archivation of games

Rule: [MovieRules#RomImageMustBeGood]



Platforms/games not archived or the inability to ensure the game is really original, unmodified

FDS

  - If C64, DOS, and some other consoles have the privilege to make use of cracked ROMs, other platforms should also take advantage of with some more rules applied. Mostly pointing arrows towards this platform, which media is also degradable and is in a poopy situation.

  - Not approved method [=forum/t/16439|Erasing save files on FDS games]

J2ME

  -  (.jar mobile games) don't have a reliable archive collection.

  - These games usually modify themselves when saving settings or other things, making them unreversible to the original state after playing it at least once.

  - This is a bit of a problem because these files are easy to manipulate, so pirate released ones will include their graphics / texts, modifying the original game.

  - Other mobile platforms except for Android also doesn't seem to have a verified collection of ROMs.

Number of possible titles: more thousand.



# Rom conversion

Rule: [MovieRules#RomImageMustBeGood]



Platforms that accepts multiple game media



No official tools

  - NES: FDS <--> NES not possible (different formats, requires elaborate hacking especially if source code is not available)

  - C64: Possible from TAP to T64/PRG/D64 etc

  - Rejected for failing being "a standard practice for the platform in question, and if it's possible with unmodified official set." [6086S]

Official tools as a peripheral

  - Sega Cards/My Card: (Power Base Converter/Master System Converter and Card Catcher)



Number of possible titles: Can not be estimated, probably thousands.



# Disc swapping

Rule: [MovieRules#RomImageMustBeIntegral]



Games with multiple discs



Relevant tricks:

  - [https://www.youtube.com/watch?v=ltwvh_yZbGk&feature=youtu.be|PSX Yu-Gi-Oh! Forbidden Memories - getting overpowered characters] 

  - [https://www.youtube.com/watch?v=erh8KT0CoqU&feature=youtu.be|PSX Final Fantasy VII skipping FMV]

Number of possible titles: Can not be estimated, might be more hundreds.



# Game version

Games that also came in multicart format, not just standalone



Using a multicart version of a game can potentially change different game factors from simple lag frame differences to different starting memory states.

Example: NES Streemerz and other games from [https://wiki.nesdev.com/w/index.php/Action_53|Action 53]

Multicarts are not allowed when there's also a standalone version, see [=forum/p/455262#455262|Mothrayas' last post]

Number of possible titles: very low, maximum a hundred.



# Adapters and converters

Relevant rule: [MovieRules#GameMustBeReal]



Platforms with adapters/converters non- or officially manufactured to play games released for other platforms

[https://en.wikipedia.org/wiki/Atari_5200|Atari 5200] A2600 adapter (official)

[https://en.wikipedia.org/wiki/Intellivision|Intellivision] System Changer A2600 adapter (official but third party)

[https://en.wikipedia.org/wiki/ColecoVision|Colecovision] Expansion Module #1 to A2600 (official but third party)

Number of possible titles: very high, thousands



# Console version

Rereleased consoles with different software/hardware



Many retro consoles have been re-released with different timings, hardware

Some examples:

  - PSX rereleased as [https://en.wikipedia.org/wiki/PlayStation_Classic|Playstation Classic], running the open source emulator [https://docs.libretro.com/library/pcsx_rearmed/|PCSX ReARMed]

  - NES rereleased as [https://en.wikipedia.org/wiki/NES_Classic_Edition|NES Classic Edition] with an emulator made by NERD ([https://en.wikipedia.org/wiki/NES_Classic_Edition#cite_note-NLcitesNERDengine-10|Nintendo European Research and Development])

  - SNES rereleased as [https://en.wikipedia.org/wiki/Super_NES_Classic_Edition|Super NES Classic Edition] with an emulator made by NERD

Many retro consoles have been remade/cloned by other companies under a different name:

  - [https://en.wikipedia.org/wiki/Nintendo_Entertainment_System_hardware_clone#Clones_by_region_or_country|Wikipedia - Clones by region or country]

  - [https://en.wikipedia.org/wiki/List_of_home_video_game_consoles|Wikipedia - List of home video game consoles]

  - [https://en.wikipedia.org/wiki/List_of_handheld_game_consoles|Wikipedia - List of handheld game consoles]

Number of possible titles: probably a few thousand.

# Debug and cheat codes

Rule: [MovieRules#CheatsDebuggingCodesAndArcadeContinuesAreNotAllowed]



Some games have mistakenly not disabled debug modes still accessible either by pressing a button or fulfilling a list of conditions.

Potential techniques:

  - Debug codes

  - Doesn't matter if it's featured in a "manual" (rejected [5411S])

  - Doesn't matter if it's done by a list of conditions (rejected [3023S])

  - Doesn't matter if it's never documented anywhere: (rejected [5524S] & [3980S] & [1753S])

  - Other example: NES Megaman 3 Player 2 buttons

  - Some popular and mostly very (hours) long games have RTA runs on speedrun.com: debug%

  - Number of possible titles: Probably a thousand.

  - Cheat codes

  - Some popular and mostly very (hours) long games have RTA runs on speedrun.com: cheats% 

  - Rejected: [5882S]

Number of possible titles: Probably more thousands.

----

!! Dangerous and real-life hazards

# Info

Potential phenomena that could be considered for speedrunning purposes.



[=forum/p/473729#473729|Recent post by feos]

> We do not allow events of the physical or hardware world to be used in TASes. Because these can't be emulated.

Somewhat relevant [https://kb.speeddemosarchive.com/Rules#Fundamental_rules|SDA rule (Impossible inputs)]:

> As such actions require worn out controllers, non-standard controllers or excessive force, they are treated as hardware modification and are thus banned as well.

# Cart tilting

Platform that allows [https://www.wikihow.com/Tilt-a-Video-Game-Cartridge|pulling of the game media slightly, interfering the console's access to said cart's connectors]

[https://www.youtube.com/watch?v=qh4KPCzeAJI&list=PLfsq8ifWdwTCNptQv2klkr6NCtsgTqdtU|N64, SNES, Wii, GC cartridge tilting series]

[https://www.youtube.com/playlist?list=PLIPMG9ZBMcxSF4WR95IDmz34xk-K3_bCu|Genesis and N64 cartridge tiltings]

[https://www.youtube.com/playlist?list=PLB42E8F7278C79593|Genesis and NES cartridge tiltings]

Genesis Sonic 3D Blast - [https://www.youtube.com/watch?v=M09oJusoKpI|Tap the cartridge on left side for level select screen (crash handler)]

 There are also various videos for the platform GBA.

[https://glitchcity.info/wiki/Nintendo_64_crooked_cartridge|N64 (4 examples)]

[https://www.mariowiki.com/List_of_Super_Mario_64_glitches#Cartridge_Tilting_glitches|N64 SM64 (5 examples)]

[https://glitchcity.info/wiki/Game_Boy_cartridge_tilting|GB (no examples)]

[https://glitchcity.info/wiki/Nintendo_DS_Sleep_Mode_exploit|Nintendo DS Sleep Mode exploit (2 examples)]

[https://gamefaqs.gamespot.com/boards/925329-nintendo-ds/71009293|Nintendo DS Sleep Mode (4 examples)]

[http://errors.wikia.com/wiki/Cartridge_tilting|22 text examples]

[https://retrocomputing.stackexchange.com/questions/1648/how-can-tilting-a-n64-cartridge-cause-such-subtle-glitches|The most technical overview of this trick I found so far, explaining the "lift left side, keep down right side" technique]

[https://www.twitch.tv/videos/177325971|NES Battletoads skipping to credits]



# Cart swapping

Platform that allows pulling of the game media + Games that forgoes erasing or writing initial memory



[https://youtu.be/WcWfwvsw7Jw?t=214|N64 game that initially planned to support to be cart swapped] - (Donkey Kong 64 x Banjo Kazooie [http://rare.wikia.com/wiki/Stop_%27n%27_Swop|Stop 'n' Swop])

  - [https://retrocomputing.stackexchange.com/questions/1837/can-removing-a-cartridge-from-an-nes-or-any-other-cartridge-based-game-system|The most technical overview of this trick I found so far, explaining the potential dangers and history of the idea of hotswappability]

[https://www.youtube.com/watch?v=xayxmTLljr8|GBC Pokemon Red cart swapping to GBC Magi-Nation]

[https://www.youtube.com/watch?v=SL_Zuc0tlvo|GBC Pokémon to GB SML2]

  - [https://www.reddit.com/r/speedrun/comments/5fq53n/player_uses_a_pok%C3%A9mon_red_memory_glitch_to/|More info in a reddit thread]

[https://www.youtube.com/watch?v=eEEnEoKSgQs|NES SMB to NES Tennis to NES SMB for "Minus" (32) world]

[https://www.youtube.com/watch?v=m_RLPV1yLDc|NES SMB 3-in-1 to NES SMB 3-in-1]

[https://www.youtube.com/watch?v=e68lj-4Sp2M|The Frame Savers - Episode 78 - Cart Swap #3]

[https://www.youtube.com/watch?v=trFuItoeUQo&index=1&list=PLhhegQQM3PvQw-94R7xr6mY7QdsYcfYCe|OG Yank the Cart series: Genesis cart swappings]

[http://www.sega-16.com/2005/12/cart-swapping-tricks-cheating-at-your-own-risk/|Sega-16's complete list of cart swapping tricks for Genesis]

[https://glitchcity.info/wiki/Cart-swap_arbitrary_code_execution|Cart-swap arbitrary code execution on SNES / GBC]



Number of possible titles: no known values, my estimation is a few hundred

Genesis: cart swapping to use region locked games

A7800:

> It doesn't appear to have any ill effects, actually, on the system or the carts. However, it will crash the game in progress and, in about 80% of cases, will actually draw graphics stored on the second cartridge on the screen. Also, with a cart out of the slot the screen resolution apparently changes itself depending on the presence (or lack thereof) of a cartridge in the cartridge slot.

----

# Destruction

Physical interactions



Frying

Very similar to cart swapping but here it's all about rapidly powering on and off the console, preferably keeping the button between the two states. 

Most prominent example is [http://www4.ncsu.edu/~awwatkin/ATARI/2600/2600cheat.html|A2600 with various results].

[https://www.youtube.com/watch?v=2TIPpXQ2o-Q|Simple demonstration of frying Atari 2600]

Other link for Atari: http://www.ataricompendium.com/game_library/easter_eggs/vcs/vcs.html



Metal bread knife on Colecovision

> Being a stupid kid, I would run a metal Bread knife along the board in the expansion slot of my Colecovision with the power on and game playing! Some of the more interesting "effects" was in the game Popeye it garbled the graphics/playfield,, somehow though it seemed to have the effect of combining 2 screens! The ship level was combined with the building level with the See-saw with Wimpy on the bottom. In Mr. Do! It mixed up colours and seemed to create invisible enemies (or make my character invisible) needless to say I wont be trying that with either of my current Colecovisions!



Kicking the console

  - SNES usually hangs up, only audio plays. I don't know working tricks based on kicking console.



Environmental conditions

Super Mario 64 cosmic ray

  -  So far unverified phenomenon, causing a [https://en.wikipedia.org/wiki/Single_event_upset|single event upset] that's accidentally [https://www.youtube.com/watch?v=X5cwuYFUUAY|upwarps Mario to a platform above him (TTC Upwarp)]

Product life, components aged, failed... 

  - [https://www.youtube.com/watch?v=_e9xdvXR8m0|Battletoads Reset button to finish the game...]

----

!! Forbidden for good reasons



# Info

Self-explanatory.



# Life and death

The natural life cycle of electronic, hardware parts has a birth, life and death. Eventually all parts die.



 Relevant text from [https://ieeexplore.ieee.org/document/5008348|IEEE document 5008348 "Birth, Life, and Death in Microelectronic Systems"]:

  -  ''[[...]]defects might be introduced during manufacture (at birth), or cause errors during operation (life). The number of permanent failures which could be endured by a system before it fails completely will determine its lifetime (death).''



 High-level view of parts used during playing a video game:

 Display <-- Platform <-- Controller

              v    ^

            Game media



# Arbitrary BIOS

Rule: [MovieRules#BiosMustBeReal]



Platforms using BIOS or firmware files.



 Very similar to platform exploit with the difference of ability to get immediate effect by editing the BIOS/firmware to jump to credits.

 That's being said, I don't see any real reason for a movie to abuse this.



# Platform exploits

Relevant rule from [MovieRules#Playarounds]: ''Arbitrary code payloads which have nothing to do with the game are not allowed. A payload which would work just as well contextually if executed on any other game for the platform will be rejected. TASVideos is not a place to show off your science projects. ''



 My opinion

  -  Exploiting the platform is not really a speedrun. We run the game and then we speedrun until the end.

  -  Communicating directly with the console is an impressive feat. If it's that entertaining, there could be platform TASes, like "PSX Console any%".



 Rejected submissions

  -  Wii buffer overflow [3515S]

  -  SNES external port [5447S]



!! SDA relevant informations

(From ais523)

SDA bans file tampering unless it's purely graphical; 

password skipping is invariably considered a separate category (and normally an uninteresting one)

cart swapping would also be its own category.

SRAM initialisation doesn't seem to be settled yet in the realtime community

as for scripting, it /used/ to be allowed at SDA but they changed their mind and banned it



# TODO

 1. Revisit Movie Rules

 2. Update applicable techniques

 3. 

 Move to other pages

  -  N64 platform resource

  - [6051S] - Emulation for the Nintendo 64 is not cycle accurate, and therefore, no functional emulator in this present time emulates lag properly.

  -  J2ME platform resource

  -  J2ME hardware differences: Non frame based systems and highly different between hardwares

  -  J2ME games can behave really weird. slow device: slow fps, high end device: high fps. resolution based gameplay. thirdparty apis. some games doesnt work at all on most phones. kvm memory.... link my jar informations thread here

 Not an accepted rule so far: [MovieRules#NoArbitraryFramerates]

  -  Examples: [=forum/p/476811#476811|Super Meat Boy], [=forum/p/476207#476207|some examples in the original thread of the rule proposal], more @ [=forum/f/60|Windows and Linux games thread], even more: Serious Sam HD, Doom (2016)

 NOP-ing

 file system tricks
