# Changelog

## 2.2.2
Needs Ragnarok Offline 1.6.9 or later. Fixes from players' reports.
- 🗡️ **Zero Cell tunings** (Boundary and Second-Dimensional Tunings) and the **Circulation of Life upgrade** froze you on "Which one?" with nothing to click, and you had to relog. The game drops an item's dialogue as soon as it waits for an answer, so the scroll now hands the choice to a regular dialogue that waits for you. Pick the weapon, check the materials, and it converts, keeping refine, cards, grade and options. The scroll is used up only when the conversion goes through.

## 2.2.1
Needs Ragnarok Offline 1.6.9 or later. Fixes from players' reports.
- 🧪 **Zero Cell quests took experience away** instead of giving it (from base 260 the reward is billions of EXP, and the game read it as a negative number). Fixed: A Hazy Gate gives 3% of your level, the Zero Cell story 5%, each Lux or Nox daily 2% and each Vita or Ark daily 3%, as intended. The same fix covers Chapter 2's rewards, the Void rift watchers, Seoyeon's Trial and the Fantasy Growth Potions, which could do the same at high levels.
- 🌌 **Constellation Tower**:
  - The **Throne Gate** froze the second player through it (nothing happened, and logging back in didn't help) once someone else had started the fight. It now lets everyone through to Betelgeuse and his Star Chest.
  - The **Meteorite Fragments** of the 5th-floor bosses and what **Betelgeuse's Star Chest** and **Naght Sieger's remains** pay now follow your server's **drop rate** (Settings), like the monsters' own drops. The souls stay at one per chest.
- 🐍 **Episode 21**: Tris (in the serpent's egg) and Nyar (at the mana altar) froze party members who weren't on that step of the story. They now say a line and send you on.
- 💬 **Lee** (Yorskalf hunts), **Devries** and **Gregor** (Distorted Ragsruth) and the **Yongjirak** dailies opened their menu with no dialogue box; picking "Take me back to Brimir" or "Never mind" could leave you stuck. They now talk first.

## 2.2.0
Needs Ragnarok Offline 1.6.9 or later. (Prepared as 2.1.10 and published as v2.2.0.)
- 📜 **Moscovia's Banish Winter quest log**: since Ragnarok Offline 1.7.8 gave its quest IDs to the Abyss Chaser job change quest, Baba Yaga's ten steps had no title or text in the quest log. They have their English text back: Banishing Winter, the magic dust, the Dragon's Lair, the people's speech, the Csar's request and the secret medicine. By MondoTruth.

## 2.1.9
Needs Ragnarok Offline 1.6.9 or later. Fixes from players' reports.
- ⏳ **Garden of Time**: the **Functional Vending Machines** opened their menu with no dialogue box, so the Tool Dealer never opened, the storage stayed invisible and you had to relog to move again. They now talk first, and the Tool Dealer, the storage (100z) and the save point all work.
- 🌌 **Constellation Tower**:
  - The **bosses of every 5th floor** now leave **Meteorite Fragments** to everyone in the room: 2 up to floor 20, 3 from floor 25, 4 from floor 50, 5 on floor 75 (our estimate: the official amount isn't published). They used to give nothing extra.
  - **Betelgeuse's fountain** picked the wrong option: "Stir it: reroll..." had a colon, which the game reads as a separator, so it showed as two lines and everything below it moved down by one. The options are now *Reroll all stats (20 Powder)*, *Max one stat (150 Powder)*, *Seal one stat (300 Powder)*.
- 🏰 The same colon bug made the **Herosria Jewel Room** warps and the **Devil in the Box** meal choices pick the wrong line. Fixed.
- 📜 **Long menu options**: our client gives each option one line; a longer one wrapped over the next option and clicks on it picked the wrong one. The 32 menu options that didn't fit (Abyss research requests, Newt's seals, 2021 town dailies, story answers) were shortened.
- 🧪 **Zero Cell** quests gave no experience. They now give a share of your level, like Chapter 2 (estimates): A Hazy Gate 3%, the Abandoned Lab Zero Cell story 5%, each Lux or Nox daily 2%, each Vita or Ark daily 3%.
- 🧍 The **Doomk** placeholder on ve_fild05 is gone: the Abyss Chaser job change quest (in Ragnarok Offline 1.8.3) brings the real Doomk to the same spot. 71 placeholders remain, 44 of them working. By MondoTruth.

## 2.1.8
Needs Ragnarok Offline 1.6.9 or later. Fixes from players' reports.
- 🌌 **Constellation Tower, rebuilt after the official tower** (iROWiki, with the guides of servers that run it):
  - Floors now hold **2 to 14** of the old tower's monsters, a little stronger every floor, instead of always 3.
  - Every 5th floor brings one of the **old tower's real bosses**: 35 of them, from Mastering and Vocal to Baphomet, Ifrit and Beelzebub, with Divine Pride's stats. They guard the floor but you don't have to beat them to go on. Chimera, Gryphon and Retribution are back to being ordinary floor monsters.
  - No more Meteorite Powder for every floor: the monsters drop it, as officially. The **blue brazier** at the start of floors 1, 6, 11... carries the room 4 floors up for 50 powder (25 more each time). Oscar no longer opens the tower higher up.
  - After floor 50 you can fight Betelgeuse or climb on: he waits again **after floor 75**, stronger (it was 70).
  - **Betelgeuse's fountain** works as officially: his Health, Attack, Recovery, Defense and Traps each get 1-3 stars after floor 50 (3-5 after floor 75). Reroll them all (20 powder), raise one to the top (150) or seal one at 0 (300). Their sum is his strength, from 200% up to 1000%, and the more, the more his chest gives. Recovery heals him, Traps glow under your feet two seconds before they snap. The fountain and the throne gate now stand on the fountain and the door you see (they were off to the left and a few cells south).
  - The minions were swapped: **Naght Sieger** fights with four **Thorny Skeletons** (back every 15 seconds), **Betelgeuse** raises **Dead Souls**.
  - **OSC0007** trades as officially: Meteorite Fragments (50 powder, or break one into 40), the Faint Star Robe, Suit and Armor and the Signet of Star (for Naght Sieger's souls), then the Nebula gear and Stellar Signets made from them (for Betelgeuse's souls and typed powders).
  - New: **OSC0008** next to it, once you've beaten Naght Sieger or Betelgeuse, enchants the Nebula gear and the Stellar Signets with the official enchant tables.
- ⏳ **Garden of Time**: the Subspace Vending Machines' **Divine Beast's Cloak upgrade** left you stuck ("finish the task in progress", relog needed), and the **enchant** machine did nothing. Both now work in dialogue with the official tables, and the fourth machine (Circulation of Life enchants), which never showed up, is there too. The **Functional Vending Machines'** Tool Dealer opened a sell window (it looked like it sold whatever you carried); it now sells potions, wings, Magnifiers and Yggdrasil Leaves.
- 🗡️ **Zero Cell tunings** (Boundary and Dimensional Tunings that turn a +10 Encroached weapon into a Frontier or Another Dimension weapon) did nothing and froze you until a relog. They now open a dialogue that does the conversion, keeping refine, cards, grade and options.
- 🍎 **Chapter 2**: in Distorted Ragsruth's northern safe spot, Painu stood on top of the sailor who takes you to the last instance. She moved a few steps.

### Chapter 1: A Hazy Gate and the Zero Cell Sector
- 🌫️ **A Hazy Gate**: Rubiel in Ash Village had nothing to start. Once the Geffen field of the second world is open, she asks you to come and see her gate the long way: through the Land of Darkness, the red portal and the **Recon Point** (the ring of stones), which now lets you into **Rubiel's safe area**. Talk to her there, then to Minuel by the shaking crossroads. Afterwards Rubiel sells a one-hour resistance for Encroached Geffenia (base level 260, 45 Mana Rings) and Minuel one for the Ruined Valkyrie Realm (base level 230, 20 Mana Rings). Both show in your quest log; the maps stay open without them, as before.
- 🧪 **Abandoned Lab Zero Cell**: no one opened the way into the Zero Cell Sector. Robin in Ash Village now starts the investigation (base level 260, Chapter 1 and A Hazy Gate done): Erosion Zone 1, Newt, Robin's search and the trace she asks you to find. Then **Newt** at the camp in Erosion Zone 1 makes **mana resistance seals** that last one hour: one for Lux and Nox (base 260, 50 Mana Rings), a stronger one for Vita and Ark (base 270, 70 Mana Rings), and takes you into the sector you pick. Without a seal the sectors send you back to the camp, and they push you out when it runs out.
- 🧹 **Robin's dailies**: Clean Up Zero Cell Lux and Nox (300 monsters each: a Tangled Singularity and 15 Mana Rings) and Vita and Ark (100 monsters each: a Boundary Singularity and 20 Mana Rings).
- ⚔️ **Encroached weapons** dropped in Zero Cell now come with random options, like the official ones: one line always, a second and a third half the time each, from ten pools (melee, ranged and magic, one- and two-handed, critical builds), with the values players' guides list.

## 2.1.7
Needs Ragnarok Offline 1.6.9 or later.
- 🔥 **Chapter 2 redone, following the official story.** The old version skipped most of it: no instances, many people missing, and a fight with Artea's invader that respawned every time you talked to her, with nothing happening after you killed it. The new one follows the official order in nine parts (the same steps players' guides list):
  - **Call of the Guardian**: the druid twins Vedr and Varg take you into the **Crossroads of Tangled Mana**. Untie four knots of tangled mana and beat Sollith to meet El.
  - **Meeting El** and **Between Cold and Heat**: Newt, Chez, Jubilus and Beryl, Yongjirak's villagers, Chez and Dew at the Root of Death, and Tamarin's shivering Hal.
  - **The Root of Death**: Gregor's survey, Maura, Shelter Geminis and its sleepers, a frozen Harvan, Prasium and the Cradle of Fire (5 Fluffy Sparks for Samsin Harvan), Charles and Orion, and Nedim's idea.
  - **Sprout of a World's End**: Gregor and Il in Brimir's parallel snowfield (20 Shadow Wardens), and Il's feather to Ragsruth.
  - **Residents of the Tattered Root**: the pony, Violas, Sirina, Orion, Elder Heria and Painu, five Apples for the village, and Artea's **Nyrholt**: four gates of Mysterious Intruders, then the Snapdragon, which shrugs off blows until you lure it into Artea's magic circles. Then Roarin, Jasminna and the branch.
  - **A Dormant Matter**: Zero and Il (20 more Shadow Wardens) and Gregor.
  - **Seed of Heat**: Bartum, Karillon and Einhar build a heat exchanger. Maura's machine button, Orion's parts (Alpurings, Icyblasts, three frozen material piles, Ice Jelly and Frost Shards), Charles, Samsin and the baby Harvan.
  - **Distorted Ragsruth**: Devries, the lost Folnirs (bring an Apple for Violas), Painu, and the **Phantom of Nyrholt** through the Phantom of Artea. Then Devries and El, and the chapter ends.
  - If you were partway through, your story carries on from the start of the part you were in. Daily Phantom of Nyrholt replaces Nirhult's Illusion. Bartom and Karimun are now Bartum and Karillon, as in kRO.
- 🌌 **New block: the Constellation Tower** (`constellation_tower`, on by default). Betelgeuse's endless tower on Misty Island, through Oscar (base level 240+, party, every 3 days): floors of the old tower's monsters made stronger, a master every 5th floor, Naght Sieger after floor 25 and Betelgeuse at floor 50 or 70 with his fountain, and OSC0007's Nebula gear and Signets of Star. All 54 of its monsters, which the server only had commented out, with Divine Pride's stats.

## 2.1.6
Needs Ragnarok Offline 1.6.9 or later.
- 🏰 **Chapter 1, Destroy the Sky Fortress**: inside, there were no NPCs, nothing happened on the stairs, and a few soldiers stood off the platforms near the start. The fortress is a chain of floating platforms with no walkway between them, and the officers, Himmelmez and Est were all on platforms you couldn't reach. Now you clear the Legion up the outer spiral, and a stairway of light takes you onto the inner spiral. Its officers wait at its heart, and the next stairway goes down to the throne hall, where you fight Himmelmez and find Est. The **Recreated Dark Whisper** works the same way: the Legion on the outer spiral, then the stairway down to Himmelmez.
- 🥚 **Episode 21's last battle** (Snake's Resting Place) was an empty room around the serpent's egg: Tan waited in a hall you couldn't reach. Now it plays like the official one. Tris, Reinhardt and Nyar are waiting by the egg. Hold Heine's tablet up to it, and the egg hatches the Eroded Tan, whom you fight right there. No item is needed: the tablet is part of the story.
- 🕯️ **Episode 21's Secret Altar** had the same problem: its three halls don't touch, so the shamans and Nyar were out of reach. Lehar now meets you at the entrance. Clear the cult's guards and break the serpent seal on the gate at the end of the hall. A stream of mana carries you up the winding way, and a door of light at the top opens onto the altar.
- ⏳ **New block: the Garden of Time's Dimensional Prisons** (`garden_of_time`, on by default). The two gates north of the Sealing Spirit Stone never showed up, and there was nothing behind them. They now open onto the **Lake of Fire** (one of the Four Divine Beasts, once a day, drops the Hall of Life Key) and the **Hall of Life** (the Dimensional Criminal, with barrier levels 1-20, traps, the other world's illusions, sanctuary and a weekly reward). For base level 250+, in a party.

