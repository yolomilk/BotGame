# BotGame
This is a simple Multiplayer game. It is intended that you can program your own bot and let them fight against other bots by other programmers.

How to use:
a) Without bots:
1. Open the Lobby Scene in the Scenen Folder.
2. start running the programm
3. One player is the Hoste (Play and Hoste) the other Player joins by entering the host's Ip and pressing join.
4. In the Lobby you can select your Color and your Name. You can Press join, if at least 2 Players are connected. After everyone pressed join the game starts within 3 secounds.
5. Controll your character (WASD to move and (left) Strg or Left Click to fire). The Aim is to shoot your enemys. Everyone has 3 lifes.
6. the last man standing won. Than you get placed back in the lobby.

b) With bots (not jet implemented)
1. create your C# script to controll you character (it will replace the controlls script in the IngameCharacter Prefab) and 
2. As the name you enter: "BOT:" and than the name of your bot behind it. Some code that has jet to be created will than load your bot and will replace the controlls script with your bot.
3. Watch and have fun.


Notes:
-Ignore everything in the SampleScenes Folder it is from the Lobby Example. The code is not run but it helps to understand the multiplayer stuff. It will be removed later

Last edited: 1.8.2018