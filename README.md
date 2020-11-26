# AlphaHubTrader
![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Alpha.JPG)
__AlphaHub Trader Optimus 1 & Minotaur 1 (V1_17 11/23/2020)__

![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Trader_11_16.PNG)

__Introduction:__

This App can be run on any Windows operating system machine. 
It has a easy to use GUI with interactive features and graphical displays. 

It allows automated trading via mirror trading using Quantonomy OPTMUS 1 & MINOTAUR 1 algorithms featured on the Alphahub platform.
You will need to open an account with AlphaHub to receive the daily signals and use the Trader.

https://alphahub.us/


You also need to open a free account with the Alpaca Markets brokerage. 

https://alpaca.markets/

__Installation Instructions:__

1) The App was created using MatLab but you don't need to have the MatLab software on your computer. 

However, you do need to download and install a free MatLab interpreter called MatLab RunTime (MyAppInstaller_web.exe) that you can find in the main directory. 
MatLab RunTime is needed to run MatLab executables. 
Read the readme.txt file for further instructions.  

2) Download and install the AlphaHubTrader1_17.exe executable file (updated 11/23/2020). 
3) Put in the same folder the AlphaHubTrader1_17.exe, the splash.png and icon.ico files.
4) Create a shortcut after installation so you can launch the Trader easily. 
5) IMPORTANT: Create a folder in the C:/ directory called DataAlphaHubReader (the name needs to be exact). Download and move the file 
OPT1_C.mat and Alpha.JPG in that folder (you can find the files among the list of files in the main page). 
6) You can watch videos discussing the trading algorithm in more details and the Alphahub platform starting with this video:

https://www.youtube.com/watch?v=VVA-R0qbk7g&t=35s

7) Please subcribe to our Youtube channel:

https://www.youtube.com/channel/UCVQFo_2Xv-6t_KASIxEn4hw?view_as=subscriber

Setup instructions:

1) Read "Alpha Hub Trader Setup.pdf" file
2) Good Trading
3) Please report errors and bugs to giovanni@quantonomy.fund
4) Once you signup for the AlphaHub signal service you will receive an invitation to join a Discord channel where we discuss daily the performance of the algorithms and our staff offers support service on a continuous basis (well, besides when we sleep). Most of us are in the US and we are available to help members during waking hours. Please join our community and give us feedback and positive criticism. 

Note: Last update is version AlphaHubTrader1_17.exe (11/23/2020)

Fixes:
1) Added market close/open alert (now Trader trades only when US market is open)
2) Fixed bug that capped trading at $2000 
3) Minor design fixes. 
4) Fixed Typos.
5) Now user can set max slippage for when the trader uses market order (if initial trade doesn't go through within 5 minutes)
Order will not be executed if slippage is higher than max user slippage. 
6) Fixed timing issues
8) Algo now produces an error log that is stored in the user created DataAlphaHubReader directory (send Error Log files to giovanni@quantonomy.fund). 
9) Added paper trading
10) Trader now gives access to 2 AlphaHub algorithms, OPTIMUS 1 and MINOTAUR 1
11) Added a candlestick graph for daily chosen stock


__Setting up a Server to Run the Trader app:__

You don't need a server to run the app, you can do this on your computer. But renting a free server with a window OS is ideal because you don't have to worry for power outage and other problems with yur computer. 
You can download the app on the server and use a remote desktop application to check once in a while on the Trader. 

1) Read the detailed document How to set up a free AWS server to run the Trader (Optional).pdf in the main download page. 

Note for Mac Users, you need to get a microsoft Remote Desktop for the mac, here is the link:  

https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12

After first linking with the server you can dowload other remote desktop software if you prefer. 





