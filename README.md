HOW TO INSTALL??

npm i ninzamusic --save


const Bot = require('ninzamusic');
 
const musicbot = new Bot({
  Token: 'xxx',
  prefix: '!'
});
 
musicbot.start();