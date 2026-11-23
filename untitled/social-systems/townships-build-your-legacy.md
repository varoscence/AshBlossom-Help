---
cover: ../.gitbook/assets/H.TOWNSHIPS.png
coverY: 0
---

# 🏘️ Townships: Build Your Legacy

In AshBlossom, you can gather your friends and establish a thriving community. Build a town, claim land, and level up to unlock powerful server bonuses. As a "Never Reset world" our systems are designed for slow, meaningful growth and long-term community building.

> \[!IMPORTANT] You can only belong to one town at a time, and each town is led by one mayor.

***

### 🚀 Getting Started

Every player has the power to start a settlement. Find an empty location and use the following:

* Menu: `/town` — Opens the town menu. Everything below can also be done from there.
* Establishment: `/town create <name>` — Start your journey (Example: `/town create Oakvale`).
* Expansion: `/town claim` — Stand in a chunk to add it to your territory and protect your builds.
* Unclaim Land: `/town unclaim` — Removes the town claim you're standing in.
* Set Spawn: `/town setspawn` — Sets the location for the community hub.
* Travel: `/town spawn` — Teleport back to your community hub.
* Map View: `/town map` — View nearby chunks in a grid; highlights your current standing position.

{% hint style="info" %}
**Claim borders:** hold a **flint** and right-click to see the outline of the claim you're looking at.
{% endhint %}

***

### 👥 Managing Members

Once your town is established, use these commands to manage your population:

* `/town invite <player>`: Invite a player to join your town.
* `/town accept`: Accept a town invite (or `/town decline`).
* `/town evict <player>`: Remove a player from your town.
* `/town promote <player>` / `/town demote <player>`: Move a member up or down a rank.
* `/town members`: See everyone in your town, sorted by Tribute given, with their rank and when they were last online.
* `/town leave`: Leave your current town. You have to type it twice.
* `/town transfer <player> confirm`: Hand your town to another member (Mayor only).
* `/town disband confirm`: Deletes the town (Mayor only).

***

### 👑 Town Roles & Permissions

#### Mayor & Co-Mayor (Town Leaders)

The leaders responsible for the town's identity and future. Co-Mayors have the same powers as the Mayor.

* Identity: Set Town Description, Set Town Rules, Rename Town, Change Town Color.
* Leadership: Evict Players, Promote/Demote Members, Give out Professions, Declare War.
* Growth: Level up the town (when enough Tribute is available).

#### Trustee (Town Manager)

Trusted assistants who handle the daily operations and maintenance.

* Land & Plots: Claim/Unclaim Land, Set Farm Areas, Create/Manage Plots, Manage Plot Members.
* Access: Full access to all town claims, Spawn Privacy, Set Town Spawn.
* Social: Invite Players, Set Greeting/Farewell Messages, Manage Town Relations, View Town Logs.

#### Resident (Town Member)

The core members who live in and support the settlement.

* Contribution: Deposit Tribute.
* Personal: Claim and manage personal building plots.
* Social: Access the private Town Chat channel.
* Travel: Teleport to the town spawn.

#### How many leaders can a town have?

The number of Co-Mayors and Trustees grows with your town level:

| Town Level | Co-Mayors | Trustees |
| ---------- | --------- | -------- |
| 1          | 1         | 3        |
| 5          | 1         | 4        |
| 10         | 2         | 5        |
| 15         | 2         | 6        |
| 21 (City)  | 3         | 8        |
| 31         | 3         | 10       |
| 41 (Empire)| 4         | 12       |
| 51         | 5         | 15       |

***

### 💎 Tribute & Upgrades

Towns run on Diamonds. By depositing diamonds, you give your town **Tribute**, which is used for leveling up.

* Exchange Rate: `1 Diamond = 10 Tribute`
* Deposit Command: `/td <amount>`
* Deposit All: `/tdall`

{% hint style="info" icon="butterfly" %}
No need to type your town name: The system automatically detects your town and deposits it for you.
{% endhint %}

