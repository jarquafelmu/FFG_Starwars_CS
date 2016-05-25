# Roll20 FFG Star Wars Character Sheet

## Change log
* 5.0.4.0
  * Finished adding collapsing sections to the Character, companion and NPC sheets.
  * Next update to add collapsing sections to the Vehicle and Group sheets on the player handouts.
  * Changed the color of the repeating section buttons to match the color of the table headers to tie them in better with the color scheme of the sheet.
* 5.0.3.0
  * All section headers on the character's tab are now collapsible where it makes sense. If you see a click cursor on a section header you can collapse it. This should make it much easier to assess what information is available.
  * Removing reliance on break tags where possible allowing for a more natural flow of the document as items are added to repeating sections.
  * Brought the initiative section's look and feel up to the level of the other sections.
  * **Warning** Since the old vehicle section has been officially deprecated for a while I will be removing it in its entirety soon. If you haven't transferred your data by now the attributes that contain them now will still contain them then but you will have to go to the attributes on the attributes page yourself and get the data.
  * Dice pool and destiny section can also be collapsed on the Character, NPC and GM pages.
* 5.0.2.0
  * NPC sections headers are now collapsible when there is more than one section header on a page
* 5.0.0.1
  * Fixed npc sheet's collapse sections
  * Added expense field to group resources
* 5.0.1.0
  * All section headers on the -DiceRoller sheet are now collapsible by clicking on their name
  * Force powers should be working and pulling from the right sources
  * Expanded the companion skills to a full skill section
* 5.0.0.0
  * New NPC sheet for gm's to use in order to make creating npcs easier
  * Fixed companion initiative
  * Fixed character and companion weapon attachment
  * Added more upgrade slots to force powers for character and companion
  * Fixed spacing for armor header
  * Changed tab clicked and neutral colors to make them easier to read and understand
  * Fixed hitbox for long selectors (thanks Vince!)
  * The footer visibility can now be toggled but it will stay to assist people in getting the help they need
  * Reverted the initial class and specialization to a text box until roll20 supports the DataList HTML5 tag
* 4.0.4.12
  * Added optgroups to companion career and specialization
  * Fixed initiative not handling custom items well
  * Fixed Lightsabers not rolling when used as combat skills (thanks Tim P.)
  * Fixed critical rolls going below 1 and failing to output. Critical rolls will now always result in a minimum of 1.
  * Added page footer
* 4.0.4.11
  * Closed some html tags that weren't properly closed.
  * Added Medicine to weapons
  * Added three more attachment slots to weapons as a stop gap before I can get them turned into an actual repeating table.
* 4.0.4.10
  * Added the ranged (light) and ranged (heavy) skills to the available skills for the force powers
  * Added resilience to the weapons dropdown skills to account for the ithorian race being able to bellow
  * Changed the first career and specialization to be a dropdown.
  * Characters, Companions, Beasts, Starships, and Planetary Vehicles all have working separate critical tables now
