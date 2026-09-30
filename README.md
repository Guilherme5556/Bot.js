# Bot.js
Minecraft bot
const mineflayer = require('mineflayer')

const bot = mineflayer.createBot({
  host:TOPSQUADSERV.aternos.me
  port:
  username: 'BOTSERV',
  version: '1.12.2'
})

bot.on('login', () => {
  console.log('Bot entrou no servidor!')
})

bot.on('chat', (player, message) => {
  console.log(`${player}: ${message}`)
})

node bot-parado.js
