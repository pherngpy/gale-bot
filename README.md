# gale-bot

# AI-Chat
```js
const AsmartChatBot = require("gale-bot");
const AIchat = new AsmartChatBot({ name: "your bot name" });

client.on("message", async message => {
  if(message.channel.id === "channel id") {
  if (!message.author.bot) {
  let reply = await AIchat.chat(message.content)
    message.channel.send(reply).catch(error => {
    return message.channel.send("this package is out of date! please update the package
    });
  }
 }
})
```
