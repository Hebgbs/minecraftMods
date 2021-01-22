# InventorySense UI remixes
Original by Moxwel, changes by Hebgbs. **Read this page in its entirety** before acting: The time I've invested here is meant to save yours.

> This original work is based on 1.4.2. As this is an unaffiliated work, any specific 1.4.3 changes _may_ be reverted, though they are not likely significant enough to be of notice as the author mentioned most of the changes were not noteworthy. Nonetheless, raise an issue if something is inconsistient compared to InventorySense UI 1.4.3.

### I know what's shown below is a lot.
I'm not going to pretend you'll read all of what I've written. So here's the tl;dr version of this as "Cliff Notes" for the below:
   * `./TransparentUI` is the original work of my creation based on InventorySense UI _1.4.2_.
   * **Anything** with `clr-` in its name is **_only_** for my Transparent UI fork.
   * **Anything** with `mox-` in its name is **_only_** for Moxwel's original InventorySense UI.
   * **Anything** with either of these suffixes should **_not_** be used concurrently (at the same time).
   * `./colourRmx` only contain button colour remixes, which **_require_** the theme they are based on to be used.
   * `./clr-bookGrid` is **_only_** for my Transparent UI fork, as a tertiary / secondary theme for filling in the recipe book with dithered transparency to be used _with_ colour remixes when applicable — Match your preference!

**Colour information is present in filenames.** This is under the assumption GitZip would be used for downloading from this repository, however the DownGit URLs provided are also an option if you wish to download nothing else _and_ either do not care about how the files appear, or are willing to correct them yourself.

Should you follow my advice and use GitZip, any of my work for the transparent UI theme will use light yellow (§e), works intended for use with Moxwel's original theme will use dark green (§2) and theme colours will use whatever is the nearest approximation available — Default green colour will use light grey (§7).

Hopefully with this information, it will help you to make sense of this repository. Have fun browsing!

### How to browse with GitZip
You could use the DownGit links provided in the table within each directory — they are there as a courtesy for people who are unable or unwilling to install /use GitZip. But you should _really_ use GitZip instead if for nothing else, so the names of files provided aren't butchered in the process of downloading them. To install / use:
|Browser|URL|
|---|---|
|Chrome / Derivatives|[Chrome Web Store](https://chrome.google.com/webstore/detail/ffabmkklhbepgcgfonabamgnfafbdlkn)|
|Firefox Quantum (57+) / Derivatives|[Firefox Add-Ons](https://addons.mozilla.org/en-US/firefox/addon/gitzip/)|
|Everything else|[Web interface](https://kinolien.github.io/gitzip/)|

For the extension; Once enabled, double-click in the empty space around any directory you wish to download and it will be queued. For the web interface; Follow the provided instructions. Rate-limited? [Register for a GitHub account]() and sign in so the extension or web service can use your authorization token for easing this restriction and allow download from GitHub using GitZip. It's free, safe and easy enough.
> I'd bet my Planet Minecraft account on it — if this advice causes you any grief, let them know!

### Downloads
Moved to other pages. View additional resources by visitiing the following locations:

|Series|Repository|URL|
|---|---|---|
|Transparent UI|`TransparentUI`|[Click](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx/TransparentUI)|
|colour themes|`colourRmx`|[Click](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx/colourRmx)|
|InventorySense UI rank shift|`mox-rankShift`|[Click](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx/mox-rankShift)|
|Transparent UI recipe book grid|`clr-bookGrid`|[Click](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx/clr-bookGrid)|

Information brief about each are presented in section [Repository use](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx#repository-use) below.

### License
[Creative Commons Attribution-ShareAlike 4.0 Int'l](https://creativecommons.org/licenses/by-sa/4.0/)  
(Even though this repository _itself_ has no license, this specific work by its author uses CC BY-SA 4.0.)
  
### About
InventorySense UI by Moxwel is a very Bedrock-inspired theme which has added niceties like being able to see a _representation_ of what certain interaction blocks look like, distinction between spaces in player dialogues and OptiFine support to include certain additional GUI elements for specific entity states.  
  
This repository presents changes as I see fit, for a variety of purposes, as I please. Most of these changes will be based around VanillaTweaks modifications, the first of which will be for transparent UI.

For changes specific to Moxwel's original work, they are suffixed with `mox-` while my work with InventorySense Transparent UI is suffixed with `clr-`.

### Repository use
**Transparent UI**  
This is my fork of Moxwel's work. As it is so extensive in asset replacement, this acts as its own theme and should _not_ be used with Moxwel's work. Other works in this repository can be used with this or Moxwel's original iteration of InventorySense UI.
  
**Additions for Moxwel's InventorySense UI**
|Directory|Description|
|---|---|
|`colourRmx`|Colour remixes for Moxwel's InventorySense UI. Themes specifically for use with Moxwel's work begin their suffix with `mox-`.|
|`mox-rankShift`|Modifies villager rank medallions / trade stones so the experience bar represents progression to _next_ rank.|

**Additions for InventorySense Transparent UI**
|Directory|Description|
|---|---|
|`colourRmx`|Colour remixes for Moxwel's InventorySense UI. Themes specifically for use with my work begin their suffix with `clr-` (clear). TO learn about each theme, view  this page's [Themes](https://github.com/Hebgbs/minecraftMods/tree/master/InvSenseRmx/colourRMX/readme.md#themes) section.|
|`clr-bookGrid`|Adds a dithered grid to the recipe book, for people who think the space feels a bit empty without it. Best used with respective theme in `colourRmx` _if applicable_.|

### Load order
> These examples use directory names rather than archives, in an effort to improve high-level understanding of how these works are used concurrently.

The provided resources, used altogether should be used in the order for each respective main thme:  
**InventorySense UI**  
`mox-rankShift` (Addition with colour preference)  
`colourRmx` (Colour preference)  
`InventorySense UI v1.4.2.zip` (Theme base)  
  
**InventorySense Transparent UI**  
`clr-bookGrid` (Addition with colour preference)  
`colourRmx` (Colour preference)  
`InvSenseUI_Transparent.zip` (Theme base)  

### Supported languages (where applicable)
**All of them.** Thanks to John Meow for that.
