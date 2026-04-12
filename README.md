# GTA SA Moonloader VS Code Extension — Snippet Update

This is an **add-on update** for the [GTA SA Moonloader VS Code extension by UmGeek](https://github.com/UmGeek/snippets-moonloader-for-vscode). It adds snippet coverage for two libraries that were missing from the original:

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

2. Copy `moonadditions_vehicle_component.json` and `moonplus.json` into the `snippets/` folder inside the extension directory:
   ```
   C:\Users\<YourName>\.vscode\extensions\umgeek.gtasamoonloader-0.0.2\snippets\
   ```

3. Replace the existing `package.json` in the extension root with the one from this repo:
   ```
   C:\Users\<YourName>\.vscode\extensions\umgeek.gtasamoonloader-0.0.2\package.json
   ```

4. Restart VS Code.

That's it — the new snippets will show up alongside the existing ones in any `.lua` file.

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