## 2.1.5
Needs Ragnarok Offline 1.6.9 or later.
- 🗡️ **Class fix for 16 iRO items.** Agni Sword, Fenrir Staff, Thorn Breaker, the Heretic Mage and Acolyte Boots, Divine Mace, Chaos Sword, Dark Chaser Boots and 8 more name whole classes ("Swordman, Thief and Merchant Classes"), but the server only let each line's first job wear them. Knights, Crusaders, Blacksmiths, Alchemists, Wizards, Sages, Priests, Monks and the rest of each line, 3rd and 4th jobs included, can equip them now. The app's own fix is on its way (Flux159/rathena#84); this carries it until then.
- 🧍 The Verkhasel placeholder on ve_fild05 is gone: Ragnarok Offline 1.7.3 brings the Shadow Cross job change quest, whose real Verkhasel stands on the same cell. 72 placeholders remain, 44 of them working.

## 2.1.4
Needs Ragnarok Offline 1.6.9 or later.
- 🌿 **Twig's Nest** dropped you into open sea at the edge of the map, where you couldn't take a step. Its entry and whole route were on cells the map blocks. It now follows the nest's real path, from its south end up to Leon and Aurelie.
- 🧊 **Drift Ice Zone**: the Rgan Bishop on the middle floe never showed up, so the run stopped after the second crossing. He's there now, and the run plays through to the white cat.
- 🐌 **Sticky Sea**: you couldn't get in, because the entry was on a blocked cell. It now follows the official route from the south tip: slugs along the way, the five lost Copos where the official ones wait, and the snail in its hollow past the cave's west tunnel.
- 👻 **Unidentified Ghost Ship**: you couldn't board, because the entry was on a blocked cell. You now go down the ship floor by floor (deck, hold, bow cabin, captain's room) through hatches that open once a floor's drowned sailors are down. Maristella waits beside the captain at the end.

