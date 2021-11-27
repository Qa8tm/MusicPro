
## 🛠 Commands:
| Command | Description |
| ------ | ------ |
| `/mplay (query)` | play music from youtube |
| `/stream (radio link)` | stream a live streaming music |
| `/vplay (query)` | play video from youtube |
| `/vstream (live link)` | play video live streaming video |
| `/pause` | pause the streaming (admin only) |
| `/resume` | resume the streaming (admin only) |
| `/skip` | switch to next stream (admin only) |
| `/stop` | end the streaming (admin only) |
| `/vmute` | for mute the userbot on voice chat |
| `/vunmute` | for unmute the userbot on voice chat |
| `/volume 1/200` | adjust the volume of userbot (userbot must be admin) |
| `/playlist` | show you all the current stream list |
| `/song (query)` | download music from youtube |
| `/video (query)` | download video from youtube |
| `/userbotjoin` | invite the userbot to join group (admin only) |
| `/userbotleave` | instruct userbot to leave the group (admin only) |
| `/leaveall` | order the userbot to leave from all group (sudo only) |
| `/update` | update your bot directly without leaving telegram (sudo only) |
| `/restart` | restart your bot directly without leaving telegram (sudo only) |
| `/clean` | clean all raw files |
| `/rmd` | clean all downloaded files |
## Heroku Deployment 💜
The easy way to host this bot, deploy to Heroku, Change the app country to Europe (it will help to make the bot stable).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/hama-maqsood/muss)

## VPS Deployment 📡
Get the best Quality of streaming performance by hosting it on VPS, here's the step's:

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/ # clone the repo.
cd video-stream
pip3 install -U -r requirements.txt
cp example.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 main.py # run the bot.

# continue the host with screen or anything else, thanks for reading.
```