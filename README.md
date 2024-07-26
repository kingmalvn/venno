### VENNO Md in Termux
Simple deployment

Setup
First above all, install Termux Apk. Click Here to download.

Open Termux App info and Allow access to Files and Media:

Make sure you have Ubuntu Installed in your termux

First step below 👇👇👇

1 . Run below cmd / to Open Ubuntu in termux:

         bash start-ubuntu.sh
after Install git, ffmpeg, and curl:

      apt -y update && apt -y upgrade
      apt -y install git ffmpeg curl
run below 👇 cmd to Install nodejs:

      curl -fsSl https://deb.nodesource.com/setup_lts.x | bash - && apt -y install nodejs
Update nodejs version in termux:

      npm install -g npm@10.8.0
run below 👇 cmd to Install yarn:

      npm install -g yarn
Install pm2 in termux:

      yarn global add pm2
Clone the repository and install packages:

      git clone https://github.com/lyfe00011/whatsapp-bot-md botName
      cd botName
      yarn install --network-concurrency 1
After you clone above repo click the below 👇 Link to get your session id using pairing code

[VENNO](https://qr-hazel-alpha.vercel.app/session):

watch carefully after you get session I'd Edit below script by adding your session I'd and your number and some other necessary things

      echo "SESSION_ID = put session I'd here
      PREFIX = .
      STICKER_PACKNAME = MALVIN
      ALWAYS_ONLINE = true
      RMBG_KEY = null
      LANGUAG = en
      WARN_LIMIT = 1
      FORCE_LOGOUT = false
      BRAINSHOP = 159501,6pq8dPiYt7PdqHz3
      MAX_UPLOAD = 200
      REJECT_CALL = true
      SUDO = 263714757857
      TZ = Africa/Lagos
      VPS = true
      AUTO_STATUS_VIEW = no-dl
      SEND_READ = true
      AJOIN = true
      DISABLE_START_MESSAGE = false
      PERSONAL_MESSAGE = null" > config.env
after you edit copy all script above after you have add Your session id and the rest and paste in termux

To save, press Ctrl O then press Enter, press Ctrl X to exit.

Start the Bot: {After this, your bot should start running just copy below 👇 text and paste in termux then tap enter}

    pm2 start . --name botName --attach --time
You can leave it at this point, but if you want the bot to run even on offline mode: Do as below
Click acquire Wakelock in the Termux notification to enable it run in background. Exit both the ubuntu & Termux and that all

INCASE BOT STOP OR YOU MISTAKELY CLOSE CONNECTION FOLLOW BELOW 👇 STEP

open Termux again and copy and paste all command below 👇

first command

          bash start-ubuntu.sh
second command

         cd botName
         pm2 start . --name botName --attach --time
🛑 Stop bot:(Incase you wanna stop it):

        pm2 stop botName


## ```Connect With Me```<img src="https://github.com/0xAbdulKhalid/0xAbdulKhalid/raw/main/assets/mdImages/handshake.gif" width ="80"></h1> 
 <br> 
<p align="center">
<a href="https://wa.me/263714757857"><img src="https://img.shields.io/badge/Contact David-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="https://whatsapp.com/channel/0029Vac8SosLY6d7CAFndv3Z"><img src="https://img.shields.io/badge/Join Official Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="https://t.me/malvinking2"><img src="https://img.shields.io/badge/Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white" /><br>
<p align="center">
<img alt="Development" width="250" src="https://media2.giphy.com/media/W9tBvzTXkQopi/giphy.gif?cid=6c09b952xu6syi1fyqfyc04wcfk0qvqe8fd7sop136zxfjyn&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=g" /> </p>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
# 

<br>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

* [🧑‍💻 Follow VENNO Whatsapp Channel🧑‍💻](https://whatsapp.com/channel/0029Vac8SosLY6d7CAFndv3Z)

* [🧑‍💻 Join VENNO Telegram Group 🧑‍💻](https://t.me/malvinking2)

* [✅ Join Public Group ⚡](https://chat.whatsapp.com/C6mhOzGQqK5Lpu3y7noTOd)

  <a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
  

- *VENNO MD is not made by `WhatsApp Inc.` Sometimes or misusing the bot might `ban` your `WhatsApp account!`*
- *In that case, I'm not responsible for banning your account.*
- *Use VENNO MD at your own risk by keeping this warning in mind.*
  
  #### ```MALVIN KING PROFILE VIEWS 🧚```
![Visitor Count](https://profile-counter.glitch.me/kingmalvn/count.svg)

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>


 
