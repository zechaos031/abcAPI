---
__abcAPI__

- __The official module for the arcane-botcenter.xyz's API__

---

##### Example:
    
```js
const abcAPI = require('abcapi');

const { Client } = require('discord.js'),
    client = new Client();

client.login(BotToken);

client.on('ready',() =>{
    abcAPI.login(AbcToken, client.user.id); // => require to use this module, log in to abcapi
    abcAPI.update(client); //=> made update every minutes
    abcAPI.post(client); //made simple post to this abcapi

});
```

___

