# AlphaHubTrader

Our main website: https://www.quantonomy.fund/

![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Alpha.JPG)
__AlphaHub Trader Optimus 1 & Minotaur 1 (V1_23 4/29/2021)__

![ScreenShot](https://github.com/gsantostasi/AlphaHubTrader/blob/main/Trader_11_16.PNG)

__Performance Graphs and Stats for the Algorithms :__

Check here the performance statistics of our AlphaHub Trading Algorithms. 

Optimus1:

https://htmlpreview.github.io/?https://github.com/gsantostasi/AlphaHubTrader/blob/main/OPTIMUS1.html

Optimizer: 

https://htmlpreview.github.io/?https://github.com/gsantostasi/AlphaHubTrader/blob/main/OPTIMIZER1.html

Benchmark (for comparison), QQQ ETF (trading similar NASDAQ stocks as Quantonomy algos). QQQ is considered one of the top managed ETF in the world (we beat it easily). 

https://htmlpreview.github.io/?https://github.com/gsantostasi/AlphaHubTrader/blob/main/QQQ1.html



__Introduction:__

Check regularly for updates. Latest version is V1_23 4/29/2021. Also check the Optimizer Trader,  Optimizer V1_9 as an alternative (see below). 

Also please check our Community based AlphaHub Trader open-source solutions (different programming languages and support for other brokers):

https://github.com/alphahub-us/AlphaHub_Community_Solutions

In that repository you will find also the algorithm that our R&D company uses every day to do his own internal fund trading (so you can replicate our Trading perfectly if you use the Optimizer algo, that is the algo we use ourself):

https://github.com/alphahub-us/xylem/tree/589202bd3b0cd72fdcae69720ceb6660a884a3c8


The AlphaHub Trader App is an additional resources that we make available to our members for free . It can be run on any Windows operating system machine. 
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

2) Download and install the AlphaHubTrader1_23.exe executable file (fully stable version, updated 4/29/2021). 
3) Put in the same folder (you can name it whatever you want) the AlphaHubTrader1_23.exe, the splash.png and icon.ico files.
4) Create a shortcut after installation so you can launch the Trader easily. 
5) IMPORTANT: Create a separate (from the one where you saved the AlphaHubTrader1_23.exe file) folder in the C:/ directory called DataAlphaHubReader (the name needs to be exact). Download and move the files OPT1_C.mat and Alpha.JPG in this folder (you can find the files among the list of files in the main page). 
6) WARNING: If you want to test the paper account on Alpaca make sure you create keys for the paper account. If you then switch to the real account you need another set of keys for the real account (and same thing if you go from real to paper account). In other words, paper and real account have different sets of keys and you need to use the proper keys for the Trader to work. 
7) You can watch videos discussing the trading algorithm in more details and the Alphahub platform starting with this video:

https://www.youtube.com/watch?v=VVA-R0qbk7g&t=35s

8) Please subcribe to our Youtube channel:

https://www.youtube.com/channel/UCVQFo_2Xv-6t_KASIxEn4hw?view_as=subscriber

9) Medium article:

https://giovannisantostasi.medium.com/400-returns-in-a-1-5-years-trading-a-nasdaq-100-stock-per-day-part-1-5a1f9a27cc17

Setup instructions:

1) Read "Alpha Hub Trader Setup.pdf" file
2) Good Trading
3) Please report errors and bugs to giovanni@quantonomy.fund
4) Once you signup for the AlphaHub signal service you will receive an invitation to join a Discord channel where we discuss daily the performance of the algorithms and our staff offers support service on a continuous basis (well, besides when we sleep). Most of us are in the US and we are available to help members during waking hours. Please join our community and give us feedback and positive criticism. 

Note: Last update is version AlphaHubTrader1_23.exe (4/28/2021)

Fixes:
1) Trader should not crash anymore when call to Alpaca fails. 
2) Eliminated a reduntant button (Alpaca ON)
3) Added a button that allows to close manually a position (check the safe first and the press the button to close all open position manually if needed, use with care). 
4) Fixed a bug related to using paper keys on real account and viceversa. 
5) Fixed a bug related to extracting data from AlphaHub
6) Trading time for Mino 1 is adjusted automatically
7) Trader works now for paper and real accounts. 

NEW: OPTIMIZE BETWEEN ALGOS !

Try the AlphaHub Signals Optimizer V1_9 (AlphaHubOptm1_9.exe, see list of files above), updated on 3/08/2021.
This new algo allows to trade signals from both Algos (Mino and Opti) with user chosen weights or allows an algorithmic optmizer that chooses between the two algos based on recent performance. 
This is a very early version so use with caution (not a fully stable version yet). Use Single Stock Trader AlphaHubTrader1_23.exe for stable version. 

 Setup instructions are identical to single stock Trader. 
 
One futher addition to this Trader is a report (that you can generate via push-button). Two reports in .pdf format would be created in the DataAlphaHubReader folder described above. One report shows the real performance of your Alpaca account vs the theoretical behavior of the algos, plus some other stats relative to you real account. The second report gives stats about slippage. Slippage is defined, for buy orders, as Slippage=(Execution Price-Suggested Price)/Suggested Price *100. This is reversed for sell orders. Sometime the Trader executes the trades at higher price that the one suggested by the algos and sometime we get better entries. In average this averages out but in general we have a small positive slippage that would affect (even if not by much), over a longer period of time, the efficiency of trades. You can check the amount of slippage in your account via the report. 
Note:
The Optimizer has 2 settings Manual (that allows you to choose weights by hand) and Optimzer (that selects the predicted best algo automatically). Please use the drop-down menu' to select desired setting.  

__Help with Setting Up:__
If you need personal assistance hit me up on facebook or send me a personal message at gsantostasi@gmail.com. I would love to guide you through the above steps or give any assistance. Also please contact me if you find bugs or you have problems with the Trader. 
My facebook contact is, send me a message and add me to your friend list if you like:

https://www.facebook.com/gsantostasi/

__Setting up a Server to Run the Trader app:__

You don't need a server to run the app, you can do this on your computer. But renting a free server with a Windows OS is ideal because you don't have to worry for power outage and other problems with your computer. 
You can download the app on the server and use a remote desktop application to check once in a while on the Trader. 

1) Read the detailed document How to set up a free AWS server to run the Trader (Optional).pdf in the main download page. 

Note for Mac Users, you need to get a microsoft Remote Desktop for the mac, here is the link:  

https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12

After first linking with the server you can dowload other remote desktop software if you prefer. 




