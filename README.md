# 🗺️ World Sync Extras

**The playable side of World Sync, in one mod.** Ragnarok Offline brings the official maps,
monsters, spawns and warps over from the iRO and kRO clients. This mod fills them with what the
server data doesn't have: the episode stories, iRO's quests, the official NPCs and services, and
the names and descriptions of the items the server knows but your client doesn't.

Everything is grouped into **blocks**. Each block has its own setting in
**Settings → Mods → World Sync Extras**, so you can turn off anything you don't want. All are on by
default except `skip_ep19` and `entrances`.

| | Block | Setting | What you get |
|:-:|---|---|---|
| 🐍 | Jormungandr saga | `jormungandr` | Episodes 20 and 21, start to finish |
| 🌳 | Varmundt & the World Tree | `varmundt` | Chapters 1 and 2, Varmundt, Amatsu, the Juno Library |
| ⭐ | Star Forest & Herosria | `star_forest` | Star Emperor job change, Sanctuary Herosria and its siege, Ash Village |
| 🛎️ | iRO services | `iro_systems` | Devil in the Box, catalogs, Dungeon Teleporter, town helpers, Acolyte training |
| 🔨 | Refine Master | `refine_master` | Refine certificates and [ROS] tickets that actually work |
| 🎯 | iRO Quests | seven settings | Bounty Boards, City Investment, Gramps, the 2021 town quests and more |
| 🏷️ | Regional items | always on | Names, descriptions and icons for 3,800 items |
| 🧍 | Official NPCs | `placeholders` | 73 official NPCs where the clients put them, 44 already working |
| 🚪 | Entrances | `entrances` (off) | 34 portals into the World Sync maps |
| 🛠️ | @npcplace | `npc_mover` | A GM command to move any NPC |

## 🐍 Jormungandr saga (`jormungandr`)

- **Episode 20, The Undying One:** the Ancient Ice Canyon, the Lair of the Rgans, the Sacred Roots,
  the Serpent's Maze, a guest in the Ice Castle, the Frozen Zone and the Nest of Small Branches, and
  the memorial dungeon Separated Sanctuary. 83 quests.
- **Episode 21, Age of Heroes:** back in time to Lunaforma and Alberta of old, the Georborg
  resistance, the ghost ship, two infiltrations of the cult's temple Gimle, and the last battle
  against the giant serpent. 101 quests, with an English quest log (the client only has Korean).
- **After the stories:** daily quests for both episodes (reset at 04:00), the memorial dungeons again
  every day, Koko's Secret Base and Lalaha's dailies, and the traders and enchanters of the Ice Castle
  and Lunaforma (Glacier, Dim Glacier, Georborg and Yorskalf gear).
- Boats, sailors and the hidden ship are real transports; Lunaforma's soldiers, workers and refugees
  have their own lines.

**How to start:** finish Issgard's Episode 19, reach base level 200 and talk to **Horuru** in the
Ice Castle's adventurers' lodge (`icas_in`). Episode 21 starts with **Voglinde** in the Ice Castle's
west wing at base level 230. No Episode 19 yet? Turn on **`skip_ep19`** and Horuru offers Episode 20
to any character of level 200+. The Episode Valkyrie's Episode 20 and 21 Clear Tickets come with
standart-npc's next release.

Everything is written from the kRO client's quest text and navigation tables, since no official
script exists for these episodes.

## 🌳 Varmundt, Amatsu, the Juno Library and the World Tree (`varmundt`)

- 📖 The Fantasy Book **"Dungeon Food"** in the Prontera East Library's new wing (base 100+, daily).
- ♟️ **Varmundt's Chess Garden** under the garden pagoda and the Biosphere Deep Abyss research, with
  Rune Crowns and their enchants (base 250+).
- 🗡️ **Seoyeon's Trial** under Amatsu (base 70+).
- 🌳 **Chapter 1, "Song of the World Tree"**: from the small ash trees near Prontera and Payon to
  Destroyed Geffen, Verus and the Dark Whisper, with memorial dungeons and dailies (base 200+).
- 🔥 **Chapter 2, "Fragment of the End"** (base 225+, after Chapter 1): from Sasha in Ash Village to
  Muspelheim's Harvan village Yongjirak, the frozen Root of Death and Ragsruth, with Yongjirak's
  dailies, Flame Gold Coins and Nirhult's Illusion.
- 📚 The **Juno Library's VR books** through the library annex (base 200+).
- 🏚️ The **eroded wing** of Varmundt's mansion and the Dimensional Biosphere watchers (base 265+).

## ⭐ Star Forest, Herosria and Ash Village (`star_forest`)

- 🌠 The **Star Emperor job change** in the Meteor Forest: talk to Nalson in Payon as a TaeKwon
  Master (base 99 / job 50).
- 🌸 **Sanctuary Herosria's Garden of Dawn**, through portals in the four castle realms: gifts for
  castle lords, Herosria gear, herb jams, the Dimensional Wanderer accessories, refining and
  enchanting.
- ⚔️ **The Herosria siege**, Sundays 20:00-22:00: break the region jewels, the Blocking Stones, the
  four garden jewels (their rulers come back to restore them) and finally the Jewel of Herosria. The
  holding guild's master gets Herosria's Gifts daily. GMs can start a 60-minute test battle at the
  Sanctuary Manager.
- 🌳 **Ash Village's** shops, enchants and signposts at the edge of the World Tree.

## 🛎️ iRO services (`iro_systems`)

iRO's permanent services that World Sync placed as greeting-only NPCs, now working:

