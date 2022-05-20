# dumb-sniper
[![GitHub release]([https://img.shields.io/github/release/wieku/danser-go.svg](https://img.shields.io/github/v/release/Darmanitan/dumb-sniper.svg))](https://github.com/Darmanitan/dumb-sniper/releases/latest) [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
## Information
dumb-sniper is a sniper written in **Python** and was made with the intent to give the Minecraft playerbase a chance to get their **dream name** without the use of expensive third party sniping services or paid sniper programs. 

dumb-sniper utilizes websockets to send the raw payload as fast as possible without any overhead or down time, speed is further increased utilizing *multihtreading* with allows dumb-sniper to send many requests conccurently.

## Features
dumb-sniper aim's to provide the best *free* user experience, and due to that we try to provide the best features possible. Besides having modern speeds able to compete with even the best paid snipers, we also have:

* Custom Skin-Changing on Snipe
* Webhook functionality to send a webhook on successful snipe
* The ability to utilize/authenticate using Mojang, Microsoft or even Manual Bearers

with more coming soon!

## To-Do / Future Features
* Dynamic Offset Calculation
* NameMC Scraping (fallback droptime grabbing)
* Giftcard Sniping
* Discord Bot Queue'ing
* Ability to use multiple accounts/bearers

## Installation
### Windows
* Download **Python** from [python.org](https://www.python.org/)

* Download the latest release from the [releases](https://github.com/Darmanitan/dumb-sniper)
* Make a folder for sniping and drag the .py file into that folder
* Open a terminal and make sure you're inside of the directory (verify this by typing ``dir`` to see the contents of your folder)
* run ``py sniper.py``
* dumb-sniper will automatically create any files you need, such as your ``config.ini`` and ``accounts.txt``

### Linux
* Download **Python** using your distrobution's package manager
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; * Ubuntu/Debian: sudo apt install python3 // * Fedora: sudo dnf install python3 // * Arch Linux: sudo pacman -S python3

* Download the latest release from the [releases](https://github.com/Darmanitan/dumb-sniper)
* Make a folder for sniping and drag the .py file into that folder
* Open a terminal and make sure you're inside of the directory (verify this by typing ``ls`` to see the contents of your folder)
* run ``py sniper.py``
* dumb-sniper will automatically create any files you need, such as your ``config.ini`` and ``accounts.txt``
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Authors

- [@Darmanitan](https://www.github.com/darmanitan) // Contact me via [Discord](https://discord.com/users/855586334005002270)



## Libraries

* [Requests](https://pypi.org/project/requests/)
* [msmcauth](https://pypi.org/project/msmcauth/)
* [colored](https://pypi.org/project/colored/)
