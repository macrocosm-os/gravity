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
