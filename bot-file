const Discord = require("discord.js");

const TOKEN = "NDE3NjkwNjc3NDUxOTQ4MDM0.DXg-Qg.Y-4T7KSO2ykvc3nmmkty_NuTxFA";

const PREFIX = "!";


var fortunes = [
    "Joo",
    "Ei",
    "Emt",
    "Kai",
    "muuten oot homo plus easter egg :3",
];

var bot = new Discord.Client();

var servers = {};

bot.on("ready", function() {
    bot.user.setActivity("!apua")
bot.on("message", function(message) {
    console.log(message.content);
});

});

bot.on("message", function(message) {
    if (message.author.equals(bot.user)) return;

   if (!message.content.startsWith(PREFIX)) return; 
   
   var args = message.content.substring(PREFIX.length).split(" "); 
   switch (args[0].toLowerCase()) {
       case "ping": 
       message.channel.sendMessage("PONG!");
       message.channel.sendMessage(message.author.toString())
       message.channel.sendMessage(message.author.avatarURL);
       break;
       case "info": 
       message.channel.sendMessage("%testeille tämä kommandi on nyt !apua kiitos.");
       message.channel.sendMessage(message.author.toString())
       message.channel.sendMessage(message.author.avatarURL);
       break;
       case "testeille": 
       message.channel.sendMessage("%testeille !bottivastaa !ping ! muita tulossa yay");
       message.channel.sendMessage(message.author.toString())
       message.channel.sendMessage(message.author.avatarURL);
       break;
       case "geometrydash": 
       message.channel.sendMessage("Mitäs. aa joo se on PARAS PELI KOKO MAILMASSA OMG EFIFEKJOSEOJISETJIOETSIJOETSIJOETJIOETSHTEIOHETSIHOETFGFHUDGHDGHDHDGHDHDFI lol");
       message.channel.sendMessage(message.author.toString())
       message.channel.sendMessage(message.author.avatarURL); 
       break;
       case "bottivastaa":
        if (args [1]) message.channel.sendMessage(fortunes[Math.floor(Math.random() * fortunes.length)]); 

        else message.channel.sendMessage("Kirjoita kysymys ok");
            break;

      case "minecraft": 
                message.channel.sendMessage("@everyone");
                message.channel.sendMessage(message.author.toString())
                message.channel.sendMessage(message.author.avatarURL);
                break;
        case "apua": 
           message.channel.sendMessage("Commadit on:!info !bottivastaa !ping !minecraft !geometrydash ",);
           message.channel.sendMessage("Tekijä on: H7SDP XDDDD",);
           message.channel.sendMessage("INFO on: njetbotter on Tosi njet. mitä kirjoittais tähän? kerro pls! Super Master H7SDP#8332",);
		   console.log(`joku laitto apua!`);
           message.channel.sendMessage(message.author.toString())
           message.channel.sendMessage(message.author.avatarURL);
            break;

       default:
            message.channel.sendMessage("Tee !apua kiitos");
            message.channel.sendMessage(message.author.toString())
            message.channel.sendMessage(message.author.avatarURL);
   } 
            

    
});

client.login(process.env.B0T_T0KEN);
