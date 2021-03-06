The Heirs to Aquitania
A total conversion mod by Savs
Based on the HtA megacampaign

Features a new world with nearly 800 years of different history (mostly as determined by the computer in CK2 and EU3)
Development has been in fits and spurts since June 2014. The mod is based on /gsg/Vickymod v1.06, which was popular at that time. It is not based on PDM, nor on HPM/HFM.
If you want to contact me, find me on reddit as /u/Savolainen5 or on the Paradox forums as Savolainen5

Also check out http://www.reddit.com/r/savs, where history and other stuff are posted. However, please direct discussion about the mod to the thread as much as possible, in keeping with Paradox rules.
Forum thread for the mod: https://forum.paradoxplaza.com/forum/index.php?threads/the-heirs-to-aquit%C3%A0nia-altervicky-mod.895808/
Vic 2 Modding Discord Server: https://discord.gg/EbY7qaA (Hosts discussion and updates for a lot of mods)
HtA Discord server: https://discord.gg/beteEPF (not in active use, use the above Vic 2 Modding server instead)

There's an event numbers list at the bottom of this file

Feel free to use anything from this mod without asking me. Please do attribute it/credit me, though.

Thanks to:

- /u/ChortlingGnome, who contributed A LOT for Hispania, China, and other things
- /u/capitanloco6 / MajorMajor, who wrote events and decisions regarding French ambitions in the Holy Land and the dismantling of Persia, as well as giving some flags and fixing Catalan military/party names
- /u/firenine09, /u/1tobedoneX, and /u/Sommern, for being a sounding board and giving many good ideas and flags
- /u/_Rosseau_, for the new Norway flags. Incorporated with permission
- /u/Rangerage, who did a lot of POP rebalancing in BYZ/ARM based off of my EU3 save
- /u/Flapjack731 for ideas and content contribution
- Rylock and contributors to the excellent NNM, off of which so many mods are based
- Developers of /gsg/Vickymod (Hisuibro, Finnbro), on which my mod is mostly based - v1.06 (itself based on NNM) - Its changelog is included among the files here
- Developers of and contributors to the Improbable Nations Mod, Community Made Countries mod, ParadoxPlaza Mod, the Symbols Flagpack (Chandlerw1) for flags and code for decisions and events
- Attalus and other developers of Divergences of Darkness for ideas, code, flags
- Naselus and other PDM folks, from whose mod I took some decisions, events, ideas, and inspiration
- arkhometha for his Historical Project Mod, from which I have taken many pictures, ideas, a good bit of country information, and some events and decisions
- EGaffney for his Rectangular Flag Frames Mod
- RenatoDS for his RDS mapping project, which creates a more detailed world map (for terrain and rivers)
- simsulla for his help in sorting out adding canals and for (passively) showing me the crucial last step for adding new provinces - making the default.map file point to your mod's directory. See my copy for more details
	- Also for passively showing me how to make music in a mod work
- Hammonia for his work on the beautiful HFMmm map, which I used in 0.36 to update the map
- /u/rascalnag / Squidward Tortellini for significant support in making the map look more like what I want
- Shatterfury, Lukesky, Skyhascheese, Necro991, Rioting Soul, Spudgun, and Athemos for their ideas, flags, sounding board-ness, testing, and feedback 
- BobSagini for MANY flags, ideas, and hooking me up with Vic1 music
- dreamonceh for pointing out that you can set some AI behaviour in OOBs
- Ahearne for suggestions, improvements, and help with Eire
- Crushric for Roman POP rework and other contributions and ideas
- Over421 for Greek-language parties and flags
- Discux for parties for lots of New World countries
- Rennes for showing me how $ORDER$ works in war localization
- Jorde for testing help

NB for the changelog - Anything with lots of # or * after it is something Savs is still working on or hasn't gotten fully/correctly implemented yet

**CHANGELOG**

Verison 0.37 - Poland and Italy

