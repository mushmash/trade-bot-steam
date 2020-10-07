# SteamTradeBot :fire:
This project is an open source tradebot that should make tradebots available for everyone. If you are a big trading website, if you are a small trader in your spare time or even a YouTuber with lots of trade offers. There are 8 simple steps to set it up, then you should be good to go. We have a UI that is updated in real-time with the offers received. 

## Why use a Steam bot? :mag:
Well, there are many reasons why you should use and develop a steambot. Maybe you have a big inventory and want to do all the trades automatic. This is where this steambot truly shines. The bot is getting the prices that are updated real-time from the steam servers. Or let's say that you want to make a trading website or a gambling website? These sites are based on steambots. But we believe in a simple solution without complicated code or logs in the console. 

## How do I set it up? :heart:
We try to focus a lot on the setup and installation of the bot being simple for people that are not really into coding or think it's complicated.
Here is what you have to do:

1. Press on the green button that says "Clone or download" and download it as a .zip file. 
2. Extract the files somewhere on your computer. We recommend creating a folder called "steambot" on your desktop. 
3. Install NodeJS. NodeJS is the core of this bot. It's required for it to work. https://nodejs.org/en/
4. Install Desktop Authenticator, it's optional but if you want it to work automatically this step is REQUIRED: https://github.com/Jessecar96/SteamDesktopAuthenticator
5. Find your shared secret & identity secret. [Tutorial](https://www.youtube.com/watch?v=JjdOJVSZ9Mo)
6. Edit `config.json`. You have to set the shared secret & identity secret to the one you've got from step 5. 
7. Run `install.bat`
8. You're all set. You now have a Steam bot running on your Steam account! 

### Withdrawing items from your bot. :sunglasses:
If you've got the bot set to another account than your name, please fill in your Steam64ID inside the config file where ownerid is. 
(WE RECOMMEND HAVING A SEPARATE STEAM ACCOUNT FOR THE BOT AND TRADING).

### Information you may want to know
You can edit the config.json file however you want. Or at least the data inside it. You will have to set your Steam username, password, shared secret and identity secret. In here you can also set values for the trash limit or the game that the bot is focusing on. When you successfully start the program up you can edit these values from the bar at the top. 

### UI & Graphics :boom:
We are currently working hard on an updated user-interface. Here you can change values more easily without risking to mess up something. But be careful: Changing some values (e.g. the trashlimit) will make the bot act differently from default. You can read more about trashlimits here. Here are the basics that you will find when starting it up:
 - Trades today: Here you will see the number of trades that the bot has done today, shutting down the bot will make it reset, we are planning to fix this later.
 - Profit: Here you will see how much profit the bot has made. This will by default be set to 0.
 - Middle box: You may just see an empty little box under the "developed by" text. This section of the page will fill up when making trades. Here you can see the partner that you traded with and how much profit you've made. This is updated in real-time.
 - Navbar: You may have noticed that there is a navbar at the top left of the window. This is used for settings, shutting down, configs etc. You can mess around here.

### Trashlimit :shit:
Alright, no one wants to trade a 150€ knife for 400 cases. To prevent that we need to have a filter that removes or changes the value of small items like cases etc. Therefore, there is a setting for the trash limit on the skins. By default, the trashlimit is set to 0,04. Every skin that is worth 0.04 or less will be worth 0.01 instead. There will be a setting to make it worth nothing. If you don't trade with small skins then consider making this value bigger. (We recommend 1€ for really big inventories) 

### Edit & Change main.js :scroll:
If you're not an experienced developer we don't recommend changing stuff in the code. Changing stuff can make the bot act weird and maybe do bad trades or crash etc. If you make some major changes feel free to submit a pull request!

### Buy Me A Coffee :coffee:
BTC - 37vr1wMWdAkvph6JAzf622UmnzGYumU4Mq
ETH - 0xba30137fb2Ba34074457847b4B91Cb8C4F368c19


