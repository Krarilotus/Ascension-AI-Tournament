# Stronghold Crusader AI Tournament 2025 – Official Rules & Setup

This tournament challenges modders to create compelling AI characters that will compete against each other in various scenarios. Participants submit **a working AI** based on the given conditions:
- The **Ascension AI Balance** is a defining framework for the entire tournament.
- The harsh starting conditions typical of **Ascension** (e.g., 0 starting gold) are slightly adjusted for AI standards.

![Description](https://raw.githubusercontent.com/Krarilotus/Ascension-AI-Tournament/refs/heads/main/bootstrap_finaltrans.png)

---

## I. Setup & Starting Resources

If you've made it this far, you're almost done: To test, create, and submit your AI, you only need the **Ascension-AI-Tournament** plugin. This provides all the necessary settings, and you can test the starting conditions in-game with your AIs. But don't worry, almost all AIs that work well in *Vanilla* also work well in **Ascension**.

For the most important changes, you can read the summary of the **Ascension AI Balance** plugin. If you want to know the exact details, feel free to check out the spreadsheet with all the values:
- **[Ascension AI Balancesheet](https://docs.google.com/spreadsheets/d/1CyEB7tdixSODzZCHn2xPRCGAScqicDi4k6oUCilch4A/edit?gid=0#gid=0)**
- **[Vanilla Balance for Comparison](https://docs.google.com/spreadsheets/d/1PdMwVbIfu8c2ebszkSiqlALeZ0YWL_1nHp9TEU10r48/edit?gid=0#gid=0)**

---

## II. Submissions – Choosing the Right Format!

To participate in the tournament, you must submit a UCP3-compatible AI. To do this, create an account on **[GitHub](https://www.github.com)** and a repository with the same name as your AI, containing a working plugin with your AI in the **resources/ai** folder.
Then, send the link to your AI's GitHub repository via Discord to **Xander10alpha** or by email to **shc.aicontest@gmail.com**.

You can read about how to create such an AI **[here in the Wiki](https://unofficialcrusaderpatch.com/#wiki/Stronghold-Crusader-Wiki%2FAI-Lords%2FAI-Editing-Tutorial)**. However, our personal recommendation is to just ask for help on the **[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)** if you need it, and to use an existing AI from the plugin (under **resources/ai**) as a reference. Happy building! ;)

It is our wish that the AIs not only **function very well** and can handle the starting conditions. It would be especially desirable if the **AIs also embody their own character**, for example, through a backstory (description), a custom AI portrait, and animated videos & audio files.

Additionally, the following restrictions apply:
- Maximum of 12 starting troops (from troop types already present in the AIC)
- Maximum Lord strength of 1.5
- No unnecessary exploits!

A sorted preference list of the maps available in the plugin is also mandatory for submission. Each map pick will be honored once during the tournament and then removed from the list. For the final map of best-of-X matches a map will be chosen at random out of those, least played by participating AIs thus far.  

**Notes:**
- For 2 vs 2 maps, a preferred starting position is also required.
- At least 5 maps for 1 vs 1, two maps for 2 vs 2, and one map for Free-for-All must be selected.
- The final map list can be found in the Appendix (see VI).

---

## III. Tournament Procedure

Games always end after 50 years at the latest, resulting in a draw! This limit is 60 years for maps with Dummy AIs and 75 Years for 2 vs 2 Games.

### Schedule
__Introductory Phase:__ There will be an introductory round where all AIs are showcased in a brief presentation before the actual tournament begins.

__Phase 1:__ The tournament will initially follow the classic **[Swiss System](https://en.wikipedia.org/wiki/Swiss-system_tournament)**. There will be at least **two Swiss System rounds** to establish a basic ranking of the AIs. The exact number of rounds will increase with the number of participating AIs.

__Phase 2:__ This is followed by one round of **[Free-for-All (4 players FFA)](https://en.wikipedia.org/wiki/Deathmatch_(gaming))** and then **two rounds of 2 vs. 2**. For each of these rounds, teams will be matched based on the current points from the standings: the first-place AI with the last, the second with the second-to-last, and so on. The lower-ranked player on a team chooses the map, while the higher-ranked player chooses the position. In Free-for-All games the target choice of the AIs will be fixed to **Gold**.

__Final Phase:__ To conclude, there will be a final round of **1 vs. 1** following the **[Swiss System](https://en.wikipedia.org/wiki/Swiss-system_tournament)** distribution.

### Point Distribution
**Victory Points:** For **1 vs. 1** and **2 vs. 2** matches, the following **Victory Points (VP)** will be awarded per AI based on the outcome:
- **Win:** 2 VP
- **Draw:** 1 VP
- **Loss:** 0 VP

In Free-for-All (FFA), the following VPs will be awarded based on placement:
- **1st Place:** 3 VP
- **2nd Place:** 2 VP
- **3rd Place:** 1 VP
- **4th Place:** 0 VP
- **Draw** (for all remaining AIs): 2 VP


**Bonus Points:**
Additionally, for each phase, there are the following bonus challenges that award **Bonus Points (BP)**. These are equivalent to Victory Points but do not influence matchmaking:

__Phase 1:__ For each of these challenges, the **top N AIs** of the phase in each category will receive one point, where **N is the number of rounds** in this phase.
- **Master Chef:** produced the most food in a single game
- **First Blood:** killed an opponent in the fewest months after the start of a game
- **Spammer:** achieved the highest ratio of (Troops Recruited / Gold Earned) in a single game
- **Raidmaster:** destroyed the most buildings in a single game
- **MVP:** killed the most troops in a single game
- **Eco-Freak:** produced the fewest wood planks in a single game
- **Cunning:** achieved the largest difference in a game from:
  `(Enemy Troops Died) - (Own Troops Killed)` where maps with dummy rats are excluded!
- **Sacrificial Lamb:** lost the most buildings accumulated over the entire phase
- **Showmaster:** had a game duration closest to the average of all games in this phase

__Phase 2:__ For each of these challenges, the **top N AIs or teams** in each category will receive one point, where **N is the number of rounds** this category affects. Furthermore, individual game goals from **Phase 1** can be awarded **once more** for breaking a record!
- **Martyr:** (2 vs. 2) in a winning game, was the first AI to be defeated
- **Hermit:** (2 vs. 2) smallest combined population among all winning teams and all losing teams (Note: Only one BP per AI per team will be awarded in this phase).
- **Teamwork:** (2 vs. 2) had the ratio (Troops Produced AI 1 / Troops Produced AI 2) closest to 1 in a single game
- **Building Maintenance:** (2 vs. 2) highest positive result in a game for the difference of:
  `Total Buildings Destroyed - Total Buildings Lost`
- **Punching Bag:** (FFA) survived the longest of all games, but died first in their own game
- **Poacher:** (FFA) built the fewest troops and still won
- **King of Dust:** (FFA) the highest difference between
  `Crowns - Kills`
  (Awarded multiple times in case of a tie!)
- **Minimalist:** best (minimum) balance of (Hard Resources Produced (Stone, Iron, Pitch) / Game Time) over the entire phase
- **Suicide:** earliest death of the lord outside the keep
- **Headhunter:** accumulated the most kills in total during the phase. In case of a tie, the accumulated in-game time for all kills will be the tiebreaker.

__Final Phase:__
This is the grand finale! Each of these criteria will be evaluated after all AI games are completed and awarded to the best 3 AIs of each category.
- **Ascended:** earned the most Ascension Points over the course of the whole tournament
- **Kingslayer:** won a single game with the largest point deficit
(Awarded multiple times in case of a tie!)
- **Superstar:** chosen by the audience from selected highlights (YouTube Poll). This honors the most epic highlight of the tournament.
- **Ecstasy:** one BP for each of the three AIs whose introduction video received the most likes
- **Record Breaker V2:** existing records for the 7 individual criteria from **Phase 1** can be broken again for a BP
- **Croesus:** most total gold accumulated across all phases
- **Game of Thrones:** most crowns accumulated across all phases
- **The Joker:** biggest jump in the overall ranking between the end of Phase 1 and the Final Phase; awarded after everything else
- **Pot of Greed:** best (maximum) ratio of (Bonus Points / Victory Points)

The AI with the most VP + BP at the end of the tournament wins!

## IV. Special Rules: Ascension Points
**Ascension Points** (APs) can be used during the tournament to make changes to the submitted AIs between rounds. The options can be found in the list below. Changes will be discussed on the **[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)** in the AI's forum channel and **must** be accepted by the AI creator to take effect.

Each round, (10 x number of participating AIs) APs will be distributed. The distribution works as follows:
- Exactly **7 days** after a video goes live, the watch time `WT` **for that video** will be recorded.
- The total watch time **of all videos** in the round is accumulated into `GWT`.
- The **APs** distributed to the **AIs featured** in the video then correspond to the ratio `WT / GWT`.
- Example: The watch time for a video is `WT = 100h` and the total watch time of all videos in the round is `GWT = 1000h`. With 20 participating AIs, the two AIs from the video would each receive (100 / 1000) x (10 x 20) = 20 AP for that round.

The exact Options for Changes are:  
- **Hotfixes (Free):** Hotfixes are free, e.g., for **pathfinding issues**, poorly set **AIC parameters**, or to **add houses**.

### AIV Change Options
- **[VBC] Village Basic Change (5 AP):** Add/Remove/Reposition one AIV Non-Castle Building or Add/Remove/Reposition up to two Fearfactor Buildings or Add/Remove/Reposition one AIV Troop Rally Point.
- **[CBC] Castle Basic Change (10 AP):** Add/Remove/Reposition one AIV Castle Building or Add/Remove/Reposition up to Twenty Wall/Moat/Pitch/Killing Pit tiles or Add/Remove/Reposition up to five Fearfactor Buildings or Add/Remove/Reposition up to three AIV Troop Rally Points.
- **[UBT] Unlock Buildingtype (15 AP):** Introduce (unlock) a new building type (Note: Woodcutters, Hunters, Oxtethers and Ghoststeps (Index 2) are always unlocked!).
- **[ABO] Adjust Build Order (40 AP):** Adjust the build order, no repositioning of buildings!

### AIC Change Options
- **[BBC] Behaviour Basic Change (5 AP):** Adjust one Non-Unit-Slot related AIC Value.
- **[UCC] Unit Count Change (5 AP):** Change the number of units in an existing Unit-Slot by up to 5 or the number of Siege Engines by one or add/remove/replace one Siege Engine and necessary engineers.
- **[AUS] Add Unit Slot (10 AP):** Add a new Unit-Slot with an existing unit type with up to 5 units.
- **[UUT] Unlock Unittype (20 AP):** Introduce a new unit type that has not been used before by this AI.

### AP Package Deals
- **[ORN] Ox & Running Newbie (10 AP):** Freely Add/Remove/Adjust any of the newly introduced Values related to Oxtether logic and Running Units.
- **[WBS] Workers Big Sellout (10 AP):** Freely Adjust all Sell Resources and Workshop Preferences.
- **[FFT] Fearful Taxcollector (10 AP):** Freely Adjust all Taxation and Popularity Values as well as Double Rations Threshold.
- **[CRL] Crops Relocation (10 AP):** Freely Adjust all Farmslot Values and the Population Per Farm Value.
- **[SPH] Stockpile Hoarding (15 AP):** Freely Adjust all Minimum and Maximum Resource Values, Resource Variance and Trade Amount Values.
- **[SEX] Strategic Expertise (15 AP):** Freely Adjust all Wall and Outer Patrol Group Counts and Rally Times and Movement, as well as Raid Retarget Delay, Support Threshold, Rally Percentage, Assault Delay, Recommand Delay and Cowthrowing Interval.
- **[FBG] Fresh Battlegrounds (20 AP):** Freely Adjust remaining Map Picks (Note: Map picks need to stay unique and already played map picks can't be redone!).
- **[DEA] Draft Eco Adjustment (20 AP):** Freely Adjust all Population per Buildingtype, Maximum Buildingtype, Recource Rebuild Delay Values.
- **[ACP] Army Conscriptions (25 AP):** Freely Adjust all Recuritment Probabilities, Recruitment Gold Threshold, Siege Engine Gold Threshold, Recruit Intervals and Recruit Buildings AIV Build Steps.
- **[SQS] Sneaky Quick Swap (10 + x AP):** Swap two Single-Unit-Slots, by unit type and unit amount, where A + B is the amounts of units of both slots combined and x = abs(A + B - 10) / 2.
- **[ILS] Increase Lord Strength (50 AP):** Increase Lord strength to 2.
- **[AST] Adjust Starting Troops (75 AP):** Adjust Starting Troops in bounds of unlocked troop types, up to a maximum of 15.
- **[GPT] Great Philanthropist (x AP):** Give x amount of Ascension Points to another AI.
- **[BBB] Big Beautiful Bill (up to 25% off):** Buy 4 Ascension Change Options and get the cheapest one for free. (Note: this can be split among multiple purchases for multiple AIs).

For a detailed overview of all options, please refer to the official **[Ascension Change Options Spreadsheet](https://docs.google.com/spreadsheets/d/1l8Ec1E-8jLa6KuQa6udAQWffidRXIl2_H3PBQ8jS_Ew/edit?usp=sharing)**.

All adjustments must be finalized at least one day before the first playday of the round begins.

__Examples:__

**Example 1: Swapping Sortie Troops**
To replace the melee sortie units (let's assume it was 10 spearmen) with 10 assassins for an AI that doesn't have a mercenary post, the following options are required:
- **[UUT] Unlock Unittype (20 AP):** Introduce assassins to the AI's repertoire.
- **[UBT] Unlock Buildingtype (15 AP):** Unlock the Mercenary Post to recruit assassins.
- **[CBC] Castle Basic Change (10 AP):** Add one Mercenary Post to the AIV castle plan.
- **[UCC] Unit Count Change x2 (10 AP):** Reduce the original spearmen slot by 10 to empty it.
- **[AUS] Add Unit Slot (10 AP):** Add a new unit slot for assassins, which starts with up to 5 units.
- **[UCC] Unit Count Change (5 AP):** Increase the new assassin slot by 5 more units to reach the target of 10.

In total, this would cost **70 AP**.

---

**Example 2: Adding a Bread Economy**
To give an AI a proper bread economy it didn't have before, assuming it needs 3 more farms, wheat capability, 2 more woodcutters, mills, and bakeries:
- **[BBC] Behaviour Basic Change x3 (15 AP):** Increase MaxFarms by 3 and change two Farm Slots to wheat.
- **[VBC] Village Basic Change x2 (10 AP):** Add 2 more AIV woodcutter's huts.
- **[UBT] Unlock Buildingtype x2 (30 AP):** Unlock the mill and the bakery.
- **[VBC] Village Basic Change x9 (45 AP):** Place one mill and 8 bakeries in the AIV.

In total, this would cost **100 AP**.

---

**Example 3: Building a Second Bailey**
To add a second outer bailey to an AI's castle, consisting of a gatehouse, a drawbridge, 78 wall sections, and 22 moat sections:
- **[CBC] Castle Basic Change x2 (20 AP):** Add one large gatehouse and one drawbridge.
- **[CBC] Castle Basic Change x4 (40 AP):** Place 78 sections of wall (4 purchases of up to 20 tiles).
- **[CBC] Castle Basic Change x2 (20 AP):** Place 22 sections of moat (2 purchases of up to 20 tiles).

This would amount to a total cost of **80 AP**.

---

**Example 4: Swapping and Boosting Attack Squads**
To swap the `AttUnitVanguard` slot (10 European Archers) with the `SortieUnitRanged` slot (20 Crossbowmen) and then add 20 more units to the new Vanguard slot.
- **[SQS] Sneaky Quick Swap (20 AP):** Swap the two slots. The cost is calculated as `10 + abs(A + B - 10) / 2`, which is `10 + abs(10 + 20 - 10) / 2 = 20 AP`.
    - *Result after swap: `AttUnitVanguard` now contains 20 Crossbowmen, and `SortieUnitRanged` now contains 10 European Archers.*
- **[UCC] Unit Count Change x4 (20 AP):** Increase the `AttUnitVanguard` slot by 20 units (4 purchases of +5 units).
    - *Result after boost: `AttUnitVanguard` now contains 40 Crossbowmen.*

This entire operation would cost a total of **40 AP**. 

## V. Get Involved

[Stronghold Modschmiede](https://discord.com/invite/sKtrj9S626)

Do you also want to help organize, build maps, cast, or simply assist with statistical analysis? Or would you like to sponsor prizes? Apply now as a caster or simply contact **Krarilotus** or **Xander10alpha**. You can find us on **Discord!**

## VI. Appendix - Maplist & Creators
### 1vs1 - 15 total
Ancient Terraces - by Crusader Pilaw  
Beaten Heart - by Krarilotus  
Berg Alawia - by Nevikov  
Conquest Deadly Ascent - by Monsterfish_  
Conquest Dune - by Monsterfish_  
Crimson Rivers - by Nevikov  
Dusty River - by Lord Hühnerfutter  
Fissure - by Krarilotus  
Guilty Modder - by Krarilotus  
Insel Kyklos - by Hacksülze  
Oasis Power - by Krarilotus  
Rumble - by Nevikov  
Silence - by Nevikov  
Trommelhügel - by Nevikov  
Watcher's Eye - by Krarilotus  

### 2vs2 - 9 total
Fading Riches - by Lord Hühnerfutter  
Green Trench - by Nevikov  
Hammer and Anvil - by Tobbi  
Heimatland - Der Archipel - by Crusader Pilaw  
Heimatland - Der Graben - by Crusader Pilaw  
Heimatland - Die Klamm - by Crusader Pilaw  
Mesopotamien - by Hacksülze  
Rocky Crenels - by Crusader Pilaw  
Two Mountains - by Xander10alpha  

### FFA - 3 total
Desert Throne - by Nevikov  
Green Haven Retraced - by Krarilotus  
Mayham - by Crusader Pilaw  
