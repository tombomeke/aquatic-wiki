# Islands

The Endless Sea is full of generated islands, each with its own terrain, caves, ores and ruins. Your crew can own up
to **3** of them.

## Island types

| Island | Rarity | Known for |
| --- | --- | --- |
| Plains, Forest | Common | Close to the capital, easy to settle; grain and timber |
| Jungle, Snowy, Desert | Uncommon | Spice, furs, saltpeter; emeralds, lapis, gold |
| Village | Uncommon | Neutral: villagers with quests, can't be claimed |
| Tropical | Rare | Rum and beaches |
| Tidewatch fort | Rare | Held by the navy: liberate it first ([Treasure, ships and ores](Treasure-and-Ores.md)) |
| Volcanic, Ancient | Epic | Volcanic Glass and relics; the richest ores (volcanic islands have diamonds) |
| Capital | Legendary | The spawn town: market, shopkeepers, piers. Safe, can't be claimed |

The farther from the capital, the rarer the islands: see the sea zones on [Cargo and trade](Cargo-and-Trade.md).
`/island map` lists the nearest islands with direction and distance, and a **Tide Compass** points the way: right-click for a random island (every 2 minutes), sneak + right-click for the
nearest one (every 5 minutes). The compass doesn't tell you what kind of island it is: go and see.

**Discovering** an island for the first time pays Doubloons (more for rare ones). `/island discovered` is your logbook.

## Claiming an island

1. Sail to an unclaimed island. `/island info` tells you what it is and who lives there.
2. The Captain or First Mate stands where the flag should go and types `/island claim`. It costs **1,000** from the
   crew bank, plus 500 for every island the crew already owns.
3. **Most islands are wild:** something lives there (squatters, bandits, temple guardians...). Claiming starts a
   *settling*: waves of them attack the flag spot (2 waves on a common island, up to 6 on a legendary one; epic and
   legendary islands end with their leader). Stay near the spot: if your whole crew is away for 30 seconds, the claim
   fails, you get half the price back and can try again after 10 minutes.
4. Win, and your crew flag goes up on a pole. The first claim of an island also gives a treasure map.

An island that loses its owner is **tamed** for 6 hours (claimable without a fight), then goes wild again.

## Owning an island

- **Only your crew builds there** (and allies, if the server allows it). Outsiders can't break, place, open your
  chests, edit your signs or use tools on your blocks; lava and water can't be poured in from outside.
  `/island manage` can limit building to officers.
- **Flags can't be broken** by anyone: an island only changes hands through a [siege](Sieges.md).
- **Income:** every 30 minutes the island pays the crew bank (60 Doubloons for a plains island, up to 120 for a
  volcanic one) while someone from the crew is online. **Upkeep** comes off that: 100 per island and 25 per
  facility, more for each extra island. If the bank can't pay it for too long, the island is lost.
- **Trade goods:** the island also produces the good of its type, even while you're offline: see
  [Cargo and trade](Cargo-and-Trade.md).
- **Facilities and upgrades** make it richer and harder to take: see [Facilities](Facilities.md).
- **Home port:** `/island home` sails you to your crew's home port (`/island homeport` shows it; the Captain or First
  Mate can move it once a day). Your other islands you reach by sailing.
- **Giving it up:** `/island unclaim` (not while it is under attack).

## Useful commands

| Command | What it does |
| --- | --- |
| `/island info [island]` | Type, owner, income, siege window and shield of an island |
| `/island here` | Which island you're standing on |
| `/island map` | The nearest islands, with direction and distance |
| `/island list`, `/island top` | Every island; crews ranked by islands owned |
| `/island claim` | Claim the island you stand on |
| `/island manage` | Your island's menu: upgrades, facilities, building rules |
| `/island flag` | Move your flag to where you stand |
| `/island vault` | The island's shared chest (needs the Vault upgrade) |

[Crews](Crews.md) · [Facilities](Facilities.md) · [Sieges](Sieges.md) · [Back to the wiki](README.md)
