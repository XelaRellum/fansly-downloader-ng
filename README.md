# [Fansly Downloader / Fansly Scraper ](https://github.com/Avnsx/fansly)
![Downloads](https://img.shields.io/github/downloads/Avnsx/fansly/total?color=0078d7&label=🔽%20Downloads.exe&style=flat-square) ![Compatibility](https://img.shields.io/static/v1?style=flat-square&label=%F0%9F%90%8D%20Python&message=3.6%2B&color=blue) [![Discord](https://img.shields.io/discord/522310203828338701?color=6A7EC2&label=Discord&logo=discord&logoColor=ffffff&style=flat-square)](https://discord.gg/Dr8wt84z2E) ![Stars](https://img.shields.io/github/stars/Avnsx/fansly?style=flat-square&label=⭐%20Stars&color=ffc83d)

![UI Banner](https://i.imgur.com/EhL42m3.jpg)
## Description:
On click code, to scrape your favorite fansly creators media content. After you've ran the code, it'll create a folder named ``CreatorName_fansly`` in the same directory you launched the code from. That folder will have two sub-folders called Pictures & Videos, which will contain the downloaded content sorted into them.
This is pretty useful for example; if you dislike the website theming and would like to view the media on your local machine instead. This code does not bypass any paywalls & no end user information is collected during usage.
## Installation
You can just install the [Executable version](https://github.com/Avnsx/fansly/releases).
Else you'll need to install python (ticking pip in installer) and paste below in ``cmd.exe``.

	pip install requests loguru imagehash pillow
or you can use [``requirements.txt``](https://github.com/Avnsx/fansly/blob/main/requirements.txt) to install the requirements above.
## How To
1. If you have Python installed download the GitHub repository, else use the [Executable version](https://github.com/Avnsx/fansly/releases)
2. Make sure you have registered an account on fansly and are logged in with it in your browser, or you'll not be able to get an authorization token from Developer Console.
3. Go to whatever creator's account page and open your browsers developer console (Most often Key: F12)
4. Reload the website by using the rotating arrow symbol to the left of your browsers search bar(Key: F5), while the developer console is open. Now do the steps on the following picture:
5. ![GitHub Banner](https://i.imgur.com/X2L9XFo.png)
6. Now paste both of the strings - that were on the right side of ``authorization:`` & ``User-Agent:`` - which you just copied, as shown in the picture above. Into the configuration file (config.ini) and replace the two strings with their corresponding values. (1. ``[MyAccount]`` > ``Authorization_Token=`` paste the value for ``authorization:``; 2. ``[MyAccount]`` > ``User_Agent=`` paste the value for ``User-Agent:``.
7. Replace the value for ``[TargetedCreator]`` > ``Username=`` with whatever content creator you wish.
8. Save the ``config.ini`` file(into same directory as fansly scraper) with the changes you've done to it, close it & then start up fansly scraper.

From now on, you'll only need to re-do step 7 for every future use case.

**Not enough content downloaded? Enable media previews.** (``Download_Media_Previews`` to ``True`` in the configuration file)

You can turn ``Open_Folder_When_Finished`` to ``False``; if you no longer wish the download folder to automatically open after code completion.

## FAQ
Q: "Could you add X feature or do X change?"
A: Funding or any kind of support on the project? <img src="https://cdn.betterttv.net/emote/5f5130616084af6c171975d8/3x" width="40" height="40" />

Otherwise you could always [open a pull request](https://github.com/Avnsx/fansly/pulls)

Q: "I'm lacking the brain cells, to follow basic instructions; please spoon-feed me!"
A: <img src="https://c.tenor.com/Eqzbcyujjw0AAAAd/throw-child-throw-kid.gif" width="180" height="80" />

Q: "I'm encountering an actual bug, that is actually pointing to a coding mistake."
A: Open an Issue, I'll look at it asap

## Funding
Dependent on how many people show me that they're liking the code by giving ⭐'s on this repo, I'll expand functionality & push more quality of life updates.
Would you like to help out more? Any crypto donations are welcome!

BTC: bc1q82n68gmdxwp8vld524q5s7wzk2ns54yr27flst

ETH: 0x645a734Db104B3EDc1FBBA3604F2A2D77AD3BDc5

## Disclaimer
"Fansly" or fansly.com is operated by Select Media LLC as stated on their "Contact" page. This repository (Avnsx/"fansly") and the provided content in it isn't in any way affiliated with, sponsored by, or endorsed by Select Media LLC or "Fansly". The developer(referred to: "Avnsx" in the following) of this code is not responsible for the end users actions, no unlawful activities of any kind are being encouraged. Statements and processes described in this repository only represent best practice guidance aimed at fostering an effective software usage. The repository was written purely for educational purposes, in an entirely theoretical environment. Thus, any information is presented on the condition that the developer of this code shall not be held liable in no event to you or anyone else for any direct, special, incidental, indirect or consequential damages of any kind, or any damages whatsoever, including without limitation, loss of profit, loss of use, savings or revenue, or the claims of third parties, whether the developer has advised of the possibility of such loss, however caused and on any theory of liability, arising out of or in connection with the possession, use or performance of this software. The material embodied in this repository is supplied to you "as-is" and without warranty of any kind, express, implied or otherwise, including without limitation, any warranty of fitness. This disclaimer is preliminary and is subject to revision.
##
Written with python 3.9.7 for Windows 10, Version 21H1 Build 19043.1237
