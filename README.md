[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_coding)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_codding_chat)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/memefi_coin_bot)


![img1](.github/images/demo.png)

> 🇪🇳 README in english available [here](README.md)

## Functionality
| Functional                                                     | Supported |
|:----------------------------------------------------------------:|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |     ✅     |
| Random sleep time between clicks                               |     ✅     |
| Random number of clicks per request                            |     ✅     |
| Support tdata / pyrogram .session / telethon .session          |     ✅     |

## [Settings](https://github.com/AlexKrutoy/MemeFiBot/blob/main/.env-example)
| Настройка                | Описание                                                                               |
|:--------------------------:|:----------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**    | Platform data from which to launch a Telegram session (stock - Android)                |
| **MIN_AVAILABLE_ENERGY** | Minimum amount of available energy, upon reaching which there will be a delay (eg 100) |
| **SLEEP_BY_MIN_ENERGY**  | Delay when reaching minimum energy in seconds (eg 200)                                 |
| **ADD_TAPS_ON_TURBO**    | How many taps will be added when turbo is activated (eg 2500)                          |
| **AUTO_UPGRADE_TAP**     | Should I improve the tap (True / False)                                                |
| **MAX_TAP_LEVEL**        | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_ENERGY**  | Should I improve the tap (True / False)                                                |
| **MAX_ENERGY_LEVEL**     | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_CHARGE**  | Should I improve the tap (True / False)                                                |
| **MAX_CHARGE_LEVEL**     | Maximum level of tap pumping (eg 5)                                                    |
| **APPLY_DAILY_ENERGY**   | Whether to use the daily free energy boost (True / False)                              |
| **APPLY_DAILY_TURBO**    | Whether to use the daily free turbo boost (True / False)                               |
| **RANDOM_CLICKS_COUNT**  | Random number of taps (eg 50,200)                                                      |
| **SLEEP_BETWEEN_TAP**    | Random delay between taps in seconds (eg 10,25)                                        |
| **USE_PROXY_FROM_FILE**  | Whether to use proxy from the `bot/config/proxies.txt` file (True / False)             |

## Installation
You can download [**Repository**](https://github.com/AlexKrutoy/MemeFiBot) by cloning it to your system and installing the necessary dependencies:
```shell
~ >>> git clone https://github.com/AlexKrutoy/MemeFiBot.git
~ >>> cd MemeFiBot

# If you are using Telethon sessions, then clone the "converter" branch
~ >>> git clone https://github.com/AlexKrutoy/MemeFiBot.git -b converter
~ >>> cd MemeFiBot

#Linux
~/MemeFiBot >>> python3 -m venv venv
~/MemeFiBot >>> source venv/bin/activate
~/MemeFiBot >>> pip3 install -r requirements.txt
~/MemeFiBot >>> cp .env-example .env
~/MemeFiBot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/MemeFiBot >>> python3 main.py

Also for quick launch you can use arguments, for example:
```shell
~/MemeFiBot >>> python3 main.py --action (1/2)
# Or
~/MemeFiBot >>> python3 main.py -a (1/2)
```

#Windows
~/MemeFiBot >>> python -m venv venv
~/MemeFiBot >>> venv\Scripts\activate
~/MemeFiBot >>> pip install -r requirements.txt
~/MemeFiBot >>> copy .env-example .env
~/MemeFiBot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/MemeFiBot >>> python main.py
```

Also for quick launch you can use arguments, for example:
```shell
~/MemeFiBot >>> python main.py --action (1/2)
# Or
~/MemeFiBot >>> python main.py -a (1/2)

#1 - Run clicker
#2 - Create session
```
