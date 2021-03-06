# BiggerDigger

Smart Crypto Mining Automator

Greetings everyone!
I have developed a Windows cryptomining helper application for my own needs and I decided to share it for free. It helped me, so if other people find it useful too, I would like the feedback.

![Application Screenshot](https://raw.githubusercontent.com/kevinpat5/BiggerDigger/master/BiggerDigger.png)


Main features:
--------------
1. BiggerDigger IS NOT A MINER, but a mining coordinator. It can work in 2 modes: a) Smart mining – It will periodically check WhatToMine.com and activate the optimum miner for your hardware configuration. In this way you can be sure to always mine the most profitable coin. b) Manual mining - You can select which miner to start, using a centralized convenient GUI.

2. BiggerDigger SENDS NO DATA to any remote machines. All your settings are stored in your computer.

3. You will be using only YOUR OWN WALLETS, YOUR OWN MINERS, YOUR OWN POOLS. So you'll have full control of what is mined, how it is mined and where it is deposited.

4. NO MIDDLEMEN, NO FEES, NO MINIMUM PAYOUT amounts. It's just like traditional stand-alone mining, only fully automated.

5. BiggerDigger will display your current daily, weekly and monthly revenues, automatically converted to USD or EUR (you'll have to create a FREE account on openexchangerates.org for that, in order to get your own App ID).

6. You can have multiple configurations, for different combinations of your GPUs.

7. BiggerDigger is smart enough to understand when a miner process is having problems. It will try to restart a problematic process for 3 times and then it will move on to the next optimum miner. *(If any of your miners support auto-restart, you should disable it)*

8. With just 1 click you can open the pool's stats or the wallet app for the running miner.


How to use it:
--------------

1. Unzip package to any location.

2. In 'Configs' folder there are 2 sample subfolders, 'AMD Vega64 x 2' and 'nVidia 1080ti x 4'. Each of the above folders is a different mining configuration and contains 2 files, 'settings.txt' and 'miners.txt'. You can add/delete/rename configuration subfolders to suit your needs. If you want simultaneous execution of different miners for different GPUs, you can run multiple instances of BiggerDigger, each one with different selected configuration.

3. Visit WhatToMine.com, set your preferred hardware, click 'Calculate' and copy the URL from your browser.

4. In BiggerDigger click 'Settings' and paste the URL into the corresponding placeholder.

5. For setting up your miners please click 'Miners' button of BiggerDigger and read usage notes.

6. Click 'SMART mining' and forget!

Those of you who will find it useful, please give me your feedback. 
If the interest is big enough, I will dedicate more time for further improvement. 
I already have a lot of ideas, like remote management, event notifications, etc.

There are NO DEV FEES, so any tips are welcome:

- BTC: 17kEoWmbFyhpCwmSSKcFDdikAdBFgQPMpU
- ETH: 0xAC7C8Ea339ac1A6ea7Ca82910EeAa4d48308684a
