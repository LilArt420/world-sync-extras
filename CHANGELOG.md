# Changelog

## 2.0.3
Needs Ragnarok Offline 1.6.9 or later.
- 🧹 The World Sync monster fixes this mod carried until the app had them (estimated stats, drop chances, and drops for the 124 monsters that had none) are in Ragnarok Offline 1.6.9 itself, so the mod's copy (db/mob_db.yml) is gone. Checked: all 303 of its entries match 1.6.9's own table.
- With 1.6.9, the 2021 town quests no longer show doubled objectives when akreao's Eden Group 2021 rework is installed too: the app's quest loader merges a quest two mods declare.
- Acolyte training (iRO services): Alice, Laforet and the quest log named the hunts' monsters by their kRO names (Denopices, Greasles, Tibias). They now say what you see on the wreck: Dead Plankton, Weak Skeletons and Weak Soldier Skeletons.

## 2.0.2
- 👀 The Herosria siege can be seen and won: the region and garden jewels, the Jewel of Herosria, the stones and the four garden rulers were invisible, because the client had no sprite for their monster ids. Also now visible: Koko, the Episode 20 boss Rasgand, the Snow Rabbit and Melibe Slugs, the Corrupted Angel Snail, the fake Iwin soldiers, the Rgan Shaman, Varmundt's crabs and shellfish, and the Rgan transformation (System/jobname.lub, from kRO's own tables).
- 🎁 iRO Quests blocks: 249 places named an item where the server needs its number, so they gave, took or checked "item 0" instead. Rewards, deliveries and turn-ins in City Investment (Union deliveries and tokens), the street stall staffers, the 2021 town quests, Eye of the Beholder, the Overlook Water Dungeon, Criminal Activities and Gramps now use the real items.
- Tested in game on Ragnarok Offline 1.6.8: a Herosria test battle won by breaking the Jewel of Herosria; Masha's delivery request, the certificate, Ridwan's selling staffer and the unsold item mailed back on closing; Laforet's ride back to Prontera and the wreck's doors; World Sync drops and stats.

## 2.0.1
- Takes priority over akreao's Eden Group 2021 rework (`eden-rework-2021`) when both are on: World Sync Extras is applied after it, so its copy of any shared table wins.
- Both mods use iRO's official ids for the 2021 town quests (299 of them), and the server's quest loader added a quest's objectives again when two mods declared it: those quests showed each objective twice, and 51 failed with "Targets list exceeds the maximum of 3". The loader fix is on its way into the app (Flux159/rathena#74). Until it ships, the quests still complete normally; only the doubled objective lines and the server log warnings remain.

## 2.0.0
Needs Ragnarok Offline 1.6.7 or later.

### 🐍 New: the Jormungandr saga (setting `jormungandr`, on)
The World Sync: Jormungandr mod is now part of World Sync Extras, so one install brings the stories with the maps.
- Episode 20, The Undying One, start to finish (83 quests): the Ancient Ice Canyon, the Lair of the Rgans, the Sacred Roots, the Serpent's Maze, a guest in the Ice Castle (His Holiness Nadyagand), the Frozen Zone and the Nest of Small Branches, and the memorial dungeon Separated Sanctuary. Starts from Horuru in the Ice Castle (Episode 19 done, level 200+; setting `skip_ep19` lets anyone start).
- Episode 21, Age of Heroes, start to finish (101 quests, with an English quest log): a rift on Scale Island, Lunaforma and Alberta of old, the Georborg resistance, the ghost ship (memorial dungeon), two infiltrations of the cult's temple Gimle, and the giant serpent in the Snake's Resting Place. Starts from Voglinde in the Ice Castle's west wing at level 230.
- After the stories: dailies for both episodes (reset at 04:00), the memorial dungeons again every day, side stories, and the traders: Torr in the Ice Castle (Glacier and Dim Glacier enchants), and in Lunaforma the Wigner Company Exchanger, Blacksmith Sansan and Mage Lobelia.
- Doors into the Ice Castle's west wing (icecastle 230,160, 157,206 and 46,164), which rAthena's World Sync content lacks; they step aside when `entrances` is on.
- Koko's Secret Base side story (box delivery, Friederike's Kokos, the hunt for Rorohyu, the Sticky Sea memorial dungeon and its Corrupted Angel Snail) and Lalaha's four dailies.
- Ready for the Episode Valkyrie (standart-npc) to skip both episodes with their Clear Tickets, through F_WSJ_Skip20/21: that part of the Valkyrie is waiting on MondoTruth/standart-npc#118 and comes with the next standart-npc release.
- Boats, Walter sailors, the hidden ship, the small door and Nyar are real transports (rAthena's 'Travel to' guides on those cells are switched off while the block is on); Lunaforma's mercenaries, soldiers, workers, children and refugees, Alberta's Wigner house staff, the working Rgans and the Frozen Zone guardians have their own lines.

### 🏛️ New: Varmundt, Amatsu, Juno Library and Chapters 1-2 (setting `varmundt`, on)
- The Fantasy Book "Dungeon Food" (iRO quests 16667-16690).
- The Chess Garden and the Deep Abyss research (16778-16801), Rune Crowns and enchants.
- Seoyeon's Trial (3519-3523).
- Chapter 1's story from Ash Village to the Sky Fortress, with its side quests and dailies.
- The Juno Library's VR books (Issgard Crafting Contest, the Demon King's Castle, Lazrigs).
- The eroded wing of Varmundt's mansion.
- Chapter 2 "Song of the World Tree ~ Fragment of the End" (kRO update 301): the main story through Beledor, Volund Valley, Yongjirak, the Root of Death, Brimir and Ragsruth to Nirhult; Tamarin's sub-quest, nine dailies and Nirhult's Illusion; the Flame Gold Coin exchanger, Artisan Kadron, the Harvan merchant, the request board and the villagers; a warp from Volund Valley east into Muspelheim's fields; Beledor's signpost and Small Ash Tree, and the Deep Abyss's own exit back to the Chess Garden. The client has no Chapter 2 text or items, so its quests (64201-64246) are this block's own and the coins are points; kill counts, rewards, trades and Nirhult (a Feeos) are estimates.
- 200 placeholders become these NPCs. Rewards, recipes and prices that kRO doesn't publish are estimates.

