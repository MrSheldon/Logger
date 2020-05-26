<h2 align="center" id="Template">
  Logger
</h2>

<h3 align="center">Minimalist, dependency-free, lightning fast NodeJS logging tool</h3>

<p align="center">
      <a href="https://patreon.com/discordboats" target="_blank">
        <img src="https://img.shields.io/badge/patreon-DiscordBoats-blue.svg?logo=patreon&logoWidth=30&logoColor=F96854&style=popout-square" alt="Patreon"/>
    </a>
    <a href="https://paypal.me/roeelupo" target="_blank">
        <img src="https://img.shields.io/badge/paypal-Roee%20Lupo-blue.svg?logo=paypal&logoWidth=30&logoColor=00457C&style=popout-square" alt="PayPal"/>
    </a>
</p>

----

## Information

A minimalist, dependency-free, lightning fast logger made for https://discord.boats and my other NodeJS projects

## Showcase

![#](https://mrsheldon.me/files/70605228.png)

## Installing

Use `npm i @mrsheldon/logger`

## Usage

```js
const logger = require("../index")

const Logger = new logger({options})

Logger.warning("warning")
Logger.error("erorr")
Logger.success("success")
Logger.info("info")
```

### Option
| Name | Default Value                  | Required | Description                                |
|------|--------------------------------|----------|--------------------------------------------|
| file_save | false  | No      | Decides if it will save the errors and warnings to the file |
| file_dir | __dirname + '/logs/debug.log'  | No      | Defines where the log file will be created |

## Contributing

Contributions are always welcome to this project!\
Take a look at any existing issues on this repository for starting places to help contribute towards, or simply create your own new contribution to the project.

Please make sure to follow the existing standards within the project such as code styles, naming conventions and commenting/documentation.

When you are ready, simply create a pull request for your contribution and I will review it whenever I can!

### Donating

You can also help me and the project out by contributing through a donation on PayPal or by supporting me monthly on my Patreon page.
<p>
    <a href="https://patreon.com/discordboats" target="_blank">
        <img src="https://img.shields.io/badge/patreon-DiscordBoats-blue.svg?logo=patreon&logoWidth=30&logoColor=F96854&style=popout-square" alt="Patreon"/>
    </a>
    <a href="https://paypal.me/roeelupo" target="_blank">
        <img src="https://img.shields.io/badge/paypal-Roee%20Lupo-blue.svg?logo=paypal&logoWidth=30&logoColor=00457C&style=popout-square" alt="PayPal"/>
    </a>
</p>

## Issues
If you have an issue, please create a GitHub issue here to report the situation, include as much detail as you can!
