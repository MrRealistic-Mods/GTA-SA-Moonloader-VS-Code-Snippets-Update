# GTA SA Moonloader VS Code Extension — Snippet Update

This is an **add-on update** for the [GTA SA Moonloader VS Code extension by UmGeek](https://marketplace.visualstudio.com/items?itemName=UmGeek.GTASAMoonloader). It adds snippet coverage for two libraries that were missing from the original:

- **MoonAdditions Vehicle Component API** — from the [Dante-1337 fork](https://github.com/Dante-1337/MoonAdditions/wiki/Vehicle-Component), which extends the original THE-FYP MoonAdditions with vehicle component, atomic object, and material manipulation
- **MoonPlus** — a separate library by plasmaXZ covering Placeable, Entity, Physical, Vehicle, Transmission, Gear, Sound, Ped, Game Settings, Weather, and Weapon objects

---

## What's Included

| File | Contents |
|---|---|
| `moonadditions_vehicle_component.json` | Vehicle Component API (Dante-1337 MoonAdditions update) |
| `moonplus.json` | Full MoonPlus object and function snippets |
| `package.json` | Updated extension manifest — replaces the original |

---

## How to Install

1. Make sure you already have the original extension installed. It should be located at:
   ```
   C:\Users\<YourName>\.vscode\extensions\umgeek.gtasamoonloader-0.0.2\
   ```

2. Copy the files and paste them in the extension's folder.

3. Restart VS Code.


---

## Usage Note

MoonPlus requires MoonAdditions to be loaded first in your script:

```lua
local mad = require "MoonAdditions"
local mps = require "MoonPlus"
```

---

## Links

- [Original Extension — UmGeek](https://github.com/UmGeek/snippets-moonloader-for-vscode)
- [MoonAdditions Vehicle Component (Dante-1337)](https://github.com/Dante-1337/MoonAdditions/wiki/Vehicle-Component)
- [MoonPlus Wiki](https://github.com/plasmaXZ/MoonPlus/wiki)

## Support my work
[Patreon](https://www.patreon.com/c/MrRealistic)