Major
- Added a new government type, the Provisional Government (which comes in yes_election and no_election forms according to whether elections are allowed, obviously) which is used for PDN initially and can be used for other countries in the future
- Also added events to switch between them based on the vote franchise
- Pan-nationalist rebels will not rise if their cultural union doesn't exist - THIS MAY NEED TO BE ADJUSTED SO THAT ONLY GERMAN ONES WON'T RISE (because I'm OK with French ones, for example)
- Added an event for SML to lose control of its Black Sea provinces if it's at peace and neither UKR nor DON are its vassals/owned by it (the check is based on four major provinces in different states close to the land)
- Added a decision for RUS to break the truce and just go capture the city of Smolensk if they have basically no military. It costs more infamy, but has the same end result as the other two ways to end the conflict

Minor
- Some more starting generals - thanks to MajorMajor
- Many new flags (both default and alternate) - thanks to Athemos for most of them
- Netherlands' Integrate Wallonia decision now gives a core, too
- Added the Prusai culture, Baltic-speaking remnants of the Old Prussians, to the Polish-Lithuanian border region, along with a country for it - Prusova (tag PRS)
- Added (army) unit files from HFM
- Changed some country colours: CYR, EGY, MGH, LUZ 
- Made it so Brunswick doesn't have a core on Emden, meaning that they should be able to do the decision chain before Germany forms
- Brabant should no longer sell its islands in Oceania/Volturnia if it has colonized beyond them in the region (continent)
- Native nations in the New World can no longer take the decision called New Life in the New World
- Made gold rush events not fire until 1870 for uncives
- When Smolensk annexes Russia, they now have a decision to reduce POP MIL and CON by 4 to reduce rebels
- Gave Mali one military reform (two seemed a bit OP, but it's there still if you want to readd it yourself!)
- Fixed 99% of remaining mismatches between various map files. The Paracel Islands will continue not to exist as land for gameplay purposes (though if you look closely you can see their shadow)
- Also made a lot rivers fit province borders better - lots more to do still
- Split Pau off from the Basque province of Miarritze, added two flavour events about Our Lady of Lourdes to the owner
- Made requirements for taking the Intervene in Persia decision more clear to the player
- Increased Make Puppet CB to 10 max badboy (previously 7)
- Increased starting experience in national values, so now they are actually kind of useful. This change is also reflected in the demonstration modifiers which you can see i nthe decision
- Made the National Assimilation event impossible to fire until 1870
- Improved the event which signals the end of BRB cores, made it specifically for NET (more, kind of), and added one for BRB
- Added decisions for an independent Greece to claim the rest of the state of Thessalonikos and (if jingoist) to claim Crete
- Greek party tweaks
- Study Room Meetings should disappear from all BOH-owned provinces after they defeat the revolution
- Added a decision for a resurgent Bohemia to lease Zadar again
- Added a decision (which the AI will never take) to return a leased Zadar to Croatia or Yugoslavia (the latter should only be seen if some other country creates YUG, not the Zadar owner, please report to Savs if this is not the case)
- Tweaked the Yugoslavia creation decision to take into account a leased Zadar - if you still have the province, you will give it to Zadar automatically.
- Arbenon (Albania) must now no longer be a vassal or must be vassal of the country in question in order to be absorbed into Yugoslavia (whether that country is a vassal or no)
- Bulgaria gets cores on the Black Sea coastal provinces it should have cores on when the Bulgarian Insurrection event fires
- Added an event to make Ardeal release Banat and Syrmia and lose cores on them if it does not own land connected to that area (as often happens)
- Added a decision to regain the abovementioned lands as cores of Ardeal
- Tweaked a few LRs
- Tweaked a few RGOs in Aengland
- Pumped up some starting prestige for important European countries
- Many localizations tweaks and fixes
- Lots of other small stuff not worth mentioning
- Added a blank province map (current to 0.36.27) for whatever you might want to use it for

Bugfixes
- Navarra has a liberal party for the entire game
- The Mare Occidentis Nostrum decision now works properly
- Intervening in Persia now no longer gives more infamy than expected
- BRB armies now all start WITHIN the duchy
- The New Zadar Lease-related decision can no longer be repeated if the owner of Zadar rejects it
- Bugfixes to the Califiana annexation chain and associated events
- Yugoslavia can no longer invite itself to join itself
- The Encourage Textile Industry NF no longer crashes the game when hovered over
- Fixed some broken event numbers in HtA_Africa

----------------------------------------------------------------------------------------------------------
See the OldChangelogs file for previous version changelogs. You can also see them on the subreddit's wiki.

To do:
- See the "To Do" text file

**Event numbers** - both currently used and planned
50000&50002 - AQT
50003-50023 - FRA
50024-50049 - ITA and DAU (This is about the time I started actually being smart and allocating numbers beforehand. All are used up, must allocate more IDs. Added 50099 here)
50050-50098 - Germany and surroundings
50100-50149 - British Isles
50150-50199 - Africa
50200-50249 - AQT and PRE
50250-50299 - Low Countries
50300-50349 - Iberia
50350-50399 - Russia/Smolensk
50400-50499 - Poland, Silesia, Bohemia (Most of these numbers are taken in Bohemia)
50500-50599 - Nordic Countries (NOR, SWE, DEN, ICL, FIN)
50600-50699 - Roman Empire and related
50700-50799 - Armenia events
50800-50849 - Miscellaneous events (some in HtA_famines, some in HtA_Flavor)
51000-51199 - North Amerigan events (separate file for each country?)
51200-51399 - South Amerigan events
51400-51449 - More FRA
51450-51499 - Baltic countries
51500-51549 - Indonesia
51550-51599 - MORE Aquitania
51600-51649 - Misc European, spread across different files
51650-51699 - Mediterranean
51700-51750 - Caribbean
51751-51850 - The Near East (first half), Persia (second half)
51851-51899 - More Italy
51900-51999 - More European flex files
52000-52100 - South Africa
52200-52499 - Rest of Africa.
52500-52799 - Southeast Asia (not including Indonesia, obviously)
53000-53199 - China, Korea, etc
53200-53299 - Balkans

59800-59949 - Misc. events
59950-59999 - Debugging events
97091-97098 - North American settlement events
97097 - Event/decision to enable railroading
97098 - Claiming Amerigan interior provinces
97099-97107 - Outremer-related events