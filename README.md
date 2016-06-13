![](icons/trayIcon@2x.png)
# electron-mini-youtube-player

This is a youtube player for Electron application.
**tested on only mac os**


**Mac OS**

![screenshot](mini-s-1.png)

![screenshot](mini-s-2.png)


Download
--------
[Download](https://www.dropbox.com/s/ld93yl43ie49ipt/Mini-darwin-x64.zip?dl=0) - Mac Os


Features
--------
- youtube api
- youtube search video
- html5 player
- app package


Getting Started
---------------
```bash
# Clone this repository
$ git clone https://github.com/gilhyun/electron-mini-youtube-player
# Go into the repository
$ cd electron-mini-youtube-player
# Install dependencies and run the app
$ npm install
$ node server.js
$ HOT=1 NODE_ENV=development ./node_modules/.bin/electron .
```

Edit api key /app/api/youtubeData.js
---------------
```bash
const youtubeKeys = [
  'YOUR_YOUTUBE_API_KEY'
]
```


Package app
---------------
```bash
$ (sudo) npm install -g webpack
$ NODE_ENV=production node package.js
---
## look ./release/darwin-x64/Mini-darwin-x64
```