{% hint style="info" %}
**Diamond blocks count too:** a block counts as 9 diamonds. Loose diamonds are used first, and any change comes back to you as diamonds. Only plain diamonds count: renamed or custom items are never taken.
{% endhint %}

{% hint style="danger" %}
\[!CAUTION] Important: Once deposited, diamonds are permanently converted into Tribute and cannot be withdrawn.
{% endhint %}

#### 📈 Town Levels & Bonuses

{% hint style="info" %}
(**Default Claim Size:** Each claimed area is a 16x16 chunk)
{% endhint %}

Leveling up increases your member capacity, claim limits, and provides global buffs:

| Level | Diamonds for this level | Total diamonds from new town | Max Members | Max Claims | Crop Growth | Spawner Bonus |
| ----- | ----------------------- | ---------------------------- | ----------- | ---------- | ----------- | ------------- |
| 1     | Free                    | 0                            | 5           | 6          | +5%         | +2.5%         |
| 2     | 120                     | 120                          | 10          | 10         | +8%         | +3.5%         |
| 3     | 250                     | 370                          | 15          | 14         | +11%        | +4.5%         |
| 4     | 450                     | 820                          | 20          | 18         | +14%        | +5.5%         |
| 5     | 750                     | 1,570                        | 25          | 22         | +18%        | +7%           |
| 6     | 1,150                   | 2,720                        | 30          | 26         | +22%        | +8.5%         |
| 7     | 1,650                   | 4,370                        | 35          | 30         | +26%        | +10%          |
| 8     | 2,300                   | 6,670                        | 40          | 36         | +30%        | +12%          |
| 9     | 3,100                   | 9,770                        | 45          | 42         | +34%        | +14%          |
| 10    | 4,100                   | 13,870                       | 50          | 48         | +38%        | +16%          |
| 11    | 5,300                   | 19,170                       | 55          | 56         | +42%        | +18%          |
| 12    | 6,800                   | 25,970                       | 60          | 64         | +45%        | +20%          |
| 13    | 8,600                   | 34,570                       | 65          | 72         | +48%        | +22%          |
| 14    | 10,800                  | 45,370                       | 70          | 80         | +50%        | +24%          |
| 15    | 13,500                  | 58,870                       | 75          | 88         | +52%        | +25%          |
| 16    | 16,800                  | 75,670                       | 80          | 96         | +54%        | +26%          |
| 17    | 20,800                  | 96,470                       | 85          | 104        | +56%        | +27%          |
| 18    | 25,600                  | 122,070                      | 90          | 110        | +58%        | +28%          |
| 19    | 31,500                  | 153,570                      | 95          | 116        | +59%        | +29%          |
| 20    | 38,500                  | 192,070                      | 100         | 120        | +60%        | +30%          |

### 📈 Progression & Rewards

Towns level up with Tribute. When the town has enough, the Mayor or a Co-Mayor runs `/town level` to increase member capacity, claim limits, and prestige.

#### Level Milestones

* Levels 1–5: Reachable for new towns.
* Levels 6–10: Require consistent teamwork.
* Levels 11–15: Represent established, thriving towns.
* Levels 16–20: Elite achievements for the most dedicated.
* Levels 21–40: **City**, for towns that keep growing.
* Levels 41–60: **Empire**, the legends of AshBlossom.

#### 🏙️ Town, City & Empire

Every 20 levels, your town moves up a tier:

| Tier | Levels | What happens |
| --- | --- | --- |
| 🏘️ Town | 1–20 | Where every community starts. |
| 🏙️ City | 21–40 | Announced to the whole server with fireworks. Professions from the Town tier get one level stronger. |
| 👑 Empire | 41–60 | Announced to the whole server with fireworks. Professions from earlier tiers get one level stronger again, and your town name is shown as ✦ Name ✦. |

{% hint style="info" %}
The Tribute cost, member limit and claim limit for levels 21 to 60 will be added to the table above when City and Empire open.
{% endhint %}

