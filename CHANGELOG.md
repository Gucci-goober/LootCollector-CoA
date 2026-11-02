# LootCollector CoA

## 1.1.0 package (2026-11-02)

Skip this download if your sell prices already look normal, you do not use DragonUI, and your framerate stays steady through a dungeon. The version number stays 1.1.0, so the addon will not tell other players to update. Pins, sharing, and the database are unchanged.

- **Sell prices.** Bag and merchant prices were turning grey because the addon recolored fonts the game uses for those prices. They stay their normal color now.
- **DragonUI.** With DragonUI loaded, LootCollector leaves that map alone. This fixes the map art sliding left while the player arrow stayed put. Pins stay on DragonUI's map. World-map mouse-wheel zoom is off while DragonUI is loaded. Without DragonUI, zoom works as before.
- **Framerate over a long session.** Background work was rereading the whole discovery list, and the map was refreshing on a timer. That work now stays on your current zone and pauses in combat and while you are moving. Get this update if your FPS sinks over about 15–20 minutes. If it does not, this change does not affect you.
