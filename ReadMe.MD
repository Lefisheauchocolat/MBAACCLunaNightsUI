# Melty Blood Luna Nights Again Current Code 
GitHub repository for a MBAACC mod that mainly replaces the vanilla UI with a Touhou Luna Nights styled interface using ripped and edited assets from the game. 

### What the hell does this include?

Files for vanilla stages with the foreground grass layer removed, custom character select and win screen songs, Luna Nights style UI and menu sounds.

### How the hell do I install this?

1. Click the green code button in this page and then select `Download ZIP`
2. Grab the File Extractor from [here](https://files.catbox.moe/ghmr93.zip) or from the included zip (File Extractor.zip) 
3. Move dump.exe to the same folder as MBAA.exe
4. Drag and drop the following .p files into dump.exe (a cmd window should pop up showing extraction progress): 

```
0000 (Stage files);
0001 (BGM files);
0003 (Visual assets);
0005 (SFX and voicelines); 
0007 (Story/Win quote files);
and 0008.p (Translation files).
```

5. Move everything inside the newly created `out` folder to the same folder as MBAA.exe
6. Rename the .p files listed above
7. Move mod files to the same folder as MBAA.exe, replacing files when prompted.

### Can I disable X part of the mod?
Most things, yes! Here's a quick list of things you can easily toggle:

- Edited Stages (aka. vanilla stages without the grass layer) - Rename 0000.p to enable, rename it back to 0000.p to disable;
- Custom music (for character select and win screen) - Rename 0001.p to enable, rename it back to 0001.p to disable;
- Custom UI - Rename 0003 and 0008.p to enable, rename them back to their original names to disable;
- Custom menu sounds - Rename 0005.p to enable, rename it back to 0005.p to disable.

> [!NOTE] 
> If anything pops up or you have trouble with installing the mod, send me a DM on Discord or ping me in MeltySUD or Reverse Beat Brasil, username's `yurisekina` .