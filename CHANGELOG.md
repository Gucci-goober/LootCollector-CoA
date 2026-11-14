# LootCollector CoA

## 1.1.0 package (2026-11-13)

Skip this download if sell prices are already white and the game is not freezing from Lua errors. If you already have the 2026-11-04 package, the older tooltip, chat, DragonUI, and framerate fixes are the same. The version number stays 1.1.0, so the addon will not tell other players to update. Pins, sharing, and the database are unchanged.

- **Sell prices.** The 2026-11-04 white font was never created on this client, so bag and merchant prices stayed grey. Each price now gets its own copy of the font and is set to white. Red and yellow prices, such as when you cannot afford an item, stay as they are. Get this if prices are still grey. If they are already white, this part does not affect you.
- **Freezes.** The minimap updater could throw a Lua error on every frame while loading or on a taxi, and that error spam locked the client. It now waits instead of retrying every frame, and it ignores a missing facing or a pin with no coordinates. Get this if LootCollector errors are freezing the game. If the game is not freezing, this part does not affect you.

## 1.1.0 package (2026-11-04)

Skip this download if bag and merchant sell prices already look normal, and item tooltips still show after you close the world map. Also skip if chat is already quiet, you do not use DragonUI, and your framerate stays steady through a dungeon. The version number stays 1.1.0, so the addon will not tell other players to update. Pins, sharing, and the database are unchanged.

- **Sell prices.** The last package still left bag and merchant prices grey. Those prices now use their own white font, so they stay the normal color. Get this if prices are still grey. If they already look right, this part does not affect you.
- **Tooltips.** Opening the world map could make the next item, bag, or spell tooltip disappear. The tooltip goes back to its normal parent when the map closes. Get this if tooltips vanish after you open the map. If they do not, this part does not affect you.
- **Cache chat.** The background item cache no longer prints "Queued N items," "Starting cache queue processor," or "Item cache queue is now empty." Caching still runs. Get this if those lines were filling chat. If they were not, this part does not affect you.
- **DragonUI.** With DragonUI loaded, LootCollector leaves that map alone. This fixes the map art sliding left while the player arrow stayed put. Pins stay on DragonUI's map. World-map mouse-wheel zoom is off while DragonUI is loaded. Without DragonUI, zoom works as before.
- **Framerate over a long session.** Background work was rereading the whole discovery list, and the map was refreshing on a timer. That work now stays on your current zone and pauses in combat and while you are moving. Get this update if your FPS sinks over about 15–20 minutes. If it does not, this change does not affect you.
