[![Typing SVG](https://readme-typing-svg.demolab.com?font=Arial+bold&size=30&pause=1000&background=D561FF00&multiline=true&width=435&lines=Welcome+%F0%9F%98%8A+to+WenaXMD...+just+a+Star+on+my+repo+Will+Make+my+day+;Print(%22Go+Hard+or+Go+Home%22);Go+Hard+or+Go+Home.)](https://git.io/typing-svg) ```javascript
// messageCreate.js

module.exports = {
    name: 'messageCreate',
    async execute(message) {
        if (message.author.bot) return;

        const menuMessage = `📁 *GiftedMD Project Structure*
\`\`\`
GiftedMD/
├── commands/
│   ├── fun/
│   │   ├── joke.js
│   │   └── meme.js
│   ├── moderation/
│   │   ├── ban.js
│   │   └── kick.js
│   └── utility/
│       ├── ping.js
│       └── uptime.js
├── events/
│   ├── ready.js
│   └── messageCreate.js
├── config.json
├── index.js
\`\`\`

📜 *Command Categories*
- 🧩 Fun: \`!joke\`, \`!meme\`
- 🛡️ Moderation: \`!ban\`, \`!kick\`
- 🧰 Utility: \`!ping\`, \`!uptime\`

Type \`!help <command>\` for more info.`;

        message.channel.send(menuMessage);
    },
};
```