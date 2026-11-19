# ⚔️ PVP Duel

## ⚔️ Duel System

{% hint style="info" %}
We have a PVP Arena: /pw pvp
{% endhint %}

***

## PvP & Duels

AshBlossom Duel lets any two players challenge each other to a 1v1 in a dedicated arena with a chosen kit: gear is snapshotted and restored automatically, arenas self-repair after every fight, and stats/leaderboards are tracked server-wide.

All duel commands are grouped under `/duel`.

***

### Player Commands

| Command                            | Description                                                                                     |
| ---------------------------------- | ----------------------------------------------------------------------------------------------- |
| `/duel <player> [arena] [kit]`     | Challenge a player. Run `/duel <player>` alone to see a menu of free arenas and available kits. |
| `/duel accept`                     | Accept a pending duel request.                                                                  |
| `/duel cancel`                     | Cancel a request you sent, or decline one sent to you.                                          |
| `/duel surrender`                  | Surrender your current duel.                                                                    |
| `/duel again`                      | Re-challenge your last opponent with the same kit and arena (skips cooldown).                   |
| `/duel quiet`                      | Toggle whether you receive duel requests.                                                       |
| `/duel queue <kit\|random\|leave>` | Join matchmaking for a kit (or any kit) instead of naming an opponent.                          |
| `/duel arrange <kit> [reset]`      | Personally reorder an official kit's item slots.                                                |
| `/duel stats [player]`             | View win/loss record, streak, and per-kit wins.                                                 |
| `/duel top`                        | View the server's duel win leaderboard.                                                         |
| `/duel help`                       | List every duel command you have permission to use.                                             |

***

### Personal Kits (`/mykit`)

Players can build their own private loadout with the same "wear it, then snapshot it" mechanic as an official kit. Nobody else can see, list, or duel against your personal kit.

1. **Build the loadout:** Wear the armor and carry whatever items you want, then run `/mykit create <name>`.
2. **Challenge someone:** Select it from the `/duel <player>` menu or run `/duel <player> <arena> <kit_name>`.
3. **Manage kits:**
   * `/mykit list` – View your personal kits.
   * `/mykit create <name>` – Create or overwrite a personal kit.
   * `/mykit remove <name>` – Delete a personal kit.

{% hint style="info" %}
* **Personal Kit Cap:** Capped at 5 per player by default.
* **Priority:** Official kits take priority over personal kits if they share the same name.
{% endhint %}

***

### How a Duel Ends

* **Surrender:** Either player runs `/duel surrender`.
* **Lethal Damage:** Fully respected; fatal hits end the fight.
* **Leaving the Arena:** Stepping outside the arena boundary results in an automatic forfeit.
* **Disconnecting:** Counts as a loss for the disconnected player. Gear is restored upon reconnecting.
* **Timeout:** Fights lasting longer than 30 minutes end as an automatic draw.

***

### Protections During a Duel

* Items cannot be dropped or picked up.
* Interacting with containers, blocks (doors, buttons), or entities is disabled.
* Non-duel commands (like `/home`, `/spawn`, `/tpa`) are blocked during combat.
* All arena blocks placed or destroyed are automatically restored when the duel ends.