### ⭐ New: Star Forest, Herosria and Ash Village (setting `star_forest`, on)
- The Star Emperor job change (iRO quests 11573-11585).
- Sanctuary Herosria's lobby services, portals, PvP dungeon blessing and gardens.
- The Herosria siege (War of Emperium: Herosria), Sundays 20:00-22:00: region jewels, arches, three gates, the four garden jewels and their rulers, and the Jewel of Herosria. The holding guild gets the gift, the Spring Jewel and the gardens. GMs can start a 30-minute test battle at the Sanctuary Manager.
- Ash Village's shops, enchants and signposts.
- 100 placeholders become these NPCs (Lala on ab_lava1 included). Prices, recipes and rewards kRO doesn't publish are estimates.

### 🛎️ New: iRO services (setting `iro_systems`, on)
- The Devil in the Box's dailies in the Clock Tower Unknown Basement (5961-5971, with the 10 Pet Mimics).
- Stall search in the Prontera and Payon markets and the Catalogue Magician.
- The Eden Group's Dungeon Teleporter.
- iRO's own services rAthena ships switched off (Keiki, Aperture, the Refining Researcher, Phelix, Izaac, Dark Luhir), placed where iRO has them; the Shadow Blacksmith, Madogear rental in Eclage and Mora, and Izlude's Increase AGI acolytes.
- The Acolytes' training ground in the Izlude Sunken Ship: Acolyte Leader Alice in the Prontera Cathedral gives kRO's three Acolyte hunts (levels 13, 18, 23) and sends you in; Laforet sends you back; the wreck's doors open between its holds and floors.
- EXP rewards and a few rules are estimates. 19 placeholders become these NPCs.

### 🎯 New: iRO Quests (seven settings, on)
The iRO Quests mod (0.1.0 was its last release) is now part of World Sync Extras, so one install brings the
stories, the quests and the NPCs:
- Bounty Boards: 314 repeatable hunts on 65 boards in 25 towns and the Illusion dungeons.
- Criminal Activities, Eye of the Beholder and the Overlook Water Dungeon.
- Gramps' weekly turn-ins at the Eden Group (184 hunts from the iRO client).
- City Investment: the City Merchant Union in 9 towns, Union Insignias, A/B/C deliveries and weekly Wanted bosses.
- Street stall staffers (City Investment): Masha of the Alberta Merchant Union gives a weekly request (a delivery, collecting an antique box from Murian or Elbury, the Bio Lab device or a hunt) that earns a Beginner, Regular or Master certificate. Ridwan turns it into a staffer that keeps a selling or buying stall open in Alberta or Prontera for 1 to 3 days, with 3 to 5 kinds of items, and mails you the zeny or the items. A stand-in: rAthena has no staffer units, so the stall is a scripted NPC on a free market cell. Bound, rented and untradable items are refused.
- The 2021 town quest chains and their dailies, from Morroc to Alberta, with the Eden Group's field mission givers.
- 48 placeholders become these NPCs, and about 140 NPCs World Sync had removed come back with their quests.
If you had installed iRO Quests on its own, remove it: World Sync Extras carries all of it now.

### 🧍 Placeholders
- 268 placeholders on the Jormungandr maps are gone, because the saga implements them for real (the list is in replaced-placeholders.txt). The Varmundt block takes over 200, the Star Forest block 100 and the iRO services block 18. Likewise 50 placeholders that iRO Quests (0.2.0 and 0.3.0) and the street stall staffers implement: the Overlook Water Dungeon signboards, the City Investment delivery recipients, the 2021 town quest chains, Murian and Elbury. 3 more (Myu, Girl, Old Man) are already scripted by rAthena. 21 placeholders for retired or online-only iRO content are left out: the Weekend Race, the Battle Pass Season 3 signboards, the Talk Like a Pirate Event 2026 hub and the Redeem Code. 73 placeholders remain, 44 of them working.

### 👾 World Sync monsters (db/mob_db.yml, until the app ships the same fixes)
- 124 monsters that drop nothing but their card (Divine Pride lists no drops for them, e.g. the 460 Yorkers on jor_base) get the drops of their closest relative: their base form for the Strong variants, else a monster on the same map, else the same class and level.
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
