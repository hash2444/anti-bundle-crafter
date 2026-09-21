# Anti-Bundle Crafter - Setup help

Everything you need to get **Anti-Bundle Crafter** running, step by step. If something goes wrong, check *Troubleshooting* at the end.

## What you need

- Minecraft **Bedrock Edition** 1.21.50 or newer (Windows, phone, console or a Bedrock server)

## Install and start

1. Download **`Anti-Bundle-Crafter-v1.0.0.mcaddon`** from the [Releases page](../../releases) - or directly from this repository.
2. Open the file (double-click on Windows, or tap it on a phone/tablet). Minecraft starts and shows *Import started* / *Import successful*.
3. Create a new world or edit an existing one and open **Add-Ons**.
4. Under **Behavior Packs** activate this add-on's pack, then under **Resource Packs** activate the matching resource pack.
5. Start the world. (On a dedicated server, copy the two pack folders from the `.mcaddon` - it is a zip - into `behavior_packs` and `resource_packs` and list them in the world's pack files.)
6. If something does not show up, open the world's **Experiments** page and switch on **Beta APIs** and **Holiday Creator Features**, then reload the world.

## Get the Dev Book (easter egg)

Place **9 logs** (any wood type) in all nine slots of a crafting table. The result is the **Dev Book**. Right-click it to open it like a real book: credits, a short description of this add-on, and the GitHub links. In creative mode you find it under *Equipment*.

## How to use it

- Open the menu: `/scriptevent abc:menu` (operators only - cheats on, or you are the world owner).
- Lock the item in your hand with `/scriptevent abc:lock_hand`, or by ID with `/scriptevent abc:toggle minecraft:bundle`.
- Locked items disappear from inventories, containers and the ground within a moment.

## Troubleshooting

**The pack does not import**

Make sure the file ends in `.mcaddon` (not `.zip`) and that Minecraft is up to date.

**The add-on does not do anything in my world**

Both the Behavior Pack **and** the Resource Pack must be active, and the world needs *Beta APIs* / *Holiday Creator Features* if your Minecraft version asks for them.

**I updated but nothing changed**

Remove the old pack version from the world's Add-Ons page (and from *Storage* -> *Behavior/Resource Packs*), then import again.

## Uninstall

Remove the packs from your world's Add-Ons page, and delete them under *Settings -> Storage -> Behavior Packs / Resource Packs*.

## Still stuck?

Open an **Issue** on this repository and tell me your Windows / Minecraft version and what you see (a screenshot helps).

---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444)
