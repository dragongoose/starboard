# djs-base-handlerTS

djs-base-handlerTS is a command handler for discord.js v13.

[![GitHub issues](https://img.shields.io/github/issues/dragongoose/djs-base-handlerTS?style=for-the-badge)](https://github.com/dragongoose/djs-base-handlerTS/issues)
[![GitHub forks](https://img.shields.io/github/forks/dragongoose/djs-base-handlerTS?style=for-the-badge)](https://github.com/dragongoose/djs-base-handlerTS/network)
[![GitHub stars](https://img.shields.io/github/stars/dragongoose/djs-base-handlerTS?style=for-the-badge)](https://github.com/dragongoose/djs-base-handlerTS/stargazers)
[![GitHub license](https://img.shields.io/github/license/dragongoose/djs-base-handlerTS?style=for-the-badge)](https://github.com/dragongoose/djs-base-handlerTS/blob/master/LICENSE)

## Setup

1. Clone the repository
```bash
git clone https://github.com/dragongoose/djs-base-handlerTS.git
cd djs-base-handlerTS
```
2. Change the config to fit your needs <br />
See [Setting up the config](#setting-up-the-config) for how to do this.
3. Compile the repo
```bash
npx tsc
```

4. Run the bot
```bash
node ./build/index
```

## Setting up the config
The config is located in the `config` folder.
It has a few options you can set.
* `prefix`: The prefix for the bot.
* `token`: The token for the bot.
* `intents`: The intents for the bot.
* `verbose` (optional): Logs extra information, such as when someone interacts with the bot.
* `mongooseURI` (optional): The mongoDB url.

## Using
For information on how to use the command handler, refer to the [wiki](https://github.com/dragongoose/djs-base-handlerTS/wiki).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Help in the [wiki](https://github.com/dragongoose/djs-base-handlerTS/wiki) would be greatly appreciated also.

Please make sure to update tests as appropriate.

## License
[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)


