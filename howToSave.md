# Saving any of my content from GitHub  

### General
Most, if not all of my Minecraft content will be supplied in their decompressed form. If being irresponsible by keeping everything in the default location, your `resourcepacks` directory will typically be in two places:  
|System|Directory|
|---|---|
|_Windows_|`%appdata%\.minecraft`|
|_Most else_|`$HOME/.minecraft`|
    
Otherwise, this content will go into your `resourcepacks` directory within the path defined for "Game Directory" of any desired Minecraft game profile.  
  
### Packed
Following the above advice, download and save to the path where your `resourcepacks` are at.  
  
### Unpacked
There are two methods for this:
   1. Extract the contents of this archive to a _directory_ within your game profile's `resourcepacks` path as defined above or applicable for your instance of Minecraft.
   2. Same as 1, except this time _clone_ the contents. You can use `-C` with command-line instances of Git to define the clone path, or using GUI tools (such as GitHub for Desktop) define repository path to where your profile's `resourcepacks` directory is.
  
If you elect for option 2 and keep your Git repositories in a _separate_ directory, use of symbolic links (should your disk partition formats support it) will allow you to remain organized while being able to use any of my content.  
  
However it is done, using the pack like this will allow you to update its contents from either desktop GUI or comand line by pulling in new content _as it is released_ so you do not have to download and extract yourself ever again.
