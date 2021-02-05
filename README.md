# AlphaHubTrader
![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Alpha.JPG)
__AlphaHub Trader Optimus 1 & Minotaur 1 (V1_21 2/5/2021)__

![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Trader_11_16.PNG)

__Introduction:__

This App can be run on any Windows operating system machine. 
It has an easy to use GUI with interactive features and graphical displays. 

It allows automated trading via mirror trading using Quantonomy OPTMUS 1 & MINOTAUR 1 algorithms featured on the Alphahub platform.
You will need to open an account with AlphaHub to receive the daily signals and use the Trader.

https://alphahub.us/


You also need to open a free account with the Alpaca Markets brokerage. 
Eventually we will develop a Trader that can work with other brokerage accounts but the main reason we have developed the Trader for the Alpaca platform is that their API is easy to use, stable and straightfoward. They also offer their brokerage service without any fees. 

https://alpaca.markets/

More info here:

https://medium.com/@AlpacaHQ

IMPORTANT:

Please read and agree with the EULA (it is assumed that you agree if you use the Trader, if you don't agree, please don't use it) that you can find in the Main folder: alphahub-trader-github-liability-statement.pdf. 

__Installation Instructions:__

1) The App was created using MatLab but you don't need to have the MatLab software on your computer. 

However, you do need to download and install a free MatLab interpreter called MatLab RunTime (MyAppInstaller_web.exe) that you can find in the main directory. 
MatLab RunTime is needed to run MatLab executables. For version compability reasons make sure to use the MyAppInstaller_web.exe in the main directory and do not directly download MatLab Runtime from the MatLab website. 

Read the readme.txt file for further instructions.  

2) Download and install the AlphaHubTrader1_21.exe executable file (updated 2/5/2021). 
3) Put in the same folder the AlphaHubTrader1_21.exe, the splash.png and icon.ico files.
4) Create a shortcut after installation so you can launch the Trader easily. 
5) IMPORTANT: Create a folder in the C:/ directory called DataAlphaHubReader (the name needs to be exact). Download and move the file 
OPT1_C.mat and Alpha.JPG in that folder (you can find the files among the list of files in the main page). 
6) WARNING: If you want to test the paper account on Alpaca make sure you create keys for the paper account. If you then switch to the real account you need another set of keys for the real account (and same thing if you go from real to paper account). In other words, paper and real account have different sets of keys and you need to use the proper keys for the Trader to work. 
7) You can watch videos discussing the trading algorithm in more details and the Alphahub platform starting with this video:

https://www.youtube.com/watch?v=VVA-R0qbk7g&t=35s

8) Please subcribe to our Youtube channel:

https://www.youtube.com/channel/UCVQFo_2Xv-6t_KASIxEn4hw?view_as=subscriber

Setup instructions:

1) Read "Alpha Hub Trader Setup.pdf" file
2) Good Trading
3) Please report errors and bugs to giovanni@quantonomy.fund
4) Once you signup for the AlphaHub signal service you will receive an invitation to join a Discord channel where we discuss daily the performance of the algorithms and our staff offers support service on a continuous basis (well, besides when we sleep). Most of us are in the US and we are available to help members during waking hours. Please join our community and give us feedback and positive criticism. 

Note: Last update is version AlphaHubTrader1_21.exe (2/5/2021)

Fixes:
1) Trader should not crash anymore when call to Alpaca fails. 
2) Eliminated a reduntant button (Alpaca ON)
3) Added a button that allows to close manually a position (check the safe first and the press the button to close all open position manually if needed, use with care). 
4) Fixed a bug related to using paper keys on real account and viceversa. 
5) Fixed a bug related to extracting data from AlphaHub
6) Trading time for Mino 1 is adjusted automatically


__Setting up a Server to Run the Trader app:__

You don't need a server to run the app, you can do this on your computer. But renting a free server with a window OS is ideal because you don't have to worry for power outage and other problems with yur computer. 
You can download the app on the server and use a remote desktop application to check once in a while on the Trader. 

1) Read the detailed document How to set up a free AWS server to run the Trader (Optional).pdf in the main download page. 

Note for Mac Users, you need to get a microsoft Remote Desktop for the mac, here is the link:  

https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12

After first linking with the server you can dowload other remote desktop software if you prefer. 





