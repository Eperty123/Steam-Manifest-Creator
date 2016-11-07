# Steam-Manifest-Creator
Stop Steam from re-downloading your games!

# Description
If you ever had experienced Steam re-downloading your games even though you've copied all the files to to right folder then you'd know that it's
a pain to download them all over again. But guess what, SMC (Steam Manifest Creator) will fix the issue by creating the necessary manifest file for the appropriate games.

SMC will not patch, hack or download additional files that may harm your Steam account or computer. All it does is creating the manifest file for the games you already have.
This is very helpful if you have a backup copy of your games from a harddrive that you want to copy back to your Steam library.

<b>Note:</b> <i>You must have the games in your Steam account for it to work!</i>
# Language
SMC has recently been converted to c#.

# Requirements
* Visual C++ Runtime 2015 (both x86 and x64)
* Windows 7, 8, 8.1 or 10.
* Dot net 4.5.

# Documentation
<a href="https://github.com/Eperty123/Steam-Manifest-Creator/wiki/Documentation" target"_blank">See the documentation here.</a>

# Note
When creating manifests - Steam will use a lot of hdd IO due to its nature of "downloading" (verify) games. This may cause pc hang ups if not being careful with big games.

You will also notice that the game it's verifying has 0 bytes, which is very normal. Let Steam finish its work and wala.

Also SMC does not support third-party assets or DLC like Skyrim's Creation Kit. You'll have to manually search for the DLC and add it.

# Copyright
SMC uses ressources from <a href="http://iconarchive.com">Icon Archive</a>. Thanks to the authors who made the icons!

<b>I am in no way affiliated with Valve in any means. This is a hobby project.</b>

Enjoy!
