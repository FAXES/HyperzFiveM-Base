# HyperzFiveM-Base
This is the most advanced and well-off Base you can get with a FiveM server!

This was originally pulled from a server I was head dev on called [Cops VS Civs RP](https://youtube.com/poogan), and which I removed a lot of the customized and paid-for resources and instead just turned it into a very solid base that anyone is free to use!

- Direct Download [here](https://hyperz.dev/fivembase1)

---

### This base includes:

- ESX with Economy Removed (It is just FXServer with a database to store phone numbers, calls, messages, tweets, etc)
- Working [Phone](https://github.com/Re-Ignited-Development/Re-Ignited-Phone) for Mumble-VOIP
- All sorts of menu's
- Sexy af [HUD](https://github.com/itz-hyperz/hyperzhuddesign-fivem)
- Similar to a knock-off PGN for custom things
- Discord Integration
- Fully Functional
- Easy Setup
- No external admin panel
- Over 200 Resources
- NO LEAKS!
- So Much More!

### Things you need to add:

- EUP (paid)
- Emergency Cars (paid (mostly))
- Paid Patreon FiveM Key (Needed for the Phone to work)
- Other optional stuff

### Known Bugs:

- ESX Like to throw errors every now and then, this doesn't appear to affect anything, and is just a slight spam in console every now and then. Just haven't had the patience or willingness to fix it, feel free to create a pull request though!
- GCPhone's camera doesn't work without screenshot-basic I believe, which is not installed in the base by default, so either get it, or don't use the camera.

---

### How to install:

- Download files from zip
- Extract to a folder
- Add [latest artifacts](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) to the "server" folder
- Download [XAMPP](https://www.apachefriends.org/index.html) (You need Apache, and MySQL when in the install wizard)
- Download [HeidiSQL](https://www.heidisql.com/download.php)
- Open HeidiSQL and setup what it asks you to
- Create a new database called `essentialmode`
- Import all SQL files from the resources in the `[esx]` folder into the SQL database **--CRUCIAL**
- Import the SQL Files from the resource**s** in the `[PHONE]` folder
- Configure your `server.cfg` & `permissions.cfg` files
- Swap out the logo in the `server-data` folder to be your server logo (96 x 96 px)
- Configure **ALL** of the resources in these folders: `[DISCORD], [Priority], [LEOCars], and [FireCars]`
- Double check your `server.cfg` file is good to go
- Configure the `StartServer.bat` file to be the current directory of your files
- Run the `StartServer.Bat` file
- You now have a working whitelisted server! (To remove whitelist, remove the `Guardian` resource)

Run into any problems? Go through the procedure again, make sure you got it right.

---

### Credits:
- Origin: [Hyperz](https://hyperz.dev/github)
- Recent Upkeep: [Nuclear](https://github.com/Nuclear15)
- Liveries & Shit: [Chris](https://github.com/RealGroddy)
- Bugs / Other: [Josh](https://github.com/joshua66553)
- All Assets are Public on [FiveM](https://forum.cfx.re/c/development/releases/7), [Github](https://github.com), [GTA5 Mods](https://gta5-mods.com), or they are Custom!
- **Good Resources:** [FAXES.TOP](http://faxes.top). Join my netflix party!

---

<p align=center>Show some ❤️ by starring this repository!</p>

---
