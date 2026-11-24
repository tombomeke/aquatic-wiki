# Crews

A crew is your pirate gang: **up to 6 pirates** under one flag. Only crews can claim islands, so this is the first
thing to sort out.

## Founding or joining one

- **Found a crew:** talk to the **Crew Registrar** at the capital or type `/crew`, click **Found a crew**, type a name
  (3-16 letters, digits or _) and a tag (2-6 letters or digits, shown as `[TAG]` in chat), and confirm. It costs
  **1,000 Doubloons**. You become its Captain.
- **Join a crew:** an officer invites you with `/crew invite <you>`; you type `/crew accept`.
- **Leave:** `/crew leave`. A Captain hands the crew over first (`/crew transfer <player>`) or disbands it.

`/crew` opens the crew menu: members, ranks, the bank, the home and your friends and enemies, all clickable.

## Ranks

| Rank | Can do |
| --- | --- |
| **Captain** | Everything, and is the only one who can disband the crew |
| **First Mate** (1) | Invite and kick, change ranks, the crew's look (colour, tag, flag), set the home, friendly fire, take money out of the bank, alliances and wars, claim islands, buy upgrades |
| **Navigator** (1) | Invite, set the crew home |
| **Quartermaster** (1) | Invite, take money out of the bank, pack cargo crates |
| **Deckhand** | Everything a normal crewmate does: build on your islands, deposit, crew chat |

`/crew promote`, `/crew demote` and `/crew setrank <player> <rank>` change ranks.

## The crew bank

Everyone can put Doubloons in: `/crew bank deposit <amount>`. The First Mate and Quartermaster can take money out
(`/crew bank withdraw <amount>`). The bank pays for island upgrades, facilities and sieges, and island income and
cargo sales go straight into it.

**If the crew is disbanded**, every member gets back what they deposited themselves (shared out if the bank holds
less than that, for example after buying upgrades). Whatever is left, like island income and prizes, goes to the
Captain. A member who leaves the crew leaves their deposits with the crew. A crew can't be disbanded while it is in a
siege.

## Friends and enemies

| Relation | How | What it means |
| --- | --- | --- |
| **Ally** | `/crew ally <crew>` from both sides (at most 3) | Can build on each other's islands and defend each other's flags; can't hurt each other |
| **Rival** | `/crew rival <crew>` | Just a label: everyone knows you don't get along |
| **War** | `/crew war <crew>` (costs 500, lasts at least 60 minutes, at most 2 at a time) | Sieges against them cost half and give a shorter warning; kills give more reputation |
| **Peace** | `/crew peace <crew>` from both sides | Ends a war |

## Getting around together

- **Crew chat:** `/cc <message>`, or `/cc` on its own to talk in crew chat until you switch it off.
- **Crew home:** `/crew sethome` (First Mate or Navigator), then `/crew home` for everyone.
- **Teleport to a crewmate:** `/tpa <crewmate>` (they type `/tpaccept`), or `/tpahere` to bring them to you.
  Not while carrying cargo, and not onto an island under siege.
- **Friendly fire** is off: crewmates can't hurt each other unless the First Mate turns it on.

## Reputation and the crew list

Crews earn reputation by beating other pirates (more in a war), defending against sieges and finishing the
tournament. `/crew top` ranks crews by reputation, `/crew list` shows every crew, `/crew info [crew]` shows one.

## Looks

`/crew color <colour>` and `/crew tag <tag>` (250 Doubloons each) change how your crew shows in chat and the tab
list. `/crew flag` designs the flag that flies on every island you own: hold a banner made in a loom and type
`/crew flag set`, or pick a ready-made design with `/crew flag preset <name>`.

[Islands](Islands.md) · [Sieges](Sieges.md) · [Back to the wiki](README.md)
