# Changelog

## 2.0.0
Needs Ragnarok Offline 1.6.7 or later.

### 🐍 New: the Jormungandr saga (setting `jormungandr`, on)
The World Sync: Jormungandr mod is now part of World Sync Extras, so one install brings the stories with the maps.
- Episode 20, The Undying One, start to finish (83 quests): the Ancient Ice Canyon, the Lair of the Rgans, the Sacred Roots, the Serpent's Maze, a guest in the Ice Castle (His Holiness Nadyagand), the Frozen Zone and the Nest of Small Branches, and the memorial dungeon Separated Sanctuary. Starts from Horuru in the Ice Castle (Episode 19 done, level 200+; setting `skip_ep19` lets anyone start).
- Episode 21, Age of Heroes, start to finish (101 quests, with an English quest log): a rift on Scale Island, Lunaforma and Alberta of old, the Georborg resistance, the ghost ship (memorial dungeon), two infiltrations of the cult's temple Gimle, and the giant serpent in the Snake's Resting Place. Starts from Voglinde in the Ice Castle's west wing at level 230.
- After the stories: dailies for both episodes (reset at 04:00), the memorial dungeons again every day, side stories, and the traders: Torr in the Ice Castle (Glacier and Dim Glacier enchants), and in Lunaforma the Wigner Company Exchanger, Blacksmith Sansan and Mage Lobelia.
- Doors into the Ice Castle's west wing (icecastle 230,160, 157,206 and 46,164), which rAthena's World Sync content lacks; they step aside when `entrances` is on.
- The Episode Valkyrie (standart-npc) can skip both episodes with their Clear Tickets, through F_WSJ_Skip20/21.
- Boats, Walter sailors, the hidden ship, the small door and Nyar are real transports (rAthena's 'Travel to' guides on those cells are switched off while the block is on); Lunaforma's mercenaries, soldiers, workers, children and refugees, Alberta's Wigner house staff, the working Rgans and the Frozen Zone guardians have their own lines.

### 🏛️ New: Varmundt, Amatsu, Juno Library and Chapter 1 (setting `varmundt`, on)
- The Fantasy Book "Dungeon Food" (iRO quests 16667-16690).
- The Chess Garden and the Deep Abyss research (16778-16801), Rune Crowns and enchants.
- Seoyeon's Trial (3519-3523).
- Chapter 1's story from Ash Village to the Sky Fortress, with its side quests and dailies.
- The Juno Library's VR books (Issgard Crafting Contest, the Demon King's Castle, Lazrigs).
- The eroded wing of Varmundt's mansion.
- 153 placeholders become these NPCs. Rewards, recipes and prices that kRO doesn't publish are estimates.

### ⭐ New: Star Forest, Herosria and Ash Village (setting `star_forest`, on)
- The Star Emperor job change (iRO quests 11573-11585).
- Sanctuary Herosria's lobby services, portals, PvP dungeon blessing and gardens (not the siege itself).
- Ash Village's shops, enchants and signposts.
- 99 placeholders become these NPCs. Prices, recipes and rewards kRO doesn't publish are estimates.

### 🧍 Placeholders
- 268 placeholders on the Jormungandr maps are gone, because the saga implements them for real (the list is in replaced-placeholders.txt). The Varmundt block takes over 153 and the Star Forest block 99. Likewise the 5 Overlook Water Dungeon signboards, which iRO Quests implements. 215 placeholders remain, 44 of them working.

### 👾 World Sync monsters (db/mob_db.yml, until the app ships the same fixes)
- They drop again: 154 monsters had drops with no chance published, which the server gave the 0.01% floor. They now use the typical chance of the same kind of item (materials 5%, cards 0.01%, equipment 0.03-0.3%).
- 303 monsters whose stats Divine Pride doesn't show get real estimates: each missing value is the median of the 7 monsters of the same class nearest in level and HP. Before, they copied one similar monster, sometimes a boss: Yorker Worker had 207 million HP (now 27.8 million), Flameanima and Feeos 614 million (now 47 million), three Vr Cst monsters 285,340 (now 27 million), and 29 monsters such as Violen, Medjed and Tatsi hit for 0.

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
