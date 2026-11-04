# LootCollector CoA

## 1.1.0 package (2026-11-04)

Skip this download if bag and merchant sell prices already look normal, and item tooltips still show after you close the world map. Also skip if chat is already quiet, you do not use DragonUI, and your framerate stays steady through a dungeon. The version number stays 1.1.0, so the addon will not tell other players to update. Pins, sharing, and the database are unchanged.

- **Sell prices.** The last package still left bag and merchant prices grey. Those prices now use their own white font, so they stay the normal color. Get this if prices are still grey. If they already look right, this part does not affect you.
- **Tooltips.** Opening the world map could make the next item, bag, or spell tooltip disappear. The tooltip goes back to its normal parent when the map closes. Get this if tooltips vanish after you open the map. If they do not, this part does not affect you.
- **Cache chat.** The background item cache no longer prints "Queued N items," "Starting cache queue processor," or "Item cache queue is now empty." Caching still runs. Get this if those lines were filling chat. If they were not, this part does not affect you.
- **DragonUI.** With DragonUI loaded, LootCollector leaves that map alone. This fixes the map art sliding left while the player arrow stayed put. Pins stay on DragonUI's map. World-map mouse-wheel zoom is off while DragonUI is loaded. Without DragonUI, zoom works as before.
- **Framerate over a long session.** Background work was rereading the whole discovery list, and the map was refreshing on a timer. That work now stays on your current zone and pauses in combat and while you are moving. Get this update if your FPS sinks over about 15–20 minutes. If it does not, this change does not affect you.
