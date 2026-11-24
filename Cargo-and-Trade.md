# Cargo and trade

This is where crews make their real money: your islands produce goods, you pack them into crates and sail them to a
**Harbor Exchange** to sell. The trip is the dangerous part.

## 1. Your islands produce goods

Every claimed island makes the trade good of its type, **also while you're offline**: a few units an hour (common
islands the most, rare ones fewer but worth far more). The island stores 24 units, and every Storehouse facility
adds 64. When storage is full, production stops, so collect it. `/cargo` shows each island's good, how much is
waiting and when it is full.

Islands in the Abyssal Reach also grow an **Abyss Pearl** every 8 hours (up to 3), worth 600 each.

## 2. Pack it into crates

A Captain, First Mate or Quartermaster stands at a **Dock** or **Storehouse** facility on the island and types
`/cargo pack` (16 units per crate). A crate is a barrel item with the good, its island and its zone on it.

## 3. Sail it to a Harbor Exchange

Harbor Exchange villagers stand at the capital and in villages. Right-click one (or `/cargo sell` next to it) to sell
every crate you carry; the money goes to your crew bank. `/cargo prices` shows today's prices.

- **The farther a crate travels, the more it fetches:** +10% for every 1,000 blocks between its island and the
  Exchange, up to +60%.
- **Goods from farther out are worth more** (see the table below).
- Prices drop for everyone when a lot of one good is sold and recover over time, so different island types pay.

## Carrying crates: being "laden"

While you carry even one crate you are **laden**:

- **No teleporting** of any kind: no `/spawn`, `/island home`, `/tpa`, ender pearls, chorus fruit, or fruit moves
  that dash, fly, blink or swap. You sail.
- No elytra, and you're slower on land with 2 or more crates (not in a boat). You carry at most **6**.
- Crates can't go in ender chests, shulker boxes, bundles or the island vault.
- Other players see a **golden wake** behind you on the water.
- **Die, get your boat sunk, or log out away from your own island, and the crates drop**, glowing, for anyone to
  pick up. Your crew gets told where. Selling another crew's crates works, but raises your bounty.
- The waters around the capital (**Harbour Waters**, 400 blocks) are safe: no fighting there.

## Harbour contracts

No island yet? The Exchange menu also lists **contracts**: carry the Crown's crates to another Exchange in time.
You pay a deposit (15% of the cargo's worth) and get it back with a fee (10%) when you deliver. While you carry
them, the bar at the bottom of your screen points the way and shows the time left. Whoever delivers the crates gets
paid, so pirates hunt contract runners too. **Merchant brigs** at sea carry crates in their hold for anyone who
takes the ship.

## Islands close together and the Sea Lord

- **Linked islands:** two of your islands within 1,500 blocks of each other each make 10% more goods (up to +30%).
  A Lighthouse doubles the range for its island.
- **Sea Lord:** every island your crew holds earns points each hour (rarer = more). The crew with the most points at
  the end of the week is the **Sea Lord**: 10,000 Doubloons for its bank and 100 reputation. `/sealord` shows the race.

## Goods and zones

<!-- generated:goods -->
| Good | Made on | Base price per crate |
| --- | --- | ---: |
| Grain Sacks | Plains | 960 |
| Timber | Forest | 960 |
| Spice | Jungle | 1,680 |
| Furs | Snowy | 1,680 |
| Saltpeter | Desert | 1,680 |
| Rum Casks | Tropical | 2,880 |
| Tidewatch Iron | Tidewatch | 2,880 |
| Volcanic Glass | Volcanic | 4,800 |
| Relics | Ancient | 4,800 |

| Zone | From (blocks from the centre) | Goods worth |
| --- | ---: | ---: |
| The Shallows | 0 | x1.0 |
| The Open Sea | 3,000 | x1.3 |
| The Abyssal Reach | 7,000 | x1.7 |
<!-- /generated:goods -->

The far sea has **squalls**: out at sea in the Abyssal Reach, a squall can roll in with rain and lightning striking
around you for a minute or so. See [Ships](Ships.md).

[Ships](Ships.md) · [Islands](Islands.md) · [Back to the wiki](README.md)
