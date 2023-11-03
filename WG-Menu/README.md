# WG-Menu
An FiveM menu used for your server that needs a menu to spawn guns and heal plus other things.


# License

    WG Scripts
    Copyright (C) 2023 Ben

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [NativeUI](Included in the Dependencies folder)


## Screenshots
![Main Menu](https://i.imgur.com/jEgkCIy.png)


## Features
- Ability to spawn guns -NEEDS FIXING
- Ability to heal
- Ability to spawn cars and change seats easily
- Ability to use the menu with your mouse just click to stop spinning arround when in the menu


## Installation
### Manual
- Download the script and put it in the server directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure NativeUI
ensure wg-menu

```

## How To Use
- Use the "U" key to enter the menu
- You can change the key in the menu.lua file at line 87 and just change the 303 number key to a different one-off this website here: https://docs.fivem.net/docs/game-references/controls/
- Most things to change about the menu are inside the menu.lua file
