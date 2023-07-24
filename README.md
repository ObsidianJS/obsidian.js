<p align="center">
  <img width="60%" align="center" src="https://github.com/obsidianjs/obsidian.js/assets/90880784/2b4ed06e-8973-4d5b-baa4-c4c8d91c3d85">
</p>

```ts
import { Client, GatewayIntents, GatewayEvents } from "obsidian.js";

const client = new Client({ intents: [GatewayIntents.Guilds] });

client.on(GatewayEvents.Ready, (user) => {
  console.log(`Ready! Logged in as: ${user.tag}`);
});

client.login("Your bot token");
```
Check [examples](https://example.com) for more examples
<hr>

## Installation

NodeJS 16.16.0 or higher is required

```sh
npm install obsidian.js
```
