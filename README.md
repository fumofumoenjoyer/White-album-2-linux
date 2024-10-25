# White-album-2-linux

I copy-pasted this from a reddit comment in r/visualnovels for safekeeping, i dont remember the post so if someone knows let me know so i can give credit, dropbox files are also hosted in this repo if the dropbox link goes down.

UPDATED: I managed to get it working fully with video and everything.
Took me a while, but for the best results, use Lutris but there's a specific Wine version you need to use.
Here is the one I used: wine-ge-8-25-x86_64. Also uncheck "Enable DXVK" in runner options.
Finally, copy these 3 files from the following link and put them in your prefix > drive_c > users > {username} > Documents > Leaf > WHITE_ALBUM2 folder (You may need to run the game once to get the last two folders). If you already have existing save data, then ignore the Sys.Sav file

https://www.dropbox.com/scl/fo/fqkgfue8p57zkzjc5nz5q/h?rlkey=823n9lsjxtivlbxd00k3s8em6&dl=0

When you start a fresh New Game, you'll get a black screen, just click and it should get you past. I promise every other cinematic should work aside from the Introductory Chapter Intro. When you get into the game, sometimes it may look off, I normally go to settings and toggle it to fullscreen mode to fix the resolution and for better clarity. To test if this works, it should get you just past the Introductory Chapter while also showing the cinematic at the ending of it too. Good luck 👍

Lastly, to get the best battery you wanna lock the framerate to 30fps. If you're unable to do this via the Deck's settings, in Lutris settings for the game, go to System Options > Environmental Variables, and put in the key MANGOHUD_CONFIG, and a value of fps_limit=30, then below in command prefix put in mangohud. This is normally how I lock framerates for Lutris games 👍 enjoy the wonderful game

if it still doesnt work delete d3d9.dll from game directory and try again (this file is from the translation patch and deleting it will not show music subtitles in some scenes for example the campus festival)
