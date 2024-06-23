# Craftoria-Neo-Bug-Tracker
Want to help? Fantastic!
Helping find and report bugs will help both _Craftoria_ and the nacsent ecosystem of NeoForge mods for MC 1.21.

The goal is to report bugs to the relevant mods' issue trackers.
This list is meant for:
1. Collaboratively listing found bugs
2. Noting their status as being reported or not yet.

An new, un-reported bug should be formatted like so: `- [ ] my new hot bug`.
It will  look like this:
- [ ] my new hot bug

To check-off a bug as reported, fill in an "X" in the box, like so: `- [x] my new hot bug`
- [x] my new hot bug

It may be best to add a link to reported issues, using the format: `[Issue #](url)`.

If you noticed a bug has been fixed, feel free to move it's line down to the "Fixed Bugs" section. That section will be our little testament to the hard work and effort the community has put in to bug-hunting and supporting the mods we love to play.

# Craftoria/Mod Bugs

- [ ] Creative Mode search item tab returns no results.
- [ ] Creative Mode search item tab conflicts with JEI search bar. Even if I click on the JEI search bar, characters are typed onto the Search Item tab's search bar.
- [ ] Mekanizm and Mekanizm Generators tabs have search bars in them as well and those function fine; odd that the main vanilla search bar does not.
- [ ] JEI suggested to install Configured to change JEI settings with a GUI. Despite saving my changes in Cheat Mode to turn on "Enable Cheat Mode for Give", leaving and re-entering the GUI shows that change being reverted to default.
- [ ] So relaunching the game shows the changes. However, JEI still does not give me items. Changing the settings from mouse pickup to sending the selected items to inventory did not give the desired result, or any result for that matter.
- [ ] Enabling cheating items into the hotbar with shift+num key doesn't work either.
- [ ] Changed keybinds revert to default when relaunching the game.
- [ ] Crafting an item, in this case a wrench, in an ME system causes a Network Protocol Error and boots me out.
- [ ] Filling a crafting pattern in an ME Pattern Encoder Terminal caused a Network Protocol Error and boots me out also. Notably it takes me back to the multiplayer server list even though I was on singleplayer. Happened when I had a half stack of copper ingots on my cursor and right clicked an empty spot in the pattern.
- [ ] The Pipe Wrench from the Pipez mod is unable to configure the mod's pipes in any way. Other wrenches are able to configure the pipes, however.
- [ ] Wearing the Mekanism Scuba Mask makes your head disappear, both in the world and in viewing your inventory.
- [ ] Building Gadgets' Copy-Paste Tool does not adapt its copied blocks to changes from the copied subject's original position.
- [ ] Sharestones are a bit borked. Trying to interact with one after placing them forces you out of your world.
- [ ] An entity spawning with a passenger and triggering a sculk sensor ([explanation]([url](https://discord.com/channels/570630340075454474/1252708934729470094/1254251928532029451))) causes a client/server desync and forces you to end task to close the game. (<https://mclo.gs/bNaLuhk>) Supposedly a long tick was detected, but no crash.
- [ ] Upgraded the Oven from Cooking for Blockheads with a Heating Unit in order to take in RF instead of coal. It cannot connect to any power cable nor direct contact with power storage blocks.
- [ ] There is a lack of utensils for Cooking for Blockheads in JEI and creative menu.
- [ ] Toaster does not toast toast. Adding to that, there doesn't seem to be any food recipes.
- [ ] Middle-clicking to copy a filled Creative Bin from Mekanizm crashes you; copying a filled Creative Fluid Tank is fine.
- [ ] Potentially missing recipes for Portal Fluid and Unstable Portal Fluid from Just Dire Things. It is required for the Advanced Portal Gun which is craftable.
- [ ] After using the base Portal Gun for a bit, it will eventually crash my game and close my client. Attempting to reenter the world crashes the game again. I think it might be because I was shooting portals near or into each other.
- [ ] Portable Crafting Table can randomly become "wonky"
- [ ] Armor Bar doesn't hide when the HUD is disabled (Ex: F1)
- [ ] Armor hud is squished for half armor and no armor pips
- [ ] Sometimes crafting table eats my items while crafting. I experienced it trying to craft the pipez wrench via REI, and separately when using some of the crafting shortcuts (like dragging items in the crafting grid). Happened with Crafting Table on a Stick and regular Crafting Table.
- [ ] Random crashes when moving items around in the crafting grid of an ME Crafting Terminal. I experienced it when crafting a barrel and moving the slabs/planks around
- [ ] Pipez pipes do not drop when broken


# *FIXED BUGS*
- [x] Upon trying to view a multiblock hologram of a Modern Industrialization machine by holding a Wrench, it shows a runaway hologram whose movements correspond with the player movements but with different axis. ASDW is forward, backward, left, right respectively when walking. If player moves in the are, the movements of the hologram are inverted.
- [x] JEI using the wrong screen GUI for Anvil Recipes
- [x] Trim on Tools causes other Trims to not load tooltips.
- [x] AE2 Spatial Anchor Loaded Chunk Visualization Bug
- [x] Shoving a villager into the Auto Trader from the Easy Villagers mod causes a crash and closes the client.
- [x] Hammers from Just Hammers uncraftable due to missing recipes (fixed by mod author in next release)
