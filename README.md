# Craftoria-Neo-Bug-Tracker

Do you wish to help us? You won't be just helping in the production of Craftoria, but also in the development and bug tracking of all the mods freshly ported to 1.21 Neoforge.

Different scenarios and what to do:
- If you have a new bug, make a PR and add it to the list. Any evidence for it would be nice, supplying a link to the github assets link next to the bug bullet point. With each bug, right after the `-` add `[ ] [ ]`. This will create TWO check mark boxes. The first one is to mark a bug as "reported," the second is to mark it as "fixed." 
- If you reported a bug, make a PR to mark the first box of the bug with an `x`, making it `[x] [ ]`, along with the link to the bug report on the mod's repository at the end of the line.
- If you noticed a bug has been fixed, make a PR to mark the second boxy of the bug with an `x`, making it `[x] [x]`, along with the link to the bug fix on the mod's repository at the end of the line.

Preferably, all of these links should be masked by using the following format: `[Report](url)` and `[Fix](url)`.
# Craftoria/Mod Bugs

- [ ] Creative Mode search item tab returns no results.
- [ ] [ ] Creative Mode search item tab conflicts with JEI search bar. Even if I click on the JEI search bar, characters are typed onto the Search Item tab's search bar.
- [ ] [ ] Mekanizm and Mekanizm Generators tabs have search bars in them as well and those function fine; odd that the main vanilla search bar does not.
- [ ] [ ] JEI suggested to install Configured to change JEI settings with a GUI. Despite saving my changes in Cheat Mode to turn on "Enable Cheat Mode for Give", leaving and re-entering the GUI shows that change being reverted to default.
- [ ] [ ] So relaunching the game shows the changes. However, JEI still does not give me items. Changing the settings from mouse pickup to sending the selected items to inventory did not give the desired result, or any result for that matter.
- [ ] [ ] Enabling cheating items into the hotbar with shift+num key doesn't work either.
- [ ] [ ] Changed keybinds revert to default when relaunching the game.
- [ ] [ ] Crafting an item, in this case a wrench, in an ME system causes a Network Protocol Error and boots me out.
- [ ] [ ] The Pipe Wrench from the Pipez mod is unable to configure the mod's pipes in any way. Other wrenches are able to configure the pipes, however.
- [ ] [ ] Wearing the Mekanism Scuba Mask makes your head disappear, both in the world and in viewing your inventory.
- [ ] [ ] Building Gadgets' Copy-Paste Tool does not adapt its copied blocks to changes from the copied subject's original position.
- [ ] [ ] Sharestones are a bit borked. Trying to interact with one after placing them forces you out of your world.
- [ ] [ ] Approaching a structure (only tested a villager) causes a client/server desync and forces you to end task to close the game. (<https://mclo.gs/bNaLuhk>) Supposedly a long tick was detected, but no crash.
- [ ] [ ] Upgraded the Oven from Cooking for Blockheads with a Heating Unit in order to take in RF instead of coal. It cannot connect to any power cable nor direct contact with power storage blocks.
- [ ] [ ] There is a lack of utensils for Cooking for Blockheads in JEI and creative menu.
- [ ] [ ]Toaster does not toast toast. Adding to that, there doesn't seem to be any food recipes.
- [ ] [ ] Middle-clicking to copy a filled Creative Bin from Mekanizm crashes you; copying a filled Creative Fluid Tank is fine.
- [ ] [ ] Potentially missing recipes for Portal Fluid and Unstable Portal Fluid from Just Dire Things. It is required for the Advanced Portal Gun which is craftable.
- [ ] [ ] After using the base Portal Gun for a bit, it will eventually crash my game and close my client. Attempting to reenter the world crashes the game again. I think it might be because I was shooting portals near or into each other.
- [ ] [ ] Portable Crafting Table can randomly become "wonky"
- [ ] [ ] Armor Bar doesn't hide when the HUD is disabled (Ex: F1)
- [ ] [ ] Armor hud is squished for half armor and no armor pips
- [ ] [ ] Sometimes crafting with the portable crafting table eats items. I experienced it trying to craft the pipez wrench via REI.



# *FIXED BUGS*
- Upon trying to view a multiblock hologram of a Modern Industrialization machine by holding a Wrench, it shows a runaway hologram whose movements correspond with the player movements but with different axis. ASDW is forward, backward, left, right respectively when walking. If player moves in the are, the movements of the hologram are inverted.
- JEI using the wrong screen GUI for Anvil Recipes
- Trim on Tools causes other Trims to not load tooltips.
- AE2 Spatial Anchor Loaded Chunk Visualization Bug
- Shoving a villager into the Auto Trader from the Easy Villagers mod causes a crash and closes the client.



- [ ] test
- [x] a done test


- SUPER DUPER BAD BUG
  - [x] Reported
  - [ ] Fixed
