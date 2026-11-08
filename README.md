# [Deprecated] OpenMap TextureFix

> [!IMPORTANT]
> ### ⚠️ DEPRECATED / MERGED INTO OPENMAP
> **This fix has been officially integrated directly into [OpenMap](https://github.com/openmap-world/openmap) as of version `v0.8.1` (WoW Forever).**
> 
> You no longer need to install this companion addon! Simply update **OpenMap** to version 0.8.1 or newer, and all dungeon and cave textures will load natively across all client languages.

---

### What was this?
**OpenMap TextureFix** was a companion addon created to fix the bright-green missing texture bug in OpenMap for non-English game clients (such as Latin American Spanish `esMX`, Russian `ruRU`, etc.).

Client databases for localized builds omitted raw FileDataIDs for classic dungeons (like Gnomeregan) and caves. This project gathered and packed all 1,224 missing texture tiles and seamlessly redirected OpenMap's texture queries.

With the release of OpenMap v0.8.1, these textures and fallbacks are now shipped directly in the main addon.

---

### License
MIT License.
