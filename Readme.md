
# Scan Qr to Get Session Id here 
<a href="https://subxscanqr-0717cb77daed.herokuapp.com/">Tap me</a>

# Deploy on Heroku / Replit
<a href="https://dashboard.heroku.com/new-app"> Deploy on heroku</a>

## Deploy on any shell including termux

- Fork repo
- edit the config.js file as per your details
- install the following dependencies
  - ffmpeg
  - nodejs
- clone the repo
- change the directory to cloned repo
- run `npm install`
- run `npm install qrcode-terminal`
- run `npm install pm2 -g`
- run `node .`
- scan the qr
- stop bot by ctrl+c
- run `npm start` again to run it

---

# Contact Mr Fr3nk

<a href ="https://wa.me/263719647303">Whatsapp</a>

# Using SubZero Plugins

## Creating a plugin

```javascript
const { command, isPrivate } = require("../../lib/"); //importing functions

command(
  {
    pattern: "ping", //command
    fromMe: isPrivate /*need to respond for everyone's message
true : only from sudo numbers
false : from everyone
isPrivate same as false but will be considered as true if worktype is private*/,
    desc: "To check ping", //description of the command
    type: "user", //command type
  },
  async (message, match) => {
    /*


PLUGIN CONTENT HERE


*/
  }
);
```

## Sending Messages

### Replying

```javascript
message.reply("Hi");
```

### Media

```javascript
let content = "https://wallpaperaccess.com/full/5531321.jpg"; //can also use buffer
message.sendMessage(jid,
  content,
  {} /*options*/,
  "image" /*change to audio , video while sending audio or video */
);
```

### Sticker

```javascript
message.sendMessage(jid,
  "url or buffer of image or video(max 10 seconds)",
  { packname: config.PACKNAME, author: config.AUTHOR },
  "sticker"
);
```

### [External Plugins](https://github.com/X-Electra/X-Asena/wiki/Plugins)

## Any Doubts ?

[![JOIN WHATSAPP GROUP](https://raw.githubusercontent.com/Neeraj-x0/Neeraj-x0/main/photos/suddidina-join-whatsapp.png)](https://chat.whatsapp.com/ESiNt1pudB1Js6QRZtM0jg)

#### Official Image



```
MIT License

Copyright (c) 2024 SubZero Md

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
