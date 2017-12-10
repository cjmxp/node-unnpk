##node-unnpk  

A Node JS port of [unnpk](https://github.com/YJBeetle/unnpk). Unpacks npk resources from netease games.  
    
    
**installation**  
  
> npm install node-unnpk  

or you just can clone this repo and run it

**usage**

> node unnpk file.npk

This version is more manifest-related. The Manifest (or a file with all  filenames and offsets of npk archive) is usually obtained from a game's server.   
The manifest file needs to be placed in *manifest* folder with the same name and json extension. Run unpk without arguments to see more info.  
If there is no manifest, this tool will try to guess a filename. Original unnpk project has a better mime/format detection.   
  
If you want to use manifest and forced extension-detection, type anything in 3rd argument, e.g.

> node unnpk file.npk 1

