# Raffadax Complete Production Beta

Updated for Stardew 1.6.14 by [Logo](https://github.com/Rogue-Toast) and [OnionNinja](https://github.com/scriptsforweirdos).

## Before you Begin

* **No redistribution permitted. This means no linking directly to this repository outside of the [Raffadax Discord](https://discord.gg/kVRFBf794c).**
  * **No redistribution of translations, reskins, and similar auxiliary mods based on this version.** If you want to make a mod or translation which expands on this code, please contact in the Discord first.
* **No streaming, videos or other social media sharing of this version.**
* **This version is not compatible with save files from Stardew 1.5.**
* **This version may not be compatible with the next version either although it will probably be OK.**

## About this Beta

* This is released with Raffadax's permission *temporarily* to the public as a stopgap until he finishes making changes for the actual release on Nexus.
  * It's mostly for other devs to get a head start on compatibility tests, translations, reskins, etc before things go live to Nexus.
  * It's been tested by a great group of alpha testers (thanks y'all!) and is fully playable.
* This is the version that Logo and I gave back to Raffadax after updating the code. It's a direct one-to-one patch to make the old version compatible with Stardew 1.6+
* Bugs should be reported as issues here or in the Discord for the time being rather than on Nexus.
* The eventual Nexus release will feature new artwork, more content, etc. It is expected to release towards the end of 2024 or early in 2025.

## How to Download

Look at the Releases section on the right side of this page.

Click the link that says "5.0.0-beta.xx", where "xx" is a pair of numbers. A new page will load.

On the new page, select the link titled "Raffadax 5.0.0-beta.xx.zip".

## Features and Changes

* Everything in the current version of Raffadax Complete Production on Nexus (v.4.3) still in the mod.
* i18n compatible, although only English is provided for now.
  * Translators please contact us in the Discord before starting.
* Removes several dependencies, including Json Assets, Custom Ore Nodes, Custom Cask Mod, Custom Crystalarium Mod, Miller Time, Mail Framework Mod, Produce to Sapling and Shop Tile Framework.
* Graphics have been combined into spritesheets for faster loading.
* Update keys have been configured so that you should be alerted via SMAPI whenever the next version is posted to Nexus.
* Shop prices have been very slightly adjusted to accommodate for the removal of STF.
* Ore node spawns may be slightly different due to the shift from Custom Ore Nodes to Item Extensions but have been tuned to feel relatively similar.
* New config: Seed Maker Saplings. Controls how Orchard Fruits interact with Seed Makers
  * "Better Saplings": Higher quality fruits yield higher quality saplings, which mature faster.
  * "More Saplings": Higher quality fruits yield more saplings. This is the same behavior as the old Produce to Sapling mod.

## Changes For beta.03 (2024 Dec 20)

* Removed MultiYield Crops due to conflict with Spacecore.
* Added Spacecore and Custom Bush as dependencies. Custom Bush is optional for now unless Raffadax decides to do more with it.
* All old MultiYield Crops functions have been moved to Spacecore and Custom Bush.
* With Custom Bush, White Tea Leaves now have a chance to drop from the Tea Bush on the 20 and 21 of the month, Spring/Summer/Fall outdoors, all seasons indoors.
* Minimum Stardew Valley Base Game version is now 1.6.14 with all associated matching mods and frameworks.
* Restored Category Text Overrides via Spacecore.

## Dependencies for all betas

* [SMAPI](https://smapi.io) v4.1.10 or higher
* [Content Patcher](https://www.nexusmods.com/stardewvalley/mods/1915) v2.4.4 or higher
* [Farm Type Manager](https://www.nexusmods.com/stardewvalley/mods/3231) v1.24.0 or higher
* [Item Extensions](https://www.nexusmods.com/stardewvalley/mods/20357) v1.11 or higher, do not use 1.15.0.
* [Producer Framework Mod](https://www.nexusmods.com/stardewvalley/mods/4970) v1.9.6 or higher
* [Custom NPC Exclusions](https://www.nexusmods.com/stardewvalley/mods/7089) v1.6 or higher

## Dependencies for beta.03 and Later

* [Spacecore](https://www.nexusmods.com/stardewvalley/mods/1348) v1.27.0 or higher
* [Custom Bush](https://www.nexusmods.com/stardewvalley/mods/20619) v1.40 or higher (Optional)
* MultiYield crops not required.

## Dependencies for Versions prior to beta.03

* [Multi Yield Crops](https://www.nexusmods.com/stardewvalley/mods/6069) v1.0.3-alpha.20240306
  * Note: this is available under "optional files". Don't pull the first option on the files tab. You want the second option.
* Spacecore and Custom Bush not required.

## Matrix/Spreadsheet

An updated version of the spreadsheet which has been traditionally provided with Raffadax is also available on the Releases page. It's the second file on the list.

## Recommended Mods

The following are not required, but certainly help.

* [Automate](https://www.nexusmods.com/stardewvalley/mods/1063) and [PFMAutomate](https://www.nexusmods.com/stardewvalley/mods/5038)
* [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098) (GMCM)
* [Lookup Anything](https://www.nexusmods.com/stardewvalley/mods/541)
* [Deluxe Grabber Redux 1.6](https://www.nexusmods.com/stardewvalley/mods/20799)
* [Item Bags](https://www.nexusmods.com/stardewvalley/mods/5382) (If you are running with Item Bags, and additional zip file can be pulled from the Releases page. It's the third file on the list.)
* A very large Greenhouse map
* A very large Farm map
