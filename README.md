[![npm](https://img.shields.io/npm/v/aflb.svg)](https://www.npmjs.com/package/aflb)
[![npm](https://img.shields.io/npm/dt/aflb.svg?maxAge=3600)](https://www.npmjs.com/package/aflb)
[![install size](https://packagephobia.now.sh/badge?p=aflb)](https://packagephobia.now.sh/result?p=aflb)

 
[![NPM](https://nodei.co/npm/aflb.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/aflb/)

# AFLB

![aflb](https://cdn.discordapp.com/attachments/814183405901053992/894023623990468618/aflb_banner.png)

## Installation
```
npm i aflb
```
Huge anime action gifs with no external dependencies.

### Action Gifs

| Function | Description |
| -------- | ----------- |
| `angry` | Gets a URL of a angry image/gif |
| `baka` | Gets a URL of a baka image/gif |
| `bite` | Gets a URL of a bite image/gif |
| `bloodsuck` | Gets a URL of a bloodsuck image/gif |
| `blush` | Gets a URL of a blush image/gif |
| `bored` | Gets a URL of a bored image/gif |
| `cheek` | Gets a URL of a cheek image/gif |
| `clap` | Gets a URL of a clap image/gif |
| `cringe` | Gets a URL of a cringe image/gif |
| `cry` | Gets a URL of a cry image/gif |
| `dance` | Gets a URL of a dance image/gif |
| `drink` | Gets a URL of a drink image/gif |
| `facedesk` | Gets a URL of a facedesk image/gif |
| `fight` | Gets a URL of a fight image/gif |
| `happy` | Gets a URL of a happy image/gif |
| `hate` | Gets a URL of a hate image/gif |
| `highfive` | Gets a URL of a highfive image/gif |
| `horny` | Gets a URL of a horny image/gif |
| `kill` | Gets a URL of a kill image/gif |
| `hand` | Gets a URL of a hand image/gif |
| `laugh` | Gets a URL of a laugh image/gif |
| `lick` | Gets a URL of a lick image/gif |
| `lurk` | Gets a URL of a lurk image/gif |
| `meow` | Gets a URL of a meow image/gif |
| `nom` | Gets a URL of a nom image/gif |
| `feed` | Gets a URL of a feed image/gif |
| `hug` | Gets a URL of a hug image/gif |
| `nuzzle` | Gets a URL of a nuzzle image/gif |
| `kiss` | Gets a URL of a kiss image/gif |
| `pat` | Gets a URL of a pat image/gif |
| `tickle` | Gets a URL of a tickle image/gif |
| `poke` | Gets a URL of a poke image/gif |
| `smug` | Gets a URL of a smug image/gif |
| `stare` | Gets a URL of a stare image/gif |
| `panic` | Gets a URL of a panic image/gif |
| `nya` | Gets a URL of a nya image/gif |
| `pout` | Gets a URL of a pout image/gif |
| `run` | Gets a URL of a run image/gif |
| `sad` | Gets a URL of a sad image/gif |
| `sake` | Gets a URL of a drink sake image/gif |
| `shoot` | Gets a URL of a shoot image/gif |
| `sip` | Gets a URL of a sip tea image/gif |
| `slap` | Gets a URL of a slap/punch/hit image/gif |
| `sleep` | Gets a URL of a sleep image/gif |
| `smile` | Gets a URL of a smile image/gif |
| `smoke` | Gets a URL of a smoke image/gif |
| `steal` | Gets a URL of a steal image/gif |
| `stockings` | Gets a URL of a stockings image/gif |
| `sweeties` | Gets a URL of a sweeties image/gif |
| `wasted` | Gets a URL of a wasted image/gif |
| `wave` | Gets a URL of a wave image/gif |
| `tease` | Gets a URL of a wave image/gif |
| `wink` | Gets a URL of a wink image/gif |
| `sex` | Gets a URL of a (NO NSFW) sex image/gif |
| `cuddle` | Gets a URL of a cuddle image/gif |

## Examples

Await/Async example
```js
const aflb = require('aflb');
async function getKissImage() {
  console.log(await aflb.kiss());
}
getKissImage();
```
returns:
```json
"https://cdn.discordapp.com/attachments/820213553540759571/894020186611548230/kiss_01.gif"
```

Standart Usage
```js
const aflb = require('aflb');

console.log(aflb.hug())

```
returns:
```json
"https://cdn.discordapp.com/attachments/820213553540759571/894021582819835904/kiss_02.gif"
```

Usage in Embed
```js
const { MessageEmbed } = require('discord.js')
const aflb = require('aflb');

const embed = new MessageEmbed().setImage(aflb.kiss())
```
returns:
```json
"https://cdn.discordapp.com/attachments/820213553540759571/894021582819835904/kiss_02.gif"
```
![Embed Usage](https://cdn.discordapp.com/attachments/820213553540759571/894023119101120572/embed_usage.png)