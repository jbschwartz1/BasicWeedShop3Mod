Foreword:
 Please play the game organically before altering the mechanics. The developers have put a lot of effort into making this game balanced and enjoyable.  I believe it’s important, not only out of respect to the developers, but in the spirit of gaming, to play the game as the developers intended for a reasonable amount of time. 

I have on several occasions, on different accounts, put hundreds of hours into the game. I find it fun and relaxing; however, I must admit that the early game grind got a little stale, so out of curiosity this mod was created. Below there will be a brief explanation on how to install the mod and the functionality therein.
A special shoutout to Andreas Pardeike, without him this would be much more technically challenging.
To learn more about Harmony, go to: https://github.com/pardeike/Harmony

Prerequisites:
1)	A basic understanding of computer filesystem architecture and the ability to modify directories
2)	A PURCHASED copy of Weed Shop 3 from https://bestweed.games or directly through steam.
3)	A fresh copy of BepInEx from https://github.com/BepInEx/BepInEx
4)	A copy of the ModMenu from https://github.com/jbschwartz1/BasicWeedShop3Mod
5)	A copy of dnSpy from https://github.com/dnSpy/dnSpy so you can view and modify the .dll source code.

Installation:
1)	Navigate to your Steam Apps directory (EX: C:\Program Files (x86)\Steam\steamapps\common)
2)	Right click Weed Shop 3, click copy, and paste it into the common folder. You should now have two copies of Weed Shop 3. One will be named Weed Shop 3 – Copy. If you corrupt your game, delete the Weed Shop 3 folder and rename Weed Shop 3 – Copy to Weed Shop 3
 ![image](https://user-images.githubusercontent.com/96957069/173198282-c394612a-964d-4933-b19a-0a037bd33e4d.png)
3)	Navigate to your Temp directory (EX: C:\Users\YOUR_USERNAME\AppData\LocalLow\Weed Games\Weed Shop 3 and copy the contents of this folder to a safe and easy-to-remember location. This is your Auto-Save data. 
4)	Extract the contents of BepInEx to the Weed Shop 3 root directory
 ![image](https://user-images.githubusercontent.com/96957069/173198297-9366202e-41d9-46bb-b7a1-c1e4f62b437f.png)
5)	Run your game, this is important because it generates the offsets for BepInEx
6)	Once the game has launched, quit the game.
7)	Copy the Mod.dll file into your ../BepInEx/Plugins folder 
![image](https://user-images.githubusercontent.com/96957069/173198313-9c12720a-6d09-4e80-9194-c5c1b063c3c0.png)
8)	Start the game! The plugin is now ready to use! You can add multiple plugins to this folder but be careful because if two plugins try to access the same IL instructions, it could crash the game and potentially corrupt your save file! Enjoy!
a.	If you notice any errors with the game, simply delete the BepInEx folder and reapply the patch. If you experience continued issues, use the backup copy of the game referenced above.

Using the Mod:
1)	Once the game is running and you are at your shop, click escape to open your options and navigate to the “Contents” menu (the mod will also appear on the settings and contents page). At the top left of your screen there should be a green cross, click it.
 ![image](https://user-images.githubusercontent.com/96957069/173198319-5191e0cf-cfbb-4d04-80c6-1d776f584ff6.png)
2)	The Mod has five features (likely to increase in future updates). 
 ![image](https://user-images.githubusercontent.com/96957069/173198326-e4ab661e-5558-48db-94e1-2a622378bd8d.png)
a.	The features are:
i.	Bonus XP, which is calculated as XP x (MULTIPLIER x 2)
ii.	Bonus Cash, which is calculated as (Cash Earned on Sale + (10,000 * MULTIPLIER)
iii.	Bonus Yield, which increases the amount of weed generated while the plant is growing (based on MULTIPLIER). If paired with Speed up Grow, you will see a rapidly growing plant. Depending on the strain, the CUMULATIVE yield will cap out at 1500G and then return to normal yield calculations.
iv.	Speed up Grow, which will speed up the rate the plant grows. If used without Bonus Yield, the final yield should be close to what the normal plant would offer.
v.	Boost Speed, which is a ‘lite’ speed hack.
3)	That’s it! Enjoy! If you have any feature requests or encounter any bugs, feel free to reach me on the Weed Shop 3 Discord, comment on the Steam Guide or make an issue on Github. Cheers!
