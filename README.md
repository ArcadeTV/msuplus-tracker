# ArcadeTV MD+ and MSU-MD Issue Tracker

![SupportHotline](https://github.com/ArcadeTV/msuplus-tracker/blob/main/support.png)

### Leave your bug-report, feedback, thoughts and requests about md+ and msu-md patches here.

Use the [issue tracker](https://github.com/ArcadeTV/msuplus-tracker/issues) to leave your comment. 
* Due to the nature of an issue-tracker you will have to click "new issue", even if you have something positive to post.
* Look for existing issues before you post your comment
* Use the green "*New Issue*" button to create a new entry
* Try to give as many details as possible, like version-number, platform etc.

---

### How to join the party

Follow the converstion in the *development* section on the zeldix forums.

> https://www.zeldix.net/f65-development

---

### Current games that need testing

* [ ] Columns (MSU-MD) <br> Columns (USA, Europe).md | D783C244
* [ ] Dr. Robotnik's Mean Bean Machine (MD+) [soundPack missing] <br> Dr. Robotnik's Mean Bean Machine (USA).md | C7CA517F
* [ ] Flicky (MSU-MD/MD+) <br> Flicky (USA, Europe).md | 4291C8AB
* [ ] Joe & Mac (MD+) <br> Joe & Mac (USA).md | 85BCC1C7 <br> prepatch with [Enhanced Colors by Pyron](https://www.romhacking.net/hacks/2276/) | AA9A21A8
* [x] The Lion King (MD+) <br> Lion King, The (World).md | 5696A5BC <br> _Tests complete. Will be released shortly._
* [ ] Thunderforce IV (MD+) [soundPack missing] <br> Thunder Force IV (Japan) (En) (Sega Ages).md | 311D9D4A

_(All roms come from the current No-Intro set)_

---

### soundPacks

All soundPacks are maintained by Relikk. [This folder](https://mega.nz/folder/5MlkSBqR#ZzodSLacnwV3d9I6mGiYLw) contains soundPacks for current patches in development.

If you need test-tracks for soundPack-creation, you will find numbered text-to-speech wave files in the `audio` folder.

---

### What to test

* [x] General playback: is the audio playing, stopping or fading correctly?
* [x] Pause function, may not be implemented yet in beta versions. Playback pausing/resuming should be identical to the original game's behaviour.
* [x] Different platforms: MegaSD, Mega Everdrive Pro, RetroArch /w Genesis-Plus-GX core, MiSTer (MD+ not yet compatible)
* [x] Resetting/Restarting
* [x] A complete playthrough would be A+, you could use cheat codes to speed up the process.

---

### When do tests end?

I will green-light a patch when at least 2 users claim, that the game was extensively tested without any issues.

---

### Games that will be queued for testing (in no particular order) each time the no. of pending games drops below 5:

* [ ] Aladdin
* [ ] Dynamite Headdy
* [ ] Earthworm Jim
* [ ] Earthworm Jim 2
* [ ] Global Gladiators
* [ ] Landstalker
* [ ] Mr. Nutz
* [ ] Pitfall - The Mayan Adventure
* [ ] Ristar
* [ ] Sonic 3D Blast Director's Cut
* [ ] The Jungle Book
* [ ] Zombies ate my Neighbor

---

### Sneek Peeks

I'll drop recordings of current work-in-progress patches in my gDrive folder here:

[previews.arcade-tv.de](http://previews.arcade-tv.de)

---

### Requesting new patches

Please note that my knowledge about all this is limited. As of today I can create patches for games that use the following sound drivers:
* SMPS
* GEMS
* Krisalis
* Cube
* TecnoSoft

I can try to interface any other games but it's not guaranteed to work. Please see [this list](https://gdri.smspower.org/wiki/index.php/Mega_Drive/Genesis_Sound_Driver_List) to identify the driver being used prior to asking for new patches.

The Electronic Arts sound drivers are above my head. Audios Wave Slave MD is also giving me a hard time since 2021.
