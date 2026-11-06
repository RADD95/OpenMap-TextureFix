# OpenMap TextureFix

**OpenMap TextureFix** restores missing dungeon and cave map textures in the [OpenMap](https://github.com/openmap-world/openmap) addon when playing World of Warcraft on non-English game clients (such as Latin American Spanish `esMX`, Russian `ruRU`, etc.).

---

### Why is this needed?
In certain localized builds of the retail engine (e.g., WoW Forever), the client databases omit raw FileDataIDs for classic dungeons (such as Gnomeregan) and caves. When zooming in or navigating these maps in OpenMap, the game engine displays empty, solid bright-green tiles.

This companion addon provides all **1,224 original dungeon and cave textures** directly from local files and hooks OpenMap's texture loader so that maps display properly across all client languages.

---

### Features
* **Complete Coverage:** All 756 dungeon tiles and 468 cave tiles included.
* **Universal:** Works seamlessly with any game client locale (`esMX`, `ruRU`, `deDE`, `frFR`, etc.).
* **Safe & Non-Destructive:** Does not modify OpenMap files, so OpenMap updates will not overwrite or break this fix.

---

### Installation
1. Download the latest release `.zip` from the [Releases](../../releases) tab or CurseForge.
2. Extract the `OpenMap_TextureFix` folder into your WoW AddOns directory:
   `World of Warcraft\_forever_\Interface\AddOns\`
3. Ensure both **OpenMap** and **OpenMap TextureFix** are enabled in the in-game AddOns menu.

---

### License
MIT License.

