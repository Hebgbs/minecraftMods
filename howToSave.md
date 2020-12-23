# Saving any of my content from GitHub  

### General
Most, if not all of my Minecraft content will be supplied in their decompressed form. If being irresponsible by keeping everything in the default location, your `resourcepacks` directory will typically be in two places:  
|System|Directory|
|---|---|
|_Windows_|`%appdata%\.minecraft`|
|_Most else_|`$HOME/.minecraft`|

Otherwise, this content will go into your `resourcepacks` directory within the path defined for "Game Directory" of any desired Minecraft game profile.  

### Packed
Following the above advice, download and save to the path where your `resourcepacks` are at. If there are DownGit links available, use of them allow for downloading _individual directories_ from this repository as a compressed archive, similar to Planet Minecraft's downloads.  

If there are new releases of a pack, _i.e._ an update to an existing work, then the only recourse to update would be to download any packs again. A programme to use DownGit URLs could be created, but would unnecessarily waste bandwidth. If the objective is to use select packs _and_ update them as time goes on, you may be better off following the advice below.

### Unpacked
There are two methods for this:
   1. Extract the contents of this archive to a _directory_ within your game profile's `resourcepacks` path as defined above or applicable for your instance of Minecraft.
   2. Same as 1, except this time _clone_ the contents. You can use `-C` with command-line instances of Git to define the clone path, or using GUI tools (such as GitHub for Desktop) define repository path to where your profile's `resourcepacks` directory is.

If you elect for option 2 and keep your Git repositories in a _separate_ directory, use of symbolic links (should your disk partition formats support it) will allow you to remain organized while being able to use any of my content.  

However it is done, using the pack like this will allow you to update its contents from either desktop GUI or command line by pulling in new content _as it is released_ so you do not have to download and extract yourself ever again.
