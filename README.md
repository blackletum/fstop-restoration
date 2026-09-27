## Info

This restoration is based on Portal Swarm (https://github.com/WonderlandWar/Portal-Swarm) and includes minor fixes from another F-Stop restoration. (https://github.com/honeyed-lemons/fstop--reimplementation)

## Setup Instructions

This project is fairly simple to set up. All you need is Visual Studio 2013, Alien Swarm installed, and Portal installed. (as of 9-27-2026 Portal files are included, though later this may not be the case later)
To compile it:

1. Go into the /src folder and run the setup bat
2. Open the produced .sln file and make sure you DO NOT upgrade it to Visual Studio 2022 (it can be opened with VS2022 just don't upgrade it)
3. Build all 3 projects. You'll find the produced .dll files (and the file to run it) in /game/portal/bin (not src/game)

To run this:
1. Edit gameinfo.txt so that the ""Game"  "E:\SteamLibrary\steamapps\common\SourceFilmmaker\game\hl2"" path is pointing towards your Source Filmmaker/game/hl2 path
2. Lastly, run the provided bat file in /game/portal
