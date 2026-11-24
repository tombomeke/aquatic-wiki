# Facilities and upgrades

Your crew makes an island its own with **facilities** (real buildings that go up block by block) and
**upgrades** (levels bought from the crew bank). Both are in `/island manage`, paid from the crew bank by the
Captain or First Mate.

## Facilities

Up to 8 per island. You pick one in `/island manage` → **Facilities**, see a ghost
preview of it where you stand (green outline = it fits), rotate or move it, and click **Build**: the site is cleared
and the building rises in about 30 seconds. Removing one gives back 50% of its price.

| Facility | Price | Max | Income | What it does |
| --- | ---: | ---: | ---: | --- |
| **Watchtower** | 3,000 | 2 | - | A tall lookout with a ladder and a roofed platform: see ships coming from far away. |
| **Forge** | 2,500 | 1 | +5% | An open smithy: anvil, smithing table, blast furnace, grindstone and a chest. |
| **Farm Field** | 1,500 | 3 | +5% | A fenced 9x9 field with water, already planted with wheat, carrots, potatoes and beets. |
| **Dock** | 2,000 | 2 | +10% | A wooden dock out over the water on posts. Stand at the shore and face the sea. |
| **Storehouse** | 2,000 | 2 | +5% | A timber storehouse full of barrels, with a crafting table and a gabled roof. |
| **Lighthouse** | 4,000 | 1 | +5% | A red and white lighthouse with a glowing lantern room. Climb the ladder to the top. |
| **Shore Battery** | 6,000 | 3 | - | A stone gun platform out over the water. During a siege it fires at attackers in boats (siege.yml: defenses.battery). Face the sea. |

**In a siege** every facility has a glowing core. While it stands, the flag takes 10% longer to capture
(at most +50%); when attackers break it, the capture jumps 10% at once. See [Sieges](Sieges.md).

## Upgrades

Each upgrade has levels; every level costs more. Buy the next level in `/island manage`.

| Upgrade | Price per level | What it does |
| --- | --- | --- |
| **Treasury** | 2,000 / 4,000 / 8,000 / 15,000 / 25,000 | More passive income from this island. +25% income per level. |
| **Fortress** | 2,500 / 5,000 / 10,000 / 18,000 / 30,000 | Enemies need longer to capture your flag. +20% capture time per level. |
| **Watchtower** | 1,500 / 4,000 / 9,000 | Your crew is warned when enemies land. Level 2+: intruders glow (longer per level). |
| **Harbor** | 1,500 / 4,000 / 8,000 | Crewmates swim faster around the island. Level 3: also breathe underwater. |
| **Barracks** | 5,000 / 10,000 / 20,000 | Crewmates without a bed respawn on this island instead of at spawn. Level 2: 3 guards defend the flag in a siege, level 3: 6 with a Guard Captain. Levels 2 and 3 also take cargo crates of Volcanic Glass or Tidewatch Iron (2, then 4), carried here. Levels 2 and 3 also need 2 and 4 cargo crates of Volcanic Glass or Tidewatch Iron, carried to the island. |
| **Wellspring** | 3,000 / 9,000 | Crewmates slowly heal while on the island. Stronger per level. |
| **Vault** | 3,000 / 8,000 / 16,000 | Storage for the whole crew on this island (/island vault). 9, 27 or 54 slots. Conquerors take what's inside! |
| **Granary** | 2,000 / 6,000 | Crewmates slowly get their hunger back while on the island. |

When an island is conquered, every upgrade on it drops one level.

---
*Generated from the server's island settings (`tools/wiki_docs.py`).*

[Back to the wiki](README.md)
