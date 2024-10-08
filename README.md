<picture>
    <source srcset="./assets/macrocosmos-white.png"  media="(prefers-color-scheme: dark)">
    <source srcset="./assets/macrocosmos-black.png"  media="(prefers-color-scheme: light)">
    <img src="macrocosmos-black.png">
</picture>

<div align="center">

# **Bittensor Subnet 13: Data Universe** <!-- omit in toc -->
[![Discord Chat](https://img.shields.io/discord/308323056592486420.svg)](https://discord.gg/bittensor)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

---

[HF Leaderboard](https://huggingface.co/spaces/macrocosm-os/sn13-dashboard) • [Discord](https://discord.gg/bittensor) • [Network](https://taostats.io/subnets/netuid-13/) • [Research](https://bittensor.com/whitepaper) 
</div>

---

# Dynamic Desirability (Gravity)

This repository is used to store validator label preferences for Subnet 13 Data Universe. 

## Access

This repo is available to everyone for read-access. Miners can use this repo to keep their scraping procedures up to date with current desirable labels. 

***Validators must request write-access to this repo in order to submit their desirabilities! Please fill out the [request form](https://forms.gle/UMNwXxXaF96zZvgw8).***

## More Information

A in-depth guide to Dynamic Desirability (Gravity) can be found [here](https://github.com/macrocosm-os/data-universe/blob/main/docs/dynamic_desirability.md). 

Validator voting submissions are submitted as JSON files with the validator's hotkey as the file name. These are located in the [validator_preferences](https://github.com/macrocosm-os/gravity/tree/main/validator_preferences) folder. 

An example of a validator's JSON format is provided below: 
```
[
    {
        "source_name": "reddit",
        "label_weights": {
            "r/Bitcoin": 0.1,
            "r/BitcoinCash": 0.1,
            "r/Bittensor_": 0.2,
            "r/Cryptocurrency": 0.1,
            "r/Cryptomarkets": 0.1,
            "r/EthereumClassic": 0.1
        }
    },
    {
        "source_name": "x",
        "label_weights": {
            "#bitcoin": 0.1,
            "#bitcoincharts": 0.1,
            "#bitcoiner": 0.1
        }
    }
]
```

## Feedback

For questions, comments, and feedback, please contact @arrmlet (Volodymyr Truba) or @ewekazoo on Discord.
