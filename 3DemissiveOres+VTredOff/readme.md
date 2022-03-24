> _Heaps of redundancy to account for the `tl;dr` crowd. Sorry if this gets on your nerves but I would rather peple be angry att my writing than angry about not being able to use my mods effectively. may improve this readme in future._

# The Vanilla Tweaks problem
So this mod is basically a rehash of _several_ existing mods to make the appearance of glowing ores. Why it was made is due to Vanilla Tweaks. In spite of how good that series of mods are, sometimes other mods tend to encounter issues out of nowhere.

Consider MrJoshuaT's 3D ores. If you use this mod with Vanilla Tweaks' Unlid Redstone Ore, this mod isn't going to look that great while mining because redstone's 3D model only happens after the ore is lit — Joshua's mod has no _Off_ state to make the ore look as it should, so "Unlit" ores (`lit=false`) having a completely different model ooccurs since there's nothing to overwrite Vanilla Tweaks with.

Arguably, you can just disable the Unlit Redstone mod. _But_ why just do that when I can create entirely new Redstone ore assets expressly for use with emissive textures, _and_ use said textures for use with Joshua's 3D ores mod?

**This is what I had done.** My will has been performed to bring together unlit redstone with 3D ore models, but also to make them emissive. Check it out!

# Technical differences
This mod differs significantly through the use of parent blocks for the 3D effect, since thanks to tthe core ores in Minecraft's overworld having two different variants, this would _normally_ mean two of the same ore must exist. **This is still true.**

What didn't have to be true is up to 50 kilobytes each for two separate blocks — Parent blocks of each are included for these instances, which means while there are more models, it takes less space overall since the child blocks only require queuing the parent for its attributes while the child provides textures. So compared against Joshua's work, this should take _less_ space even with the extra models and textures.

# Installation
_Just get it._ If you do not know where this goes, there's more than enough material in this repository and elsewhere explaining such.