#### Rewards Table

Every reward unlocks automatically, and your town is told the moment it does. See them all in-game with `/town rewards`.

| Town Level | Reward | Description |
| ---------- | ------ | ----------- |
| 3 | Profession: Gatherer | Luck. See Professions below. |
| 5 | Custom Town Tag | A single color tag for your town, made with `/town tag create <TAG>`. |
| 5 | Mayor Tag | Official "Mayor" tag for the leader. |
| 6 | Profession: Miner | Haste. |
| 9 | Profession: Redstoner | Night Vision. |
| 10 | Enhanced Town Tag | A gradient tag with a second color. |
| 10 | Co-Mayor Tag | Official "Co-Mayor" tag. |
| 12 | Profession: Builder | Jump Boost. |
| 15 | Enhanced Mayor & Co-Mayor Tags | Prestigious gradient Mayor and Co-Mayor tags. |
| 15 | Spawn Particles | Cherry leaves drift around your town spawn. |
| 15 | Profession: Postmaster | Speed. |
| 18 | Marker on the Online Map | Your town shows on our official online map. Your town needs a spawn. |
| 18 | Profession: Farmer | You get hungry half as fast. |
| 20 | Server Celebration | An announcement to the whole server and fireworks at your town spawn. |
| 20 | Town Tier Complete | Mayor and Town tags in the Discord, and a unique item for the top 5 members, handed out by staff. |
| 21 | Becomes a City 🏙️ | Server announcement, fireworks, and Town-tier professions one level stronger. |
| 23 | Profession: Fisher | Luck and Dolphin's Grace. |
| 25 | Town Warp | One town warp that members and visitors can use. |
| 27 | Profession: Diver | Water Breathing and Conduit Power. |
| 31 | Profession: Explorer | Speed and Slow Falling. |
| 35 | Profession: Merchant | Hero of the Village. |
| 39 | Profession: Guard | Resistance. |
| 41 | Becomes an Empire 👑 | Server announcement, fireworks, earlier professions one level stronger, and the ✦ Name ✦ style. |
| 44 | Profession: Sage | Fire Resistance. |
| 50 | Profession: Healer | Regeneration. |
| 50 | Hall of Empires | Your town banner on the Hall of Empires wall at spawn, placed by staff. |
| 55 | Custom Join Message | A message the whole server sees when one of your members joins. |
| 56 | Profession: Champion | Strength. |
| 60 | Profession: Archon | Luck, Haste and Speed. |
| 60 | Legendary Statue | A server announcement, fireworks, and a permanent statue at Spawn, built by staff. |

#### 🏷️ Town Tags

* A town tag is 2 to 5 capital letters or numbers, and every town's tag is different.
* Once your town has a tag, every member can wear it from `/tags`. It shows in your town color.
* Members who leave the town lose the tag.

#### ⚒️ Professions

The Mayor and Co-Mayors can give each member one profession. Each profession can be held by one member per town.

| Profession | Unlocks at | Effect |
| --- | --- | --- |
| Gatherer | Level 3 | Luck |
| Miner | Level 6 | Haste |
| Redstoner | Level 9 | Night Vision |
| Builder | Level 12 | Jump Boost |
| Postmaster | Level 15 | Speed |
| Farmer | Level 18 | Get hungry half as fast |
| Fisher | Level 23 | Luck, Dolphin's Grace |
| Diver | Level 27 | Water Breathing, Conduit Power |
| Explorer | Level 31 | Speed, Slow Falling |
| Merchant | Level 35 | Hero of the Village |
| Guard | Level 39 | Resistance (off during wars) |
| Sage | Level 44 | Fire Resistance |
| Healer | Level 50 | Regeneration (off during wars) |
| Champion | Level 56 | Strength (off during wars) |
| Archon | Level 60 | Luck, Haste, Speed |

