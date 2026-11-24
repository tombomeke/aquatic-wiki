# Sieges

A siege is how an island changes hands. One crew attacks, the owners defend, and whoever holds the ground around
the flag wins. Sieges only happen at times the defenders chose, so nobody loses an island while they sleep.

## The siege window

Every crew has a **siege window**: one fixed time slot a day when its islands can be attacked.

- It lasts **2 hours** (1 hour for crews of one or two players) and starts at one of the evening hours the server
  allows (17:00 to 21:00).
- **The window uses the server's clock**, not yours. `/island siege window` shows the server's time, its time zone
  and UTC offset, and how long until each possible window starts, so you can work out what it is for you.
- The Captain or First Mate picks it: `/island siege window <hour>`, then click **[Confirm]**. You can change it
  once a week, and the change starts 24 hours later (no dodging a siege that is coming).
- A new crew is safe from sieges for its first 48 hours.

`/island siege` shows your window and every siege going on; `/island info` shows any island's window.

## Declaring a siege

The Captain or First Mate of the attacking crew stands within 300 blocks of the target island, **during its owners'
window**, and types `/island siege declare`.

- It costs **1,000 Doubloons** from the crew bank, times the island's rarity (common x1, uncommon x1.5, rare x2,
  epic x3, legendary x4). **At war** with the owners: half the price.
- The siege starts **10 minutes** later (5 at war). Both crews get the coordinates: sail there.
- An island can be besieged once a day, and a crew can declare two sieges a day.
- During the siege nobody can teleport onto the island. Everyone sails.

## Taking the flag

The siege lasts at most **30 minutes**. The attackers win by filling the capture bar (it takes 3 minutes at full
speed, longer with a Fortress and standing facilities).

- What counts is the **area 25 blocks around the flag** (and 10 blocks up or down), marked by a **ring of gold sparks**.
  You don't have to stand on the flag: fight for the ground around it.
- **Only attackers there:** the bar fills, faster with more of them (up to twice as fast).
- **More attackers than defenders:** it fills slowly.
- **As many defenders as attackers:** it stops.
- **More defenders, or only defenders:** it goes back down. With nobody there it slowly drops.
- Allies of the owners defend too. The boss bar shows the percentage, both sides' numbers and the time left.

## Facilities fight back

Every [facility](Facilities.md) on the island gets a glowing **core** during the siege.

- **Each standing facility makes the flag 10% slower to take** (at most +50%).
- Attackers can **break** a core by hitting it (it has health, shown like a ship's hull) or by firing ship cannons
  at it, or **sabotage** it by standing at it for 20 seconds with no defender within 8 blocks.
- **Every facility brought down adds 10% to the capture at once.** Defenders who all stand at the flag lose their
  facilities one by one: spread out.
- A **Watchtower** makes every attacker on the island glow.
- A **Shore Battery** fires at attackers on the water: three hits sink a boat, and on servers with ship cannons it
  fires real cannonballs at their ships.
- A **Barracks** at level 2 or 3 sends 3 or 6 guards to the flag; each counts as half a defender. Dying and
  respawning at the Barracks means 20 seconds of regrouping before you count again.
- Nothing is destroyed for good: after the siege every facility works again.

## How it ends

- **The flag falls:** the attackers choose (click, or `/island siege take` / `plunder`):
  - **Take** the island: it becomes theirs, and every upgrade on it drops one level.
  - **Plunder** it: they get 60% of the stored goods as cargo crates and the island vault's contents, and the
    owners keep the island.
- **30 minutes pass:** the siege fails. The defenders get reputation and half of what the attackers paid.
- After every siege the island has a **24-hour truce**.
- **Called off:** if the defending crew disappears (staff removed it, for example), the siege ends and the attackers
  get their money back. A crew in a siege can't disband to escape it.

## Tips

- **Defenders:** put your window at a time your crew is online, build facilities (each one slows the capture), and
  don't all stand on the flag.
- **Attackers:** scout the island first (`/island info`), bring a ship with cannons for the Shore Battery and the
  cores near the water, and send someone to break facilities while the rest hold the ring.

[Facilities](Facilities.md) · [Crews](Crews.md) · [Back to the wiki](README.md)
