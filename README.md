# hbv-nes
NES reverse engineering project for Host Based Vulnerability Discovery at UNO

## Proposal

For our semester project, we would like to reverse engineer an original Nintendo game, such as Super Mario Bros or Final Fantasy. As the NES uses the 6502 CPU, with a dramatically different processor architecture than x86, simply learning the new instructions and different methods of doing things should prove to be an interesting challenge. Fortunately, due to the hobbyist community, a significant amount of documentation exists to explain processor architecture, hardware, and file layouts. Numerous emulators have been created as well, with the most popular being FCEUX on Windows and OpenEmu on OSX.

We expect the actual project to consist of a mixture between simply analyzing and understanding the code in one of these games, and making some edits to the game ranging from trivial to complicated. Initial ideas include changing sprites and text (trivial), changing starting lives, score, and time (easy), modifying enemy behavior (medium/hard), or giving Mario new abilities like double jump (hard). Based on initial research, there are tools out there to easily edit graphics, but other editing usually requires a hex editor supplemented by an emulator’s debugger. For very popular games like Mario, numerous modified ROMs (known as ROMHacks) already exist and can be used for reference or additional inspiration.

Initial resources we’ve located include architecture reference for the 6052 at https://fms.komkon.org/EMUL8/NES.html, the community at https://www.romhacking.net/ and John Riggs’s YouTube tutorials on NES ROMhacking at https://www.youtube.com/playlist?list=PLsOTz-tlvayLmYmgreE4q1w0E6rN29T4p.
