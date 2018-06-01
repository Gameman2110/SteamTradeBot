# SteamTradeBot
This project is an opensource tradebot that should make tradebots available for everyone. If you are a big trading website, if you are a small trader on your spare time, if you are a youtuber with lots of trade offers. This is for everyone. There is 8 simple steps to set it up, then you should be good to go. We have an UI that is lived updated with the offers recieved. 


## Why use a steambot?
Well, there are many reasons why you should use and develope a steambot. Maybe you have a big inventory and want to do all the trades automatic. This is where the this steambots truely shines. The bot is getting the prices that are updated realtime from the steam servers. Or let's say that you want to make a trading website or a gambling website? These site are based on steambots. But we believe in a simple solution without complicated code or logs in the console. 

## How do I set it up?
We try to focus a lot on setup and installation for the bot for the people that are not really in to coding or thinks it's complicated.
Here is what you have to do:

1. Download the zip file, press on the green button that says "Clone or download" and download it as a .zip file. 
2. Extract the files to another location on your computer. We recommend creating a folder called "steambot" on your desktop. 
3. Install NodeJS. Nodejs is the core of this bot. You simply need it for it to work. Here is a link: https://nodejs.org/en/
4. Install Desktop Authenticator, you dont have to but if you want it AUTOMATIC this step is REQUIRED: https://github.com/Jessecar96/SteamDesktopAuthenticator
5. Find your shared secret & identity secret. Here is a video: https://www.youtube.com/watch?v=JjdOJVSZ9Mo
6. Edit the config.json. Note that set the sharedsecret & identitysecret to the one you've got from step 5. 
7. Run install.bat
8. You're all set. You now have a steambot running on your steamaccount! 

### Withdrawing items from your bot.
If you've got the bot set to another account than your name, please fill in your Steam64ID inside the config file where ownerid is. 
(WE RECOMMEND HAVING A SEPERATE STEAM ACCOUNT FOR THE BOT AND TRADING).

### Information you may want to know
You can edit the config.json file how ever you want. Or at least the data inside it. You will have to set you steamusername, password, sharedsecret and identity secret. In here you can also set values for the trash limit or the game that the bot is focusing on. When you successfully start the program up you can edit these values from the bar at the top. 

### UI & Graphics
We are currently working hard on an updated userinterface. Here you can change values more easily without risking to mess up something. But be carefull: Changing some values like the trashlimit(for example) will make the bot act differently from default. You can read more about trashlimits here. Here is hte basics that you will find when starting it up:
 - Trades today: Here you will see the amount of trades that the bot has done today, shutting down the bot will make it reset, we are planning to fix this later.
 - Profit: Here you will see how much profit the bot has made. This will by default be set to 0.
 - Middle box: You may just see an empty little box under the "developed by" text. This section of the page will fill up when making trades. Here you can see the partner that you traded with and how much profit you've made. This is updated in realtime.
 - Navbar: You may have noticed that there is a navbar at the top left of the window. This is used for settings, shutting down, configs ect. You can mess around here.

### Trashlimit
Alright, no one wants to trade a 150€ knife for 400 cases. To prevent that we need to have a filter that removes or changes the value of small items like cases ect. There for, there is a setting for the trash limit on the skins. By default, the trashlimit is set to 0,04. Everyskin that is worth 0.04 or less will be worth 0.01 instead. There will be a setting to make it worth nothing. If you don't trade with small skins then consider making this value bigger. (We recommend 1€ for really big inventories) 

### Edit & Change main.js
If you're not an experienced developer we don't recommend changing stuff in the code. Changing stuff can make the bot act weird and maybe do bad trades or crash ect. If you are a developer the code is opensource so you can basicly edit whatever you want. If you make some major changes please send them to us and we will take a look at them and maybe add them to the main script. As I said. This bot is free to use if you make under 10.000$ per year with the bot.

### Contact
The owner of this project is OlleThunberg, if you want to join the project then please contact him on: olle.thunberg03@gmail.com. 
Everyone can contribute. Even if they are not part of the project. Just create an issue or a pull request and we will be sure to take a look at it. 
Since this project is free, we don't have any income. That means that advertising this project will mean a huge loss. If you truly want to support the project then please share it. It doesn't cost you anything, but it will make us happy.
 - OlleThunberg: olle.thunberg03@gmail.com

### Donate to the project
There is currently no way of supporting the project. This will be added later...

### License
MIT
Copyright 2018 OlleThunberg

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