## 2.1.3
Needs Ragnarok Offline 1.6.9 or later.
- 🚪 None of this mod's memorial dungeons let you in: the entrance made your solo instance, then looked for a party one. Fixed for all of them: Est's **Sky Fortress** and the **Recreated Dark Whisper** (Varmundt), Aurelie's **Separated Sanctuary**, the **Canyon Exploration** and the **Sticky Sea** (Episode 20), and the **Snake's Resting Place**, **Secret Altar**, **Serene Sanctuary** and **Unidentified Ghost Ship** (Episode 21).
- 🧊 Episode 20's **Drift Ice Zone** and **Twig's Nest** are now the official solo instances, instead of short scenes. Step through the rippling wall in the Serpent's Maze onto the drifting ice, break the cult's rituals, meet Bagot again and face Rasgand, until the white cat throws everyone out. Later, follow Lehar through Twig's Nest to find Leon, Aurelie and Nyar. Both give Sacred Cat Whiskers.
- The Separated Sanctuary moves to its own round arena (the official Isolated Sanctuary map), since Twig's Nest now uses the map it borrowed.
- The quest log points Episode 20's Twig's Nest step at Lehar, and says "Leon" where it said "Leo".

## 2.1.2
Needs Ragnarok Offline 1.6.9 or later.
- 🐍 Episode 20: after the Snake God's Nest door, Lazy sends you to Aurelie in the Ice Castle, but she wasn't there, and the story stopped. She's back where the quest log points (the inner Ice Castle lodge). A check of every story NPC found five more that were hidden at the one step they're needed, all fixed: Lehar at the castle front (going back into the canyon), Lehar in the Roots (the way down to Lazy's cave) and three Episode 21 hints.
- 🏔️ Episode 20's **Canyon Exploration** is now the official solo instance, instead of a short scene. Follow the canyon road to two suspicious Iwins, get thrown across the canyon, meet Bagot, and follow the white cat over the ridge and down a gully to a rift home. Your minimap marks the next spot.

## 2.1.1
Needs Ragnarok Offline 1.6.9 or later.
- 🏙️ City Investment's setting and the README now say it replaces akreao's **City Unity** mod. Both are the same kRO system on the same quests, insignias and NPC spots. City Unity 0.1.2 and later turns itself off while City Investment is on. To play City Unity instead, untick City Investment and restart the server; that also turns off the street stall staffers. Each mod keeps its own city contribution.

## 2.1.0
Needs Ragnarok Offline 1.6.9 or later.

### 🏷️ New: Regional items (always on)
The Regional Items mod is now part of World Sync Extras. The server knows about 3,800 items your client has no name for; they showed as "Unknown Item".
- 3,582 items get names and descriptions: about 1,700 with official text (translated from Korean or Japanese where needed), 1,380 with their own icons, the rest described from the server's data. (A stray line ending in 1,217 of these texts made the client drop the whole table; fixed, and CI now compiles every Lua table.)
- The 237 kRO-only items, all translated into English, and iRO's text for the 8 items with iRO's own abilities.
If you had Regional Items installed on its own, remove it.

### 🐍 Episode Valkyrie
standart-npc 5.0.3 brings the Episode Valkyrie's Episode 20 and 21 Clear Tickets, which skip this mod's Jormungandr stories.

### 🔨 Refine tickets
The refine certificates and [ROS] tickets get their text pointing to standart-npc's Grade Refiner ("Refine with a ticket"), which takes them in standart-npc's next release. The iRO services block's Refining Researcher is gone: it was a copy of the same switched-off rAthena NPC, stood on the same cell, and stopped at a TODO for level 5 weapons.

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