- 📦 The Clock Tower's **Devil in the Box** (Clock Tower 1F, base 200+): daily meals in the Unknown
  Basement (100/300/1,000 monsters), a weekly feast (5,000), a snack and her Pet Mimic's errand.
- 🔎 **Catalog Dispensers** search the Prontera and Payon markets' stalls; the **Catalogue Magician**
  in Prontera sells the Window Shopper Catalogue.
- 🌀 The Eden Group's **Dungeon Teleporter** books a dungeon for your party (25,000 z).
- iRO's own NPCs that rAthena ships switched off: Keiki and Aperture's warps, the Refining
  Researcher, Phelix and Izaac, Dark Luhir. Plus the Shadow Blacksmith, Madogear rental (Eclage,
  Mora) and Izlude's Increase AGI acolytes.
- ⛪ **Acolyte training** in the Izlude Sunken Ship: Acolyte Leader Alice in the Prontera Cathedral
  gives three hunts (base 13, 18 and 23) and sends you to the wreck; Laforet brings you back.

## 🔨 Refine Master (`refine_master`)

A **Refine Master** in Prontera (186, 178) uses the refine certificates and tickets, which do
nothing on a stock server because rAthena ships its Refine Master switched off.

- The **+5 to +19 refine certificates** for weapons and armor.
- The **[ROS] tickets** (+13 to +15) for level 5 weapons and level 2 armor.
- No chance of failure; it never refines past the ticket's level, and keeps cards.

## 🎯 iRO Quests (seven settings)

iRO's permanent quests that the server has no script for, with full dialogue and iRO's own quest log.

| Setting | Quests |
|---|---|
| `bounty_boards` | 314 repeatable 150-kill hunts on 65 boards in 25 towns and the Illusion dungeons |
| `criminal_activities` | Agent York and Jymmy the Thumb's casino airship (base 70) |
| `eye_of_the_beholder` | Beho and Bianca in Rachel (base 50) |
| `overlook_water_dungeon` | The Sign west of Geffen, its 15 Aged monsters and 5 floor hunts (base 30-85) |
| `gramps_turn_ins` | Gramps' weekly 400-kill hunts at the Eden Group (base 70-150) |
| `city_investment` | The City Merchant Union: Union Insignias, 113 deliveries, weekly Wanted bosses, investing in 9 cities, Union gear, and the **street stall staffers** |
| `town_quests_2021` | kRO's 2021 town quests: story chains and dailies from Morroc to Alberta, and the Eden Group's field missions |

**Street stall staffers** (City Investment): do Masha's weekly request in Alberta's Merchant Union
(a delivery, a collection or a hunt) to earn a certificate. Ridwan, next to her, turns it into a
staffer that keeps a **selling or buying stall** open in Alberta or Prontera for 1 to 3 days with
3 to 5 kinds of items. Buyers and sellers pay at the stall; the owner gets the zeny or the items by
mail, and whatever is left is mailed back when the stall closes. This is a scripted stand-in: the
server has no real staffer units.

With akreao's **Eden Group 2021 rework** installed too, World Sync Extras takes priority (it is
applied after it). Both use iRO's official ids for the 2021 town quests, which the app merges.

## 🏷️ Regional items (always on)

The server knows about 3,800 items that your client has no name or description for: newer iRO and
kRO items, and items from other regions. Without this they show as "Unknown Item" with an apple
icon. This block gives them:

- **3,582 items** with names and descriptions: about 1,700 with official text (translated where the
  official text is Korean or Japanese), 1,380 with their own icons, and the rest described from the
  server's own data.
- **237 kRO-only items**, all translated into English.
- iRO's text for the 8 items with iRO's own abilities.

## 🧍 Official NPCs (`placeholders`)

73 official NPCs whose dialog and logic exist in no server data yet, standing where the client puts
them with their own sprite and name. **44 already work**: storage lockers, guild storage, inns,
repair, channel switches, the Varmundt elevator, Jormungandr's contact points and the market guides.
The rest greet you until their quests are written. Every block takes over the placeholders it
implements (see `replaced-placeholders.txt`).

## 🚪 Entrances (`entrances`, off)

34 portals from rAthena's towns and fields into the maps World Sync fills (Biosphere, Jormungandr,
Chapter 2 and more). The server leaves them out on purpose: a player whose client lacks those maps
would hang on the loading screen. Turn this on only with recent iRO/kRO client data.

## 🛠️ @npcplace (`npc_mover`, GM level 60+)

Stand next to any NPC and type `@npcplace` to move it where you stand, nudge it a cell, or put it
back. Moves are kept across restarts. `@npcplace list` shows them.

## 📦 Install

**Settings → Mods → Find Mods → World Sync Extras → Install.** Updates come through Settings → Mods
as well.

If you had **iRO Quests** or **World Sync: Jormungandr** installed on their own, remove them: both
are part of this mod now. The same goes for **Regional Items**, which this mod now carries.

### Requirements

- Ragnarok Offline **1.6.9** or later, **Renewal**.
- A client with recent iRO or kRO data (the World Sync maps such as `jor_mbase`, `star_frst`,
  `ch1_geffen`).

### Good to know

- Rewards, prices, recipes and kill counts that kRO doesn't publish are estimates, and say so in
  the scripts.
- Placeholders and entrances are generated by `tools/world_sync/generate.py --placeholders` in
  https://github.com/LilArt420/rathena.

## 📜 License

The mod's own scripts and tools are GPL-3.0 (see `LICENSE`). Gravity's game content (names,
sprites, cut-ins, quest and item text) is not covered and belongs to its owners.
