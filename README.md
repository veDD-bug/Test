const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('Nzk4OTQ2NDk4MTcwNzE2MTcw.X_8a6A.uZtjTt3Bqv59O9Psg2Q6fZFciUo');
