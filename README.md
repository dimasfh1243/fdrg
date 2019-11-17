# Foundry VTT Module Repository

[![Build Status](https://travis-ci.org/foundry-vtt-community/modules.svg?branch=master)](https://travis-ci.org/foundry-vtt-community/modules)

Foundry modules that work across all or most systems are noted here.  These may include reskins, general improvement mods, and more.

To clone this repository, along with every module in it, use the following command:

```
git clone --recurse-submodules https://github.com/foundry-vtt-community/modules.git
```

Instead, if you'd like to clone this repository and only fetch a specific module from it, use the following commands:

```
git clone https://github.com/foundry-vtt-community/modules.git
cd modules
git submodule init
git submodule update name-of-the-module
```


<!--tl=2-->
<!--ts-->
   * [Foundry VTT Modules (Universal)](#foundry-vtt-modules-universal)
      * [Actually Private Rolls](#actually-private-rolls)
      * [Always Show Notes](#always-show-notes)
      * [Anvil Menu](#anvil-menu)
      * [Arcane Viewing](#arcane-viewing)
      * [Chat Autoloader](#chat-autoloader)
      * [Combat Utility Belt (Beta)](#combat-utility-belt-beta)
      * [Cursor Hider](#cursor-hider)
      * [Deselection](#deselection)
      * [Installation](#installation)
      * [Foundry 0.4.0 Update](#foundry-040-update)
      * [License](#license)
      * [Dice Calculator](#dice-calculator)
      * [Discord Rich Presence](#discord-rich-presence)
      * [Display Mode](#display-mode)
      * [Entity Order](#entity-order)
      * [FFG Roller](#ffg-roller)
      * [Foundry Patrol](#foundry-patrol)
      * [Foundry Pin](#foundry-pin)
      * [The Furnace](#the-furnace)
      * [Grid Scaler](#grid-scaler)
      * [Image Previewer](#image-previewer)
      * [(Journal Drag)](#journal-drag)
      * [Journal Enhancer](#journal-enhancer)
      * [Layer Hotkeys](#layer-hotkeys)
      * [Less Fog](#less-fog)
      * [Maestro](#maestro)
      * [Message Age Restriction](#message-age-restriction)
      * [No Token Animations](#no-token-animations)
      * [Patches by trdischat](#patches-by-trdischat)
      * [Permission Viewer](#permission-viewer)
      * [Pings](#pings)
      * [Playlist Import](#playlist-import)
      * [Popout!](#popout)
      * [Pointer](#pointer)
      * [Search Anywhere](#search-anywhere)
      * [SVG Loader](#svg-loader)
      * [Tiles Browser](#tiles-browser)
      * [VTTA Tokenizer](#vtta-tokenizer)
      * [Token Mold](#token-mold)
   * [Foundry VTT Modules for DnD 5E](#foundry-vtt-modules-for-dnd-5e)
      * [Better NPC Sheet 5e](#better-npc-sheet-5e)
      * [Better Rolls for 5e](#better-rolls-for-5e)
      * [Beyond 20](#beyond-20)
      * [Chat Damage Buttons](#chat-damage-buttons)
      * [Chat Damage Buttons - Better Rolls Edition](#chat-damage-buttons---better-rolls-edition)
      * [Chat Damage Buttons - Beyond20 Edition](#chat-damage-buttons---beyond20-edition)
      * [DDB Popper](#ddb-popper)
      * [DnD Beyond Character Importer](#dnd-beyond-character-importer)
      * [Favourite Item Tab](#favourite-item-tab)
      * [Group Roll](#group-roll)
      * [Item Sheet Buttons](#item-sheet-buttons)
      * [Item Collection](#item-collection)
      * [Minor QOL Improvements](#minor-qol-improvements)
      * [Loot Sheet NPC (5e)](#loot-sheet-npc-5e)
      * [NPC Browser](#npc-browser)
      * [Polyglot](#polyglot)
      * [Polymorpher](#polymorpher)
      * [Roll20 Converter](#roll20-converter)
      * [Roll20 NPC Importer, for 5e](#roll20-npc-importer-for-5e)
      * [Sky's 5th Edition Dungeons &amp; Dragons Sheet](#skys-5th-edition-dungeons--dragons-sheet)
      * [Spell Browser](#spell-browser)
      * [SRD Bestiary Module](#srd-bestiary-module)
      * [VTTA Party](#vtta-party)
      * [Dynamic Items](#dynamic-items)
   * [Foundry VTT Modules for WFRP 4E](#foundry-vtt-modules-for-wfrp-4e)
      * [Arcane Marks &amp; Careers](#arcane-marks--careers)
   * [Foundry VTT Modules (Defunct)](#foundry-vtt-modules-defunct)
      * [Encumbrance Variant](#encumbrance-variant)
      * [FVTT-Party (Discontinued, see VTTA-Party for an successor)](#fvtt-party-discontinued-see-vtta-party-for-an-successor)
      * [GM Roll Message](#gm-roll-message)
      * [Infinite Folders](#infinite-folders)
      * [Z Order (functionality integrated into core)](#z-order-functionality-integrated-into-core)
   * [Appendix](#appendix)
      * [Appendix A: Adding a Module](#appendix-a-adding-a-module)
      * [Appendix B: Best Editing Practices](#appendix-b-best-editing-practices)
<!--te-->

# Foundry VTT Modules (Universal)

Foundry modules that work across all or most systems are noted here. These may include reskins, general improvement mods, and more.

## [Actually Private Rolls](Foundry%20VTT%20Modules%20%28Universal%29/Actually-Private-Rolls.md)
Hides Private GM Rolls completely rather then just obfuscating the result.

## [Always Show Notes](Foundry%20VTT%20Modules%20%28Universal%29/alwaysshownotes.md)
Sets the Display Notes toggle to true by default

## [Anvil Menu](Foundry%20VTT%20Modules%20%28Universal%29/foundry-vtt-anvil-menu.md)
Adds a context menu to Foundry's Anvil logo in the top left of the screen. This module adds entries to the menu to put the application into Fullscreen mode, as well as providing the ability to toggle the visibility of the main UI components.

## [Arcane Viewing](Foundry%20VTT%20Modules%20%28Universal%29/Arcane%20Viewing.md)
Arcane Viewing adds Audio/Video conferencing support directly from within FVTT.

## [Chat Autoloader](Foundry%20VTT%20Modules%20%28Universal%29/chat-autoloader.md)
This module improves loading times by only rendering the last few chat messages at page load. Older messages will automatically get rendered while scrolling to the top. (This behaviour is similar to e.g. scrolling in Discords chat)

## [Combat Utility Belt (Beta)](Foundry%20VTT%20Modules%20%28Universal%29/beta.md)
You can read more about the module in the README @ (https://github.com/death-save/combat-utility-belt/tree/beta).

## [Cursor Hider](Foundry%20VTT%20Modules%20%28Universal%29/Project%20Repository%20%26%20Readme.md)


## [Deselection](Foundry%20VTT%20Modules%20%28Universal%29/deselection.md)
This module lets the GM deselect a token or tokens by clicking anywhere on the map.

## [Dice Calculator](Foundry%20VTT%20Modules%20%28Universal%29/foundry-vtt-dice-calculator.md)
This module turns the d20 icon near the chat prompt into a clickable link that opens up a new dice calculator dialog. The dice calculator includes buttons for dice, numbers, attributes for the selected token, and simple math. In addition, it includes support for inline dice rolls, such as `[[2d6 + @abil.str.mod]]` in chat. [Screenshot of the calculator can be found here.](https://i.imgur.com/53XmxEN.png)

## [Discord Rich Presence](Foundry%20VTT%20Modules%20%28Universal%29/FoundryVTT-Discord-Rich-Presence.md)
Enables Discord Rich Presence and Invites for http://foundryvtt.com/

## [Display Mode](Foundry%20VTT%20Modules%20%28Universal%29/displaymode.md)
This module makes it so that when you click the anvil in the top left of the screen, the sidebar in Foundry is hidden.

## [Entity Order](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-entityorder.md)
This Foundry VTT module allows you to re-order entities (Actors, Scenes, Items and Journal entries).

## [FFG Roller](Foundry%20VTT%20Modules%20%28Universal%29/FFG-Roller.md)
This adds a simple dice rolling window for the special dice used in Fantasy Flight Games Star Wars RPG and Genesys.

## [Foundry Patrol](Foundry%20VTT%20Modules%20%28Universal%29/foundry-patrol.md)
TLDR: Create token automated token patrols

## [The Furnace](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-furnace.md)
The Furnace is an essential part of every Foundry. This Foundry VTT module brings Quality of Life Improvements to the VTT.

## [Grid Scaler](Foundry%20VTT%20Modules%20%28Universal%29/scaleGrid.md)
This mod allows you to resize a grid more easily within Foundry, allowing easier map setup when a grid is uneven or unclear within a background image.

## [Image Previewer](Foundry%20VTT%20Modules%20%28Universal%29/image-previewer.md)
A little app to preview images on hover in the file picker menu.

## [(Journal Drag)](Foundry%20VTT%20Modules%20%28Universal%29/journal-drag.md)
This module allows you to drag things into your journal entries (while they are being edited) and to drag journal links to the map (actors) or to characters (items) or to other journal entries.

## [Journal Enhancer](Foundry%20VTT%20Modules%20%28Universal%29/journal-enhancer.md)
This module adds a search function for journal entries, includes a “jump to pin” button for moving the camera to a pinned journal entry, adds a zoom function for image handouts, and hides the name of a handout to users without permissions set. Moerill includes a video showing off the mod’s utility here: [https://youtu.be/5O4yA8Kr6bs](https://youtu.be/5O4yA8Kr6bs)

## [Layer Hotkeys](Foundry%20VTT%20Modules%20%28Universal%29/layer-hotkeys.md)
This module adds hotkeys for switching layers and the active tool in canvas.

## [Less Fog](Foundry%20VTT%20Modules%20%28Universal%29/lessfog.md)
Module to enhance visibility for the GM in Foundry VTT.

## [Maestro](Foundry%20VTT%20Modules%20%28Universal%29/maestro.md)
A quality of life audio-focused module for Foundry Virtual Tabletop.

## [Message Age Restriction](Foundry%20VTT%20Modules%20%28Universal%29/messageagerestriction.md)
A Foundry VTT Module to enable filtering chat-messages by their age. Each user can choose his own settings. It is possible to set the maximum age (in days) and to specify if the filter should be applied.

## [No Token Animations](Foundry%20VTT%20Modules%20%28Universal%29/No%20Token%20Animations.md)
Adds an option to the settings dialog to disable token movement animations. Tokens will drop immediately instead of sliding when dragged and dropped around the map with this setting enabled.

## [Patches by trdischat](Foundry%20VTT%20Modules%20%28Universal%29/patches.md)
Module to apply the following patches to Foundry VTT:

## [Permission Viewer](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-permission-viewer.md)
This Foundry VTT module displays colored diamonds/squares/circles to represent the players who have limited/observer/owner permissions on Entities (Actors, Journal entries, Items, etc..)

## [Pings](Foundry%20VTT%20Modules%20%28Universal%29/pings.md)


## [Playlist Import](Foundry%20VTT%20Modules%20%28Universal%29/playlist_import.md)
This module aims to simplify the process of adding multiple music tracks to Foundry VTT, doing so in a timely manner.

## [Popout!](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-popout.md)
This Foundry VTT module lets you pop out journal entries into their own windows. It is currently acting as a proof of concept.

## [Pointer](Foundry%20VTT%20Modules%20%28Universal%29/pointer.md)
This module adds the ability for each user to show a cursor following his mouse as well as adding the option to ping a certain location.

## [Search Anywhere](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-search-anywhere.md)
A FoundryVTT Module that adds a way to quickly search for any entity by name via a handy auto-complete widget.

## [SVG Loader](Foundry%20VTT%20Modules%20%28Universal%29/svg-loader.md)
This module allows to load walls, lights and sources through .svg files, provided e.g. by DungeonFog.

## [Tiles Browser](Foundry%20VTT%20Modules%20%28Universal%29/tiles-browser.md)
Adds a browser to the tiles layer to conveniently preview and then drag and drop tiles onto the scene. Providing additional features to manipulate tile rotation and size while dragging.

## [VTTA Tokenizer](Foundry%20VTT%20Modules%20%28Universal%29/VTTA%20Tokenizer.md)
Tokenizer provides the user with:

## [Token Mold](Foundry%20VTT%20Modules%20%28Universal%29/token-mold.md)
What is a foundry without its molds? This module provides you with a customizable mold for your Tokens.

# Foundry VTT Modules for DnD 5E

Foundry modules that work within Dungeons and Dragons 5th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, and much, much more.

## [Better NPC Sheet 5e](Foundry%20VTT%20Modules%20for%20DnD%205E/BetterNPCSheet5e.md)
This module overwrites the default NPC sheet that comes shipped with the dnd5e system and brings it closer to the well known official template. It also includes functionality supporting separation of action categories (legendary actions, actions, reactions, etc.), and features the ability to expand and view the description of the ability/action in-sheet.

## [Better Rolls for 5e](Foundry%20VTT%20Modules%20for%20DnD%205E/FoundryVTT-BetterRolls5e.md)
This module modifies certain sheet functions on Foundry VTT Character sheets for D&D 5th Edition. Currently, it adds compound rolls (for attack rolls and damage rolls combined), as well as "dual rolls" for all attacks, ability checks, and saving throws, rolling 2 d20s side-by-side in a single chat message. Additionally, it allows for "extra damage" rolls and configurable quick rolls for each item that can show desired details & rolls of an item on the sheet whenever it's clicked. On top of all this are a few options to customize layout and enable/disable certain features of the module.

## [Beyond 20](Foundry%20VTT%20Modules%20for%20DnD%205E/Beyond20.md)
This module allows you to use and roll sheets in DnD Beyond, and have those results displayed in Foundry VTT. For more details, see Kakaroto’s module page and readme files.

## [Chat Damage Buttons](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt---chat-damage-buttons.md)
This module replaces the right-click context menu with buttons on the dice-roll chat message. This allows for quicker application of damage/healing.

## [Chat Damage Buttons - Better Rolls Edition](Foundry%20VTT%20Modules%20for%20DnD%205E/Better%20Rolls%20for%205e.md)
A small module to add "Apply Damage" buttons to Red Reigns Better Rolls 5e Module, based on hookings Chat Damage Buttons.

## [Chat Damage Buttons - Beyond20 Edition](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt-chatdamagebuttons-beyond20.md)


## [DDB Popper](Foundry%20VTT%20Modules%20for%20DnD%205E/ddb-popper.md)
Opens a D&D Beyond popup for a linked actor.

## [DnD Beyond Character Importer](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt-modules.md)
This module allows you to import character data from DnD Beyond into Foundry Virtual Tabletop.

## [Favourite Item Tab](Foundry%20VTT%20Modules%20for%20DnD%205E/favtab.md)
Adds a Favourite tab to display a customized list of items, feats and spells. Usable with the default dnd5e Character sheet. You can add any item from the inventory, spell book or feature section of the character sheet. This module also gives access to item charges. You can add these to any item on the favourite list or remove them by changing the maximum to 0. This uses the same data that is used by Moerill#7205's adnd5e module, since this data is not supported by default.

## [Group Roll](Foundry%20VTT%20Modules%20for%20DnD%205E/grouproll.md)
Implements group ability and skill check rolls per Player's Handbook, page 175: "*If at least half the group succeeds, the whole group succeeds.*" Modules also includes patches to implement the Halfling Lucky trait, and a house rule to use the average of 2d20 for normal skill and ability check rolls. Both of these patches can be disabled in config.js. All patches rely on the included `patchClass` utility function.

## [Item Sheet Buttons](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt---item-sheet-buttons.md)
This module adds item card buttons into the description of items, so that the item cards do not need to be pinged in chat. It does have the side effect of making it harder to ping item descriptions within chat.

## [Item Collection](Foundry%20VTT%20Modules%20for%20DnD%205E/itemcollection.md)
This module allows the creation of bags which can contain other items, think backpack or bag of holding. These items can be put anywhere an item can.

## [Minor QOL Improvements](Foundry%20VTT%20Modules%20for%20DnD%205E/minor-qol.zip.md)
Adds item deletion confirmation, accelerated dice rolls with attack and damage in one click and item info hiding. All features can be enabled/disabled from the in-game module settings. If enabling/disabling speed-item-rolls you should reload the browser window.

## [Loot Sheet NPC (5e)](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt---loot-sheet-npc.md)
This module adds an additional NPC sheet which can be used for loot containers such as chests. It also allows spells to be automatically converted into spell scrolls by dragging them onto this sheet.

## [NPC Browser](Foundry%20VTT%20Modules%20for%20DnD%205E/npc-browser.md)
This module adds a search interface for actors. This enables more comfortable browsing and searching via predefined filters like challenge rating, type or ability score.

## [Polyglot](Foundry%20VTT%20Modules%20for%20DnD%205E/fvtt-module-polyglot.md)
Talk to others using a language your selected character can understand and scrambles in-character text you can't understand.

## [Polymorpher](Foundry%20VTT%20Modules%20for%20DnD%205E/polymorpher.md)
A module for Foundry VTT that lets you polymorph characters into any other character! Just drag any Actor (NPC or Character) on top of another Actor to change the later into the prior. Support dropping both from Compendium or the sidebar.

## [Roll20 Converter](Foundry%20VTT%20Modules%20for%20DnD%205E/Roll20%20Converter.md)
This module imports most facets of a campaign, including scenes, dynamic lighting, basic sheet information, and more. It currently does not include thorough actor information (either for PCs or NPCs), or items. Bear in mind that exporting a campaign from Roll20 may violate the EULA.

## [Roll20 NPC Importer, for 5e](Foundry%20VTT%20Modules%20for%20DnD%205E/roll20npcimporter.md)
This module allows for the importing of NPCs from Roll20, through use of JSONs exported via [VTT Enhancement Suite](https://ssstormy.github.io/roll20-enhancement-suite/). This import currently only supports NPCs created in the Roll20 OGL or Shaped version sheets. This module supports the Better NPC Sheet 5e, as well as the aDnD5e sheet in tagging actor items according to abilities, reactions, legendary actions, etc. To install, first download the module, unzip it into `/public/modules`, and then restart Foundry while it is running.

## [Sky's 5th Edition Dungeons & Dragons Sheet](Foundry%20VTT%20Modules%20for%20DnD%205E/sky5e.md)
This module provides a variant layout of the Core 5e Character Sheet in Foundry as well as providing some upgrades to various sections of the sheet.

## [Spell Browser](Foundry%20VTT%20Modules%20for%20DnD%205E/Spell-Browser.md)
This module adds a search interface for spells. This enables more comfortable browsing and searching via predefined filters like spell level, class or damage type.

## [SRD Bestiary Module](Foundry%20VTT%20Modules%20for%20DnD%205E/SRD%20Bestiary%20Module.md)
This module includes each SRD NPC in 5th edition, imported into Foundry VTT. This includes all of their features, immunities/resistances/vulnerabilities, actions, and much, much more. Other than lacking token images (token images do not appear to be part of the SRD), each NPC is built and ready for use in Foundry Virtual Tabletop. Included in the module is a folder containing each individual NPC json, in case you wish to experiment with importing them, or future updates break the NPCs in this module. These can be imported individually using the Roll20 NPC Importer, for 5e module.

## [VTTA Party](Foundry%20VTT%20Modules%20for%20DnD%205E/VTTA%20Party.md)
Successor to fvtt-party, which is discontinued as of now. Provides both an overview about the party in regards to AC, HP, and passive perception/investigation/insight and adds tooltips for the actors of the currently active scene.

## [Dynamic Items](Foundry%20VTT%20Modules%20for%20DnD%205E/dynamicitems.md)
Dynamic items are ones that makes changes to your stats/modifiers when they are active in your inventory. This module is really intended for player characters and NPCs that have linked tokens.

# Foundry VTT Modules for WFRP 4E

Foundry modules that work within Warhammer Fantasy Roleplay 4th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, changes to roll tables, etc.

## [Arcane Marks & Careers](Foundry%20VTT%20Modules%20for%20WFRP%204E/Arcane-Marks-Careers-FVTT.md)
[This homebrew](https://drive.google.com/file/d/1uTy2r0EDMdcISFqqyxeIOSadtzz-OTAg/view) supplement I made adds Lore specific careers and marks for WFRP4e.

# Foundry VTT Modules (Defunct)

Foundry VTT modules that no longer work are noted here. Modules included here have been defunct for at least one month. This exists to help document previous work on Foundry Virtual Tabletop by the community, as well as to exist as a record for anyone who chooses to remain on a previous version of Foundry VTT.  

## [Encumbrance Variant](Foundry%20VTT%20Modules%20%28Defunct%29/foundry-vtt---encumbrance-variant-5e.md)
This module modifies how the encumbrance bar in the actor sheet is displayed to distinguish the different levels of encumbrance when using the variant rules in **PHB pg. 175**. It does not currently support the Powerful Build feature, as doing so would require extending the base Actor5eSheet class.

## [FVTT-Party (Discontinued, see VTTA-Party for an successor)](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-party.md)
This module adds a convenient button to the actor’s tab, which will track the HP, AC, and Passive Perception, Investigation, and Insight of tokens on the Canvas. Currently a WIP, and may exhibit some bugs.

## [GM Roll Message](Foundry%20VTT%20Modules%20%28Defunct%29/gmrollmessage.md)
Sends an extra public message/hint when rolling a `gmroll` or `blindroll`.

## [Infinite Folders](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-module-infinite-folders.md)
This Foundry VTT module allows you to create infinite depth of folders for Scenes, Actors, Items and Journals. No more limit to a depth of 2 folders (or none for Journal entries). This will also add a `New entity` button on folders so you can create it directly in the folder (does not work for Scenes though).

## [Z Order (functionality integrated into core)](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-module-zorder.md)
This Foundry VTT module lets you send tiles to the front or the back of the scene.

