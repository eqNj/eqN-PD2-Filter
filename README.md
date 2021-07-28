# Hello! Stay awhile and listen.

![Ground Loot](https://raw.githubusercontent.com/eqNj/eqN-PD2-Filter/Filter-Sub/Loot.jpg)

This filter is up-to-date for Season 3 of Project Diablo 2!

You can find my loot filter(s) either here or on the Project Diablo 2 game launcher.

If you would like to contact me, find me in the offical PD2 Discord with the name eqN.

There is both a Relaxed (Default) and Strict version of my filter. The differences are subtle and described below at the end of the features section. 

Originally, this was a remastered version of Kryszard's Project Diablo 2 loot filter from Season 1. Now, due to many differences this filter is all its own. I do want to give a big thanks to him for his awesome work on his filter though! 

For those familiar, I have kept many of the features of Kryszard's filter intact. I have added several quality of life features, cleaned up a lot of the syntax and formatting, thoroughly refined the drops shown throughout leveling and endgame, and much more.

This filter is generally less strict than other filters available but still focused. It is especially focused on optimizations as you level and slightly more lenient in the end game by comparison.

This filter is for those of us used to life without one. Those of us who like quality of life improvements but don't want potentially useful items hidden from them.

Solo players, hardcore players, or simply those seeking out less commonly used items for specialty builds may find this filter most useful compared to others. This filter will show you if anything usable, even into the late game, would drop for any class. Period. 

This filter doesn't try to make all the decisions for you. You will see things that you may or may not be inclined to pick up, but it is always reasonable why you're seeing these items. 

My philosophy, and playstyle, have always been that you should be allowed to decide what items are worth picking up for yourself. Knowledge is power.

## Features

![Staff Mods](https://raw.githubusercontent.com/eqNj/eqN-PD2-Filter/Filter-Sub/Staffmods.jpg)

All non-magic (white) items with a relevant amount of plus skills that drop will show those skills in their name, making them easily identifiable at a glance.

All armor pieces of any kind will always show their base defense ranges (in their description) to allow you to know if the item has a "good roll" in this way.

![Socketable](https://raw.githubusercontent.com/eqNj/eqN-PD2-Filter/Filter-Sub/Details.jpg)

All unsocketed, but socketable, items of any kind will show their potential maximum sockets (in their description), accounting for item level. 

If an item is non-magic it will show its maximum potential sockets possible through the Larzuk quest or Cube socket recipe. 

If an item is rare, crafted, set, or unique it will show its maximum potential sockets through corruption specifically. 

Once an item is either corrupted or socketed in any fashion the maximum potential socket information will be removed from the item's description.

![Crafting Ring](https://raw.githubusercontent.com/eqNj/eqN-PD2-Filter/Filter-Sub/Craft.jpg)

All items will show any recipes possible, as applicable. They will use a color-coded symbol (@) matching their respective perfect gem color within the recipe, as seen above.

These recipes will show up once relevant as your character progresses, to help ease new players into this information. I.E.: Non-magic items will show their socketing recipe, if not of superior quality. Magic items will show all possible crafting recipes. Rare, crafted, set, and unique items will show possible upgrade recipes if any are available.

Specifically, socketing recipes will show at item level 21+ (or earlier on any +3 skills items). Upgrading recipes will show at item level 13+. Crafting recipes will show at item level 51+ (as a resulting craft item level of 51 is when you can guarantee at least 3 mods).

![Upgrade Boots](https://raw.githubusercontent.com/eqNj/eqN-PD2-Filter/Filter-Sub/Upgraded.jpg)

All elite tier items are set to show, even after level 80, with only small exceptions for either some class items that are of low plus skill values or unideal weapons with a maximum of 2 sockets or less. 

Rares of all tiers will still show at all levels. This includes all class items (wands, orbs, helms, scepters/maces, staves, claws) and any rare bows or crossbows of all tiers aswell.

Select ethereal and/or magic items from all tiers, those that are best for crafting, will continue to show, and they will be indicated by two gray asterisks, one on each side. High item level magic amulets will show an orange [C] next to them, and once identified will show the exact level best for crafting them to ensure +2 skills rolls are possible.

Four socket, ethereal polearm/spear weapons of all tiers, for use with the Insight Rune Word on lower level characters, will show at all levels.

Any class items with +3 to at least one of any useful skill will always show, regardless of item tier (unless a staff, due to tier-scaling cast speed), as well as any elite class items that could be used for Rune Words.

Descriptions have been added to almost every quest item and/or utility item in the game. These descriptions are either lore tidbits or famous quotes throughout history befitting the items.

Read the "Changelog" further below for more details on the filter's features.

## Relaxed / Strict Filter Differences

The Strict filter has the following changes (after character level 75):

Four socket, ethereal polearm/spear weapons of normal and exceptional tiers are hidden.

Non-magic class items with one socket are always hidden, even with +3 skills.

Non-magic elite items are hidden, unless specifically valuable for use with certain runewords or +3 to a useful skill.

Normal and exceptional magic class items are hidden unless specifically great for crafting.

Normal and exceptional rare items are hidden, with exceptions for: Gloves, boots, belts, ethereal weapons, bows, grim shields, mage plates, circlets, and all class items.

Only high/mid-tier unique and set items will notify on drop, but will still always show.

# Changelog:

## 1.0.0 - (Season 1)

Replaced the word 'Superior' on superior items with an orange + at the front of item names.

All presently showing superior items with Enhanced Defense or Enhanced Damage will show their percentage at all stages of the game.

Stack sizes now only show on item names for stacks > 1.

All possible Rune Words or the method of socketing will show in the description on applicable items at all times, if that item is seen by your character.

Added a description to unsocketed superior items advising they can be socketed only through Larzuk or Corruption.

Ethereal items will be tagged with [e] at the front of their names.

More magic items worth crafting now show up with a gray asterisk crafting base indication, and select few with added alerts.

Reduced the threshold for Enhanced Damage and Increased Resistance paladin shields to be shown.  

Paladin shields with any All Resistance or high Enhanced Damage will now show such ([#r] or [ed]) behind their names instead of in front.  

Potion names have been greatly shrunk across the board, and greater mana potions will still show in Hell.

Restructured item name formatting to help reduce visual clutter.  

Shortened skill names shown on dropped white class items to help reduce visual clutter.  

Removed exact item prices, and instead replaced a green $ indicator (like Wolfie's filter) on identified rares if they sell for maximum value for each respective difficulty.  

Item level 88+ amulets will be marked [C] to indicate they're desired for crafting (like Wolfie's filter), and they will tell you what level to craft them at for +2 class skills.  

All circlets of all tiers will always show, except if they are lower tier, white, and ethereal and/or socketed (unusable for imbuing).  

All circlets will show the ideal level to imbue them for +2 to class skills in their description.  

All Runes of all tiers, all uniques, and any decent set items will continue to alert you on drop at all levels.    

Corrected and reduced any incorrect or unnecessary vocabulary in item descriptions and improved the overall visual experience.  

Re-optimized the filter's structure to make editing easier and cut back on some redundancies.

## 1.1.0 - (Season 2)

Multi-line item names are impossible as of 3/29/21.

All uniques and runes previously using multi-line item names will look otherwise identical and still use spacing to increase their name size.

Plus skills on items will still be listed, though shortened, in dark green text next to applicable item names. (As seen above, in the Features section)

Items with only plus 1 to a skill will not show such in their names after character level 30. These items will still show up on the ground as normal, until character level 80+ where any non-elite bases are required to have plus 3 to atleast one useful skill to show.

I find this the easiest way to maintain item plus skill legibility at a glance, though I am open to any suggestions on how to improve this new system.

All elite items will continue to show past level 80 as normal.

Details from 'The Arreat Summit' about Base Defense ranges and maximum potential sockets (dynamic with item level) have been added to all item descriptions where possible/applicable. The max sockets shown on Unique, Crafted, Set, and Rare items will be the maximum amount possible through a corruption. As soon as an item has any sockets it will stop showing the max sockets that were possible.

(Big thanks to TheIrateSeaGoer for his work on the Arreat Summit details!)

Crafting recipes will now only show on identified magic items with item level 51 or higher. 

Worth note: when crafting, base item level 51+ and character level 51+ ensures a minimum of three additional affixes on the resulting item.

All unidentified magic items marked as ideal for crafting (two gray asterisks, one on each side) do so based on when they meet the item level (assuming same character level or higher) for either 4 guaranteed additional affixes (level 71) and/or in rare cases when their most relevant affixes become available before then.

Replaced the word 'Inferior' (Crude, Cracked, etc.) on inferior items with a blue - sign at the front of item names. 

(Inferior items are only viewable before level 30 and only if they have + to skills.)

Further refined the leveling experience to continually show useful items while de-cluttering across a gradient of character progression at all stages.

Added quest item lore and quotes.

## 1.2.0 - (Season 3)

Made it so ALL rares will now show, regardless of tier, at ALL levels. 

If this is deemed excessive I will cut it down to how it was previously (showing select ethereal rare weapons and/or ideal rare armors).

Changed the Perfect Gem icon from "O" to "@" to help further distinguish it.

Changed the Flawless Gem icon from "O" to "*" to help further distinguish it.

Change the Gem icon for all gems of lower tiers from "*" to ":" to further distinguish them.

Made it so Large Charms (just as Small and Grand did priorly) will now notify on drop.

Added detailed information to charm names for Large Charms with new % Damage stats.

Added all new uniques added to the game for Season 3 as particularly highlighted drops.

Made it so magic (for crafting) and non-magic (with druid plus skills) clubs of all tiers will always show on drop.

Added new Vampiric and Bountiful crafting recipes to magic item descriptions.

Added the new Pandemonium Tailsman.

Some jewels that are good for LLD (Low Level Dueling) will indicate such once identified.

Made it so "Base Defense: X-X" and "Max Sockets: X" are now on separate lines in item descriptions.

Tidied up and added all new/changed runewords to applicable socketed item types.

Narrowed down some parameters to show non-magic staves at higher levels now due to staves having a scaling implicit cast speed bonus based upon tier.
