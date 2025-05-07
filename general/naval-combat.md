---
layout: page
title: Naval Combat rules
indexed: true
categories: [General]
---

The rules for naval combat are largely based on [The Complete guide to Nautical Campaigns](https://www.greatgamemaster.com/dm/product/the-complete-guide-to-nautical-campaigns-pdf/) by [How to be a Great Game Master](https://www.greatgamemaster.com/). This page summarizes the system from a player's perspective, and some details may be abbreviated or simplified. In case of conflict the rules as written in the Complete Guide take precedence.

There are two types of naval combat described in the rules:

- Chase
- Boarding

Boarding is essentially the same as regular combat, with a few additions, so most of this page will focus on Chase Combat.

## Chase combat

Chase combat is what happens when a hostile ship comes within range (within 800ft for regular ships, 200ft when underwater) of its quarry. Chase combat can end in a number of ways:
- The distance between ships is reduced to 0ft (either by disabling the quarry or outsailing it), and boarding combat commences
- The distance between ships is increased to more than 800ft, and the chase ends
- The attacking ship is sunk
- The chased ship is sunk 

### Movement

Rather than using a grid with exact positions, naval combat uses a distance tracker with relative positions.

<table class="w-100">
    <tbody>
        <tr>
            <td><img class="img-fluid" alt="Surface tracker" src="../surface-tracker.png" /></td>
            <td><img class="img-fluid" alt="Underwater tracker" src="../underwater-tracker.png" /></td>
        </tr>
        <tr>
            <td class="text-center">Surface tracker</td>
            <td class="text-center">Underwater tracker</td>
        </tr>
    </tbody>
</table>

At the end of each turn, the movement speeds of both ships are compared:

{:class="table"}
| Speed difference                                | Movement effect                              |
|-------------------------------------------------|----------------------------------------------|
| Target ship > Chasing ship (factor 2 or more)   | Target ship moves two positions to the right |
| Target ship > Chasing ship (less than factor 2) | Target ship moves one position to the right  |
| Equal speeds                                    | Target ship remains in position              |
| Chasing ship > Target ship (less than factor 2) | Target ship moves one position to the left   |
| Chasing ship > Target ship(factor 2 or more)    | Target ship moves two positions to the left  |

### Officers

A ship is run by its officers. These officers can be both PCs and NPCs. A ship can have the following officers:

{:class="table"}
| Officer       | Task                                                                                             | Relevant stats         |
|---------------|--------------------------------------------------------------------------------------------------|------------------------|
| Captain       | Leads the ship, manages its operation                                                            | Wisdom, Charisma       |
| First Mate    | Link between crew and captain, ensures smooth operation of ship and responsible for morale       | Wisdom, Charisma       |
| Bosun         | Ensures the ship's structural integrity, layout. Basically a chief engineer                      | Strength               |
| Ship's Mage   | Magical liaison between the ship and the ocean, using magic to get the ship where it needs to be | Intelligence, Charisma | 
| Quartermaster | Ensures the ship is well-supplied; responsible for navigation                                    | Wisdom, Charisma       |
| Surgeon       | Keeps the crew healthy, interrogates prisoners                                                   | Intelligence, Wisdom   | 

### Turns

Ships cannot take actions on their own, so their actions are determined by their crews. As crews can get quite large, the initiative order only tracks any officers a ship may have, and all players.

On each turn, a player can take actions as they normally would, and if they have the role of an officer aboard the ship in question, issue a command (this is generally a free actions, unless stated otherwise). Some of these commands can be issued out of combat as well.

### Orders

{:class="table"}
| Order                     | Type     | Issued by             | Effect                                                                                                                                                                                                               |
|---------------------------|----------|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Fire!                     | Attack   | Any officer           | All weapons that belong to a single weapon component fire on the target vessel, targeting their hull                                                                                                                 |
| Brace!                    | Buff     | Any officer           | DC12 Crew Quality check. Reduce all non-magical damage to crew by 2D10 for one round                                                                                                                                 |
| Training                  | Buff     | Any officer           | **Takes 3 days to complete.** Crew trained in hand-to hand combat an hour daily, increases Crew Quality by 1                                                                                                         |
| Learning                  | Buff     | Any officer           | **Takes 3 days to complete.** Crew trained in seamanship an hour daily, increases Crew Quality by 1                                                                                                                  |
| Get us moving!            | Movement | Any officer           | **When ship has speed 0.** Ship speed is 10ft this turn, and regular speed next turn                                                                                                                                 |
| Put that out!             | Repair   | Any officer           | DC5 Crew Quality check to put out a fire. May take multiple orders to complete if larger fire (up to 4 orders)                                                                                                       |
| Focus fire                | Attack   | Captain or First Mate | Single weapon from a weapon component attacks with advantage, targeting their hull                                                                                                                                   |
| Reload!                   | Attack   | Captain or First Mate | Requires an extra officer (any) near weapon. Allows a weapon component to make a second attack                                                                                                                       |
| Split your targets        | Attack   | Captain or First Mate | Attack multiple targets with single weapon component (if component has that many weapons). Targets hull                                                                                                              |
| Sacrifice to the gods     | Attack   | Captain or First Mate | Sacrifice two crew members (-1 Crew Quality) for kamikaze attack using rowboat against enemy hull within 200ft (CQ vs AC). 8D10 Fire Damage + large fire started. Crew members can be retrieved after combat on miss |
| Kill them all             | Attack   | Captain or First Mate | Attack vs enemy crew within 100ft. Attack vs Helm AC. Kills 2D6 crew on hit                                                                                                                                          |
| Launch: attack target     | Attack   | Captain or First Mate | Launches naval or aerial units from the ship to attack target ship                                                                                                                                                   |
| Rip it open               | Attack   | Captain or First Mate | **Requires harpoon embedded in target.** Strength vs. DC5 + Target ship size. 2D10 damage to target per harpoon on hit. 2D10 damage to harpoon component on miss                                                     |
| Drag it down              | Attack   | Captain or First Mate |                                                                                                                                                                                                                      |
| Ram them                  | Attack   | Captain or First Mate |                                                                                                                                                                                                                      |
| Evasive                   | Buff     | Captain or First Mate |                                                                                                                                                                                                                      |
| Hide                      | Buff     | Captain or First Mate |                                                                                                                                                                                                                      |
| Hoist the colors          | Buff     | Captain or First Mate |                                                                                                                                                                                                                      |
| Club hauling              | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Dead stop                 | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Gnome it                  | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Surface                   | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Dive                      | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Faster!                   | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Ramming speed!            | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Launch: scout             | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Reduce speed              | Movement | Captain or First Mate |                                                                                                                                                                                                                      |
| Debris                    | Attack   | Bosun                 |                                                                                                                                                                                                                      |
| A little surprise         | Attack   | Bosun                 |                                                                                                                                                                                                                      |
| Improvised shot           | Attack   | Bosun                 |                                                                                                                                                                                                                      |
| A new paint job           | Buff     | Bosun                 |                                                                                                                                                                                                                      |
| Swabbing the deck         | Buff     | Bosun                 |                                                                                                                                                                                                                      |
| Wet that!                 | Buff     | Bosun                 |                                                                                                                                                                                                                      |
| Jury rig                  | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| All hands on deck         | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Bucket chain!             | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Cannibalize               | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Fix her up                | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Miracle worker            | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Drydock                   | Repair   | Bosun                 |                                                                                                                                                                                                                      |
| Target component          | Attack   | Quartermaster         |                                                                                                                                                                                                                      |
| Target squadron           | Attack   | Quartermaster         |                                                                                                                                                                                                                      |
| Weighted shot             | Attack   | Quartermaster         |                                                                                                                                                                                                                      |
| Scrounge up supplies      | Buff     | Quartermaster         |                                                                                                                                                                                                                      |
| Hunt                      | Buff     | Quartermaster         |                                                                                                                                                                                                                      |
| Rally for pay             | Buff     | Quartermaster         |                                                                                                                                                                                                                      |
| Rig for speed             | Movement | Quartermaster         |                                                                                                                                                                                                                      |
| Lighten the load          | Movement | Quartermaster         |                                                                                                                                                                                                                      |
| Collect flotsam or jetsam | Movement | Quartermaster         |                                                                                                                                                                                                                      |
| Maximum casualties        | Attack   | Surgeon               |                                                                                                                                                                                                                      |
| Old sea bones             | Attack   | Surgeon               |                                                                                                                                                                                                                      |
| Butcher's work            | Buff     | Surgeon               |                                                                                                                                                                                                                      |
| Invigorating tonic        | Buff     | Surgeon               |                                                                                                                                                                                                                      |
| Heal up                   | Buff     | Surgeon               |                                                                                                                                                                                                                      |
| Medicinal herbs           | Buff     | Surgeon               |                                                                                                                                                                                                                      |
| Rest in a bottle          | Buff     | Surgeon               |                                                                                                                                                                                                                      |
| Insanity                  | Movement | Surgeon               |                                                                                                                                                                                                                      |
| Distraction               | Attack   | Ship's Mage           |                                                                                                                                                                                                                      |
| Sparkling Lights          | Buff     | Ship's Mage           |                                                                                                                                                                                                                      |
| Ward                      | Buff     | Ship's Mage           |                                                                                                                                                                                                                      |
| Disrupting hex            | Buff     | Ship's Mage           |                                                                                                                                                                                                                      |
| Protection of Magics      | Buff     | Ship's Mage           |                                                                                                                                                                                                                      |
| Wind!                     | Movement | Ship's Mage           |                                                                                                                                                                                                                      |
| Invisible workforce       | Movement | Ship's Mage           |                                                                                                                                                                                                                      |
| Read the wind             | Movement | Ship's Mage           |                                                                                                                                                                                                                      |
| Control currents!         | Movement | Ship's Mage           |                                                                                                                                                                                                                      |
| Ship mending              | Repair   | Ship's Mage           |                                                                                                                                                                                                                      |

## Boarding combat

Once two ships have reached 0 distance on the tracker, boarding combat can begin. The ships are now very close, and the following orders become available for the most senior officer remaining:

{:class="table"}
| Order            | Effect                                                                                                                                                                       |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Board            | Attackers can make DC12 Crew Quality check to leap to other ship. PCs can use DC12 Acrobatics for the same purpose. No combat on failure                                     |
| Grapple          | Ship Strength vs target ship's Hull AC check. Success reduces both ship speeds to 0 and neither can pull away. Crew can move freely from ship to ship                        |
| Pull away        | Break grapple on successful opposed ship Strength check                                                                                                                      |
| Repel Boarders   | DC14 Persuasion or Performance check to gain +2 Crew Quality for combat duration. Cannot be used if _Have at 'em_ has been issued                                            |
| Have at 'em      | DC14 Intimidation or Persuasion check to gain +2 Crew Quality for combat duration. Cannot be used if _Repel Boarders_ has been issued                                        |
| Strafe the decks | Attack target ship with weapons at close range. Weapon attack against target ship hull. On hit, 1D10 sailors gravely wounded. Friendly fire possible, casualties split 50/50 |
| Protect the...   | Assigns crew members to protect officers, adding 10 temp HP per crew member (20 if they are Ship's Guard)                                                                    |

During boarding combat, the PCs focus on enemy officers and vice versa, while the regular crews fight one another. This is done as follows:

- After everyone has taken their turn, both ships make an opposed Crew Quality check. 
- The difference is the number of crew gravely wounded or killed in the losing crew. 
- Ranking officers do not count toward the total
- When all enemy officers are defeated, the enemy ship surrenders
- When the crew of one ship is more than triple the number of crew on the other, the smaller crew surrenders if given a chance
- On an Undead ship, the crew collapses if the ship's Necromancer is slain

In addition to these rules, the following modifiers may apply in crew to crew combat:

- For every 10 additional crew more than the other crew add +1 to the bigger crew’s CQ for the combat.
- For crew that includes ship’s guard increase the CQ by 1 for every 10 ship’s guard.
- For crew fighting in unfamiliar territory, such as underwater, out of water, reduce their CQ by 2.
- Mounted units can join the fight if they’ve been launched. Increase the CQ for that side by +1 per 5 mounted units.
- When the captain is killed or taken prisoner, decrease the CQ for the crew belonging to that captain by 3.
- When a ranking officer dies -1 to the CQ of that crew.