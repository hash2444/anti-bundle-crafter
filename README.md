# Anti-Bundle Crafter

> Lock any item ID: it disappears from inventories, containers and drops - controlled from an in-game menu.

[![Download](https://img.shields.io/badge/Download-latest%20build-e94560?style=for-the-badge&logo=github&logoColor=white)](../../releases/latest)

A Bedrock add-on (behavior + resource pack) with a command-driven item lock system. Locked items are removed from player inventories, equipment slots, every nearby container (chest, hopper, dropper, dispenser, barrel, shulker, crafter, brewing stand, furnace, ...) and dropped item entities - both by tick scan and by instant event hooks.

## What it does

- Full-screen menu: toggle the item in your hand, search all ~1700 item IDs (multiple terms, exact match), paginated with bulk lock/unlock
- List of locked items - tap an entry to unlock it; *Unlock all* with confirmation
- Settings for scan radii, tick intervals and before-event cancels
- Statistics of what was removed

## Download

Download **`Anti-Bundle-Crafter-v1.0.0.mcaddon`** from the [releases page](../../releases) (or straight from this repository) and open it - Minecraft imports the packs.

1. Create or edit a world and open **Add-Ons**.
2. Activate the **Behavior Pack** and the **Resource Pack** of this add-on.
3. Requires Minecraft Bedrock **1.21.50 or newer**.

If items are missing in your world, check the world's *Experiments* page and enable *Beta APIs* and *Holiday Creator Features* as a fallback.

New to this? Follow **[SETUP-HELP.md](SETUP-HELP.md)** - it walks you through installing and starting it.

## Commands (operators only)

| Command | Action |
|---|---|
| `/scriptevent abc:menu` | Open the main menu |
| `/scriptevent abc:lock_hand` | Toggle the lock on the item in your hand |
| `/scriptevent abc:toggle minecraft:bundle` | Toggle by item ID |
| `/scriptevent abc:stats` | Print statistics in chat |
| `/scriptevent abc:help` | Command overview |

`/scriptevent` needs operator rights (cheats on, and you are the world owner or `/op`'d). Regular players cannot use it.

## Dev Book

Every pack of mine carries a small easter egg: craft the **Dev Book** with **9 logs** (any wood type, 3x3 in a crafting table) and right-click it. It opens like a book: page 1 the credits, page 2 what this mod is, page 3 the GitHub links (Minecraft cannot open links, so they are shown as text). It also sits in the creative inventory under *Equipment*.

## Notes

- Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.

![preview](anti-bundle-crafter.png)

---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444) - [anti-bundle-crafter](https://github.com/hash2444/anti-bundle-crafter)
