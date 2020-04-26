# ShareX-Custom-Uploader
This is how to use the ShareX Custom Uploader.
**If you also want a good ShareX uploader you can use [Shutter](https://shutter.host). A guide is available down this markdown document.**

## Requirements
- Cloudflare must be enabled **and HTTPS on**.
- Must have ShareX *of course*.
- **Use only Github Pages if you have Github Pro so that people can't see your private key.**

## Original Source
[The original forum post can be found here.](https://www.nextgenupdate.com/forums/computers/886853-how-make-your-own-custom-sharex-image-uploader-custom-domain-etc.html)

## How to?
### 1.
First requirement is to have Cloudflare enabled on your website so that you can have https.
If you use Github Pages you can either use Cloudflare or Github Pages's Enforce HTTPS.
### 2.
Download the up.php file [by clicking on this link.](https://github.com/BlueGoPvP/ShareX-Custom-Uploader/raw/master/up.php)
### 3.
Change this what's in the red boxes: ![](https://i.bgpvp.xyz/slloO.png) 
### 4.
Upload to your server.
### 5.
Follow the steps on the screenshot: ![](https://i.imgur.com/J3z35jW.png)
### 6.
Enjoy your new custom uploader!

# Shutter guide:
I recommend using Shutter, it's very good and fast.
Coded in Go by [@fjah](https://github.com/fjah).
**You still need to use Cloudflare**
## [Join the discord](https://discord.gg/xdQVQ7b)
You need to join the discord server to interact with the Shutter bot.
## Interact with the bot
Once you're in the discord server, go to the #bots channel and type this command:
*domain https://subdomain.yourdomain.com
## Cloudflare
Go to your **DNS settings** and add a **Apex record**, named whatever you typed as a subdomain and the content as **34.69.120.176**
Go to your **SSL settings** and change them to **Flexible**.
## ShareX
Go back in the discord server, #bots channel, and type this command:
*sxcu https://subdomain.yourdomain.com

# Problems?
If you have any problems, you can open an issue on this repo [by clicking on this text](https://github.com/bgpvp/ShareX-Custom-Uploader/issues/new).
