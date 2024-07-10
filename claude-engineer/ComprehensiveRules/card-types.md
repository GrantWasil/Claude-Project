# Star Wars Unlimited: Card Types

## Table of Contents
- [Star Wars Unlimited: Card Types](#star-wars-unlimited-card-types)
  - [Table of Contents](#table-of-contents)
  - [1. Base](#1-base)
  - [2. Event](#2-event)
  - [3. Leader](#3-leader)
  - [4. Unit](#4-unit)
  - [5. Upgrade](#5-upgrade)
  - [6. Token](#6-token)
  - [7. Card Anatomy](#7-card-anatomy)
  - [8. Card Interactions](#8-card-interactions)

## 1. Base
1.1. Represents a location in Star Wars.
1.2. Each deck must have exactly 1 base.
1.3. Starts the game in the owner's [base zone](game-zones.md#base-zone).
1.4. Can be dealt damage through abilities and enemy attacks.
1.5. When a base has no remaining HP, its owner loses the game (see [Victory Conditions](setup-and-victory.md#2-victory-conditions)).

Examples and Strategic Uses:
- "Death Star": A base with high HP (40) and the ability "Action: Deal 1 damage to each enemy unit." Strategic use: Provides longevity and board control.
- "Rebel Base on Hoth": A base with moderate HP (30) and the ability "When an enemy unit attacks your base, exhaust it." Strategic use: Discourages direct attacks on your base.
- "Coruscant Senate": A base with lower HP (25) but the ability "At the start of your turn, gain 1 additional Force." Strategic use: Accelerates your Force generation for faster card deployment.

[Insert visual representation of a Base card, highlighting its unique features such as high HP and lack of cost]

## 2. Event
2.1. Has a name, cost, trait(s), and ability.
2.2. To play: pay its cost, place it in the [discard pile](game-zones.md#discard-pile), then resolve its ability.
2.3. Does not enter play; moves directly from hand to discard pile.
2.4. Can affect itself if it affects cards in the discard pile.

Examples and Strategic Uses:
- "Force Lightning": Cost 3, "Deal 2 damage to up to 3 different enemy units." Strategic use: Efficient multi-target removal.
- "Rebel Assault": Cost 4, "Deal 3 damage to an enemy unit. If that unit is defeated, deal 2 damage to the enemy base." Strategic use: Combines unit removal with base damage.
- "Jedi Mind Trick": Cost 2, "Return target enemy unit with cost 3 or less to its owner's hand." Strategic use: Tempo play to disrupt enemy board presence.

[Insert visual representation of an Event card, highlighting its cost and one-time use nature]

## 3. Leader
3.1. Double-sided card with a horizontal "Leader side" and a vertical "Leader Unit side".
3.2. Each deck must have exactly 1 leader.
3.3. Starts the game in the base zone on its Leader side (see [Game Setup](setup-and-victory.md#1-game-setup)).
3.4. Deployed using the Epic Action ability on its Leader side.
3.5. When deployed, flips to Leader Unit side and moves to the ground arena, [ready](game-concepts.md#5-ready-and-exhausted).
3.6. When defeated as a Leader Unit, flips back to Leader side and moves to the base zone, exhausted.

Examples and Strategic Uses:
- "Luke Skywalker":
  - Leader side: "Epic Action [5 Force]: Deploy Luke Skywalker."
  - Leader Unit side: 5/5, "When Luke Skywalker attacks, you may ready another friendly unit." 
  Strategic use: Provides additional actions through his ability.
- "Darth Vader":
  - Leader side: "Epic Action [6 Force]: Deploy Darth Vader. When you do, defeat an enemy unit with cost 4 or less."
  - Leader Unit side: 6/6, "Overwhelm 2"
  Strategic use: Immediate board impact upon deployment and sustained pressure.

[Insert visual representation of a Leader card, showing both sides and the flip mechanic]

## 4. Unit
4.1. Depicts a Star Wars character or vehicle.
4.2. Has a name, cost, power, HP, trait(s), and arena type.
4.3. To play: pay its cost and place in the designated arena (ground or space).
4.4. Enters play exhausted and remains in play until defeated.
4.5. Defeated when it has no remaining HP or when an ability defeats it directly (see [Defeating Cards](game-concepts.md#6-defeating-cards)).

Examples and Strategic Uses:
- "X-wing Starfighter": Cost 3, 3/3, Space, Pilot. "When this unit attacks, it gets +1 power for this attack for each other friendly Pilot unit." Strategic use: Synergizes with other Pilot units for increased damage output.
- "Stormtrooper Squad": Cost 2, 2/2, Ground. "When this unit enters play, you may search your deck for a card named 'Stormtrooper Squad' and put it into your hand." Strategic use: Provides card advantage and consistent board presence.
- "Millennium Falcon": Cost 5, 4/5, Space, Unique. "Action: Move this unit to an adjacent arena. When you do, you may move another friendly unit to an adjacent arena." Strategic use: Provides flexibility in unit positioning and surprise attacks.

[Insert visual representation of a Unit card, highlighting its cost, power/HP, and arena type]

## 5. Upgrade
5.1. Attaches to a unit in play.
5.2. Has a name, cost, trait(s), power modifier, and HP modifier.
5.3. To play: pay its cost and attach to an eligible unit in play.
5.4. May specify it must "attach to" a specific type of unit (play restriction).
5.5. No limit to the number of upgrades that can be attached to a unit.
5.6. Can be played on friendly or enemy units.
5.7. If a player plays an upgrade onto an enemy unit, that player still [controls](game-concepts.md#4-card-ownership-and-control) the upgrade. If that upgrade gives abilities to the attached unit, the unit's controller resolves those abilities.
5.8. Defeated when the attached unit leaves play or when an ability defeats it directly.
5.9. Some upgrades are also tokens and have the "token upgrade" card type.
5.10. Token upgrades follow the same rules for upgrades, except that they are put into play differently and are set aside when defeated.

Examples and Strategic Uses:
- "Lightsaber": Cost 2, +2/+1. "Attached unit gains Overwhelm 1." Strategic use: Improves unit's combat effectiveness and provides additional base damage.
- "Stealth Field Generator": Cost 3, +0/+2. "Attached unit cannot be targeted by enemy events or abilities." Strategic use: Protects key units from removal effects.
- "Rebel Armor": Cost 1, +0/+2. "When attached unit would be defeated, instead remove all damage from it and defeat this upgrade." Strategic use: Provides additional durability to important units.

[Insert visual representation of an Upgrade card, showing how it attaches to a unit and its modifiers]

## 6. Token
6.1. Set aside at the start of the game.
6.2. Put into play by specific abilities.
6.3. Cannot be shuffled into decks, discarded, or "played".
6.4. If it would move to an out-of-play zone, set it aside instead.
6.5. No limit on tokens available to a player.

Examples and Strategic Uses:
- "Shield Token": Token Upgrade, +0/+1. "Prevent the next damage that would be dealt to attached unit this turn." Strategic use: Provides temporary protection to valuable units.
- "Droid Token": Unit Token, 1/1, Ground. "When this unit is defeated, draw a card." Strategic use: Provides chump blockers that replace themselves when defeated.
- "Bounty Token": Token Upgrade. "When attached unit is defeated, its controller loses 2 Force." Strategic use: Discourages your opponent from sacrificing the marked unit.

[Insert visual representation of a Token card, emphasizing its unique features like lack of cost]

## 7. Card Anatomy
7.1. Name: Located at the top of the card.
7.2. Cost: Number in the top-left corner (for non-base cards).
7.3. Aspects: Colored icons on the left or right side of the card.
7.4. Type: Indicated in the top-left corner (e.g., "Unit", "Upgrade").
7.5. Arena Type: For units, indicated in the top-right corner ("Ground" or "Space").
7.6. Traits: Listed below the card art or name.
7.7. Text Box: Contains the card's abilities.
7.8. Power/HP: For units, shown in the bottom-left and bottom-right corners, respectively.
7.9. Power/HP Modifiers: For upgrades, shown on the left and right sides, respectively.
7.10. Unique Symbol: A diamond (⟡) before the name for unique cards.

[Insert detailed diagram of a card, labeling all the anatomical features mentioned above]

## 8. Card Interactions

Understanding how different card types interact is crucial for mastering Star Wars Unlimited. Here are some key interactions:

8.1. Units and Upgrades:
- Multiple upgrades can be attached to a single unit, potentially creating powerful combinations.
- Upgrades that give abilities to units can create synergies with the unit's existing abilities.
- Example: A "Blaster Rifle" upgrade (+1/+0, "Attached unit gains 'Action: Deal 1 damage to target unit.'") on a unit with the ability "When this unit deals damage, draw a card" creates a powerful action economy.

8.2. Leaders and Other Cards:
- Leader abilities often synergize with specific card types or traits.
- Example: A leader with "Friendly Droid units get +1/+1" encourages building a deck with many Droid units.

8.3. Events and Units:
- Events can often target units for various effects, such as dealing damage, moving units, or granting temporary bonuses.
- Some units have abilities that trigger when targeted by events, creating interesting counterplay opportunities.
- Example: An event "Deal 3 damage to target unit" against a unit with "When this unit would be dealt damage, you may discard a card to prevent 2 of that damage."

8.4. Bases and Other Card Types:
- Some units, upgrades, or events may have abilities that specifically interact with bases.
- These interactions can be crucial for both offensive and defensive strategies.
- Example: An upgrade "When attached unit damages the enemy base, gain 1 Force" can create a powerful economic engine.

8.5. Tokens and Regular Cards:
- Tokens often interact with regular cards through abilities that create or manipulate tokens.
- Understanding these interactions can provide additional strategic depth.
- Example: A unit with "When this unit enters play, create two Shield tokens and attach them to this unit" provides built-in protection.

Understanding these interactions allows players to create powerful combos, anticipate opponent's plays, and make more informed decisions during deck building and gameplay.

---

For more information on game zones, see the [Game Zones](game-zones.md) section.
For details on game concepts, refer to the [Game Concepts](game-concepts.md) section.