* `/town profession` — See every profession and who holds it.
* `/town profession set <player> <profession>` — Give a member a profession.
* `/town profession clear <player>` — Take a profession away.

**Leader bonus:** the Mayor and Co-Mayors also get Haste.

**Tier bonus:** when your town becomes a City, and again when it becomes an Empire, every profession unlocked in an earlier tier gets one level stronger (for example Haste I becomes Haste II). Effects without levels, like Night Vision or Fire Resistance, stay the same.

#### 🏅 Patron of the Month

Each town's top Tribute giver of the month gets the **Patron** tag. If someone gives more, it moves to them. It resets on the 1st of every month.

#### 🌀 Town Warps (Level 25)

* `/town setwarp <name>` — Set a town warp where you stand, inside your claims (Trustees and above).
* `/town warp <name>` — Teleport to one of your town's warps.
* `/town warp <town> <name>` — Visit another town's warp, if that town's spawn is public.
* `/town warps` — List the warps.
* `/town delwarp <name>` — Delete a warp.

#### 📣 Custom Join Message (Level 55)

The Mayor and Co-Mayors can set a message with `/town joinmessage <text>`. Everyone online sees it when one of your members joins. Use `{player}` for the member's name.

#### 🎆 Town Anniversary

Every year on the day your town was founded, your town gets a message and fireworks at its spawn.

***

#### 🌾 Farms, Plots & Ally Claims

Every claim can be one of these types:

* **Normal claim:** Trustees and above can build. Residents can use doors and buttons.
* **Farm** (`/town farm`): Residents can farm, use doors and buttons, open chests and hit mobs.
* **Plot** (`/town plot`): A personal plot. Residents can claim one with `/town plot claim`, and add others with `/town plot add <player>`. Plot members can do everything in their plot, even if they're from another town.
* **Ally claim** (`/town allyclaim`): A shared storehouse. Members of your town and of your allied towns can build, farm, use doors and open chests there. Both towns must have set each other as allies. Choose which allies can use it with `/town allyclaim add <town>` and `/town allyclaim remove <town>`.

{% hint style="info" %}
**Town Rules:** the Mayor and Co-Mayors can open `/town rules` to choose what visitors can do in your claims, farms and plots: build, farm, interact, open containers, mob spawning, fire, PvP, explosions and mob griefing.
{% endhint %}

***

#### 📜 Full Command Reference

| Command | Description |
| --- | --- |
| /town | Open the town menu. |
| /town help | View the full list of town commands. |
| /town about \[town] | View detailed information about a town. |
| /town list | View all towns. Sort by level, members, tribute, claims or name. |
| /town towns \[search] | Search all towns by name, tag or member. |
| /town members \[town] | See every member with their rank and Tribute given. |
| /town census \[town] / /town deeds \[town] | See a town's members and ranks, or its claimed chunks. |
| /town player \<name> | See a player's town and rank. |
| /town invite \<player> | Invite a player to join your town. |
| /town accept / decline | Answer a town invite. |
| /town claim / unclaim | Claim or remove the chunk you are standing in. |
| /town autoclaim | Toggle auto-claiming as you walk. |
| /town map | View a visual map of nearby town claims. |
| /town spawn \[town] | Teleport to a town's spawn point. |
| /town setspawn / clearspawn | Set or remove your town spawn. |
| /town privacy \<public\|private> | Choose whether other players can visit your town spawn. |
| /town promote/demote \<player> | Manage the roles/hierarchy of your members. |
| /town evict \<player> | Remove a member from the town. |
| /town leave | Leave your current town. |
| /town chat \[message] | Send a town chat message, or toggle town chat. |
| /town farm / plot / allyclaim | Change the type of the claim you're standing in. |
| /town rules | Choose what visitors can do in your land. |
| /town level | Pay Tribute to level up the town and unlock bonuses. |
| /town rewards | See every level reward. |
| /town deposit \<amount\|all> | Deposit diamonds as Tribute (same as `/td`). |
| /town tag create \<TAG> / clear | Create or remove your town tag. |
| /town profession | See and give out professions. |
| /town welcome \<text\|clear> | A message every new member gets when they join. |
| /town setwarp / warp / warps / delwarp | Manage and use town warps (level 25). |
| /town joinmessage <text> | Set your custom join message (level 55). |
| /town log | View the town's audit log (recent actions). |
| /town relations | Manage alliances or rivalries with other towns. |
| /town war | View and declare wars. |
| /town bio/rename/color | Edit the town's description, name or color. |
| /town greeting/farewell | Edit enter/exit messages for your land. |
| /town transfer \<player> confirm | Transfer town ownership to another member. |
| /town disband confirm | Permanently delete the town. |

