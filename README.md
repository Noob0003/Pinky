## Thanks for Everything.
### We will always remember you jk lol..

<div align="center">
  <img border-radius: 30px src="https://i.imgur.com/qiOJVHs.jpeg" width="400" height="250"/>
  <p align="center">
<a href="#"><img title="senpai" src="https://img.shields.io/badge/HARI-pink?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="https://chat.whatsapp.com/Ioo8xNPBfEcADzPkdvkfvo"><img title="join support" src="https://img.shields.io/badge/join_support-afnanplk/pinkymwol?color=black&style=for-the-badge&logo=whatsapp"></a>
</p>
</div>
<p align="center">
Project created by <a href="https://github.com/HARI-SANTH">Hari</a> to make it public
<p align="center">
Project edited by <a herf="https://github.com/noob0003">noob</a> lol
    <br>
       | © |
        Reserved |
    <br> 
</p>

----

  <p align="center">
  <a href="https://github.com/HARI-SANTH/AlexaV1 ">
    


## Setup
<div align="center">

  ### Simple Method
  
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/HARI-SANTH/Pinky)



<br>
<br >
If Repl.it not working Try Termux for Qr scanning.Just Copy the Link Below in Termux
```
bash <(curl -L https://t.ly/tHxh)
``` 

## F.A.Q
Answer a few frequently asked questions;
### Can you read my messages?
This project is open source so all the codes are clear. Neither less nor more; you can look what you want. **We absolutely do not have access to your accounts.**

### What about our security?
If you are concerned about security, you can install it on your own computer. If you think someone else has captured your data, simply click on **Whatsapp> Three Dots> Whatsapp Web> Logout** from all sessions button.

### Is it paid?
**Of course not.** It will never happen. But you can donate to us. You can reach me via [Telegram](https://t.me/fusuf) .

### ⚠️ Warning! 
```
Due to Userbot; Your WhatsApp account may be banned.
This is an open source project, you are responsible for everything you do. 
Absolutely, Asena executives do not accept responsibility.
By establishing the Asena, you are deemed to have accepted these responsibilities.
```
  
## Developers
  <div align="center">
    
  [![Farhan-Dqz](https://github.com/farhan-dqz.png?size=100)](https://github.com/farhan-dqz) |  [![TOXIC4L!3N](https://github.com/Alien-alfa.png?size=100)](https://github.com/AI-VIKI) | [![afnanplk](https://github.com/afnanplk.png?size=100)](https://github.com/afnanplk) 
----|----|----
[farhan-dqz](https://github.com/farhan-dqz)  | [TOXIC4L!3N](https://github.com/AI-VIKI) | [afnanplk](https://github.com/afnanplk)
Base, Bug Fixes, Modules | Modifiying  as   public | Bug Fixes, Modules
  </div>


## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark
  
### thanks for your help and support guys
    `saidalli, amal ser,hari,  ichu, karthik, lyf, farhan, ihsan, hyper, muhsin, sahal, cherry 🥰🥰, plk`

### when forking 
```
add your own heroku button
  
  example :
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/afnanplk/Pinky)
  

  change it into your repo link
```
  
```
 If you want add bgm (voice auto reply),sticker (auto reply)

 create 3 files name them bgmone,bgmtwo,stick
 upload your mp3/sticker to created folder

 open plugins/filter.js , change path    
     for bgm one 
        change line 133 in filter.js to 

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmone/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true}) //dont forget to add in const array ['mp3 name']
    
     for bgm two
        change line 165 in filter.js into

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmtwo/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['mp3 name']

    for sticker
        change line 193 in filter.js

          await message.client.sendMessage(message.jid, fs.readFileSync('./stick/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['sticker name']
```
