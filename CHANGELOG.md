# Changelog

## 1.2.1
- World Sync monsters drop again: 154 of them (e.g. all of Varmundt's) had drops with no chance published, which the server gave the 0.01% floor. They now use the typical chance of the same kind of item (materials 5%, cards 0.01%, equipment 0.03-0.3%), until the app ships the same fix (db/mob_db.yml, by drop slot).

## 1.2.0
- 44 placeholders now work:
  - Storage Lockers (8): your storage, for 40 zeny like a Kafra.
  - Guild Storage Managers (9): your guild's storage, for guild members, for 200 zeny.
  - Jormungandr's Contact Points (8): touch one to register it, then travel between every point you've touched.
  - Market Guides (10): mark the market's storage, catalog and other services on your minimap.
  - Battle Pass hunting grounds' Switch Channel (6): hop to the other copy of the map, at the same spot.
  - The Inn Employee (rest for 5,000 zeny and save there), the Repairman (mend everything for 5,000 zeny) and Varmundt's Warp Elevator (pick a floor).
- Placed against every enabled mod's NPCs, so none stands on another.
- 289 World Sync monsters and 34 NPC looks get their sprites on iRO clients (System/jobname.lub): the iRO client's table doesn't name these kRO-only ones, so they showed a stand-in. Needs a kRO fallback GRF for the art.

## 1.1.0
- Needs Ragnarok Offline 1.6.6 or later.
- Entrances (setting `entrances`, off by default): 34 portals from rAthena's towns and fields into the maps World Sync fills. Only for clients that have those maps.
- 740 placeholder NPCs (was 723), regenerated for the World Sync content that shipped in Ragnarok Offline 1.6.6.

## 1.0.0
- Placeholder NPCs: the official NPCs whose logic no server data has yet, with their sprite, name and spot.
- `@npcplace`: a GM command to move any NPC and keep it there across restarts.