***

### ⚔️ Town Wars Protocol

Towns can declare war if both sides agree to the conflict. Use the following commands to initiate the process:

* Set Enemy Town: `/town relations set enemy <town>`
* Declare War: `/town war declare <town> <wager>`
* Answer a Declaration: `/town war accept` or `/town war decline`
* Give Up: `/town war surrender`

#### 📋 Requirements & Matchmaking

* Enemies Only: You can only declare war on a town you've set as an enemy.
* Declaration Acceptance: The defending town has **10 minutes** to accept, or the declaration expires.
* Player Turnout: At least 25% of each town's members must be online to start the war.
* The Wager: Both towns put the same amount of Tribute at stake. Both towns must be able to afford it. The winner takes both wagers.
* Roster Submission: Both towns must compile and exchange a complete list of all participating town members prior to the match to ensure accurate counting and prevent unfairness.

### 🛑 The Main Rule: No Hiding, No Camping!

> ⚠️ STRICT POLICY: Absolute transparency is required. Players are forbidden from hiding or camping to stall out the clock. You must engage!

### 🏟️ The War Zone & Mechanics

* Commencement: When the defending town accepts, all online members of both towns are teleported to the defending town's spawn. Defenders start at the spawn, and attackers start a short distance away.
* The Battlefield: The war zone is a **160-block radius** around the defending town's spawn, marked by a red wall of particles.
* Elimination: Dying, leaving the war zone or logging off removes you from the battle.
* Victory Condition: A town loses when it has no fighters left. The winner takes both wagers.
* Surrender: A town can surrender at any time. The other town wins.
* Time Limit: A war lasts at most **3 hours**. If time runs out, it's a stalemate and both wagers are lost.
* Truce Period: After a war concludes, a mandatory 7-day truce is enforced before either town can declare or accept another war.
* War Honors: Every war your town wins is counted and shown in `/town about`.

### 💰 Rewards, Spoils, & Risks

#### Pre-War Agreements & Rewards

Before the war begins, both towns must formally agree upon the stakes and rewards. For example, the winning town could demand terraforming labor or specific resources.

* The Sealed Contract: All agreed-upon terms must be written in an in-game book, signed, and sealed by the challenging Mayor.
* Strict Terms: What is written is final. Absolutely no additional terms may be added after the book is signed.

#### Combat Risks

* Inventory Loss: All inventory could be permanently lost upon death, unless both sides explicitly agree *before the war* to return items to their rightful owners.
* Town Griefing: Town griefing is enabled/possible during the conflict. Be hyper-aware of your claims and protect your assets.
* Allies & Reinforcements: Allies from outside towns are permitted to show up and assist. They don't count as fighters for the victory condition, but they can change the outcome, which is why diplomatic alliances are critically important.

### ⚠️ Inactivity Policy

To keep the world healthy and free up land for new communities:

* If no members from a town log in for 90 consecutive days, the town and its claims may be permanently deleted.

***

#### ⚠️ Important Guidelines

* Expansion Space: Towns must be at least 8 chunks apart. Do not build too close to existing towns. If you block another town's growth, your claims may be removed.
* Island Sovereignty: Towns on islands own the entire island. Unauthorized builds on a town's island will be removed.
