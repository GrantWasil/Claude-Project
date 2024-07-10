+++
title = "Card Types"
description = "An overview of the different card types in Star Wars Unlimited"
date = 2024-07-10T04:40:12-06:00
updated = 2024-07-10T04:40:12-06:00
draft = false
weight = 20
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Learn about the various card types in Star Wars Unlimited and their unique characteristics."
toc = true
top = false
+++

## Overview

Star Wars Unlimited features several distinct card types, each with its own role in the game. This section provides a comprehensive overview of these card types and their characteristics.

## General

A card's type is located in the top left corner of the card. There are 6 different types of cards: bases, events, leaders, units, upgrades, and tokens.

{{% alert context="info" %}}
A "resource" is not a type of card, but a game object that a card becomes when placed in the [resource zone](/docs/game-zones/#resource-zone).
{{% /alert %}}

## Base

- Represents a location in Star Wars.
- Has a name, trait(s), HP value, and aspect icon. Some bases also have an ability.
- Each player's deck must have exactly 1 base, which begins the game in its owner's [base zone](/docs/game-zones/#base-zone).
- Can be damaged through abilities and enemy attacks.
- Some abilities heal damage from a base (e.g., [Restore](/docs/keywords/#restore) keyword).
- When a base has no remaining HP, its owner immediately loses the game.

## Event

- Has a name, cost, trait(s), and ability. May also have aspect icons.
- To play: pay its cost, place it in the owner's [discard pile](/docs/game-zones/#discard-pile), then resolve its ability.
- Moves directly from hand to discard pile when played.
- Can affect itself if it affects cards in the discard pile.

## Leader

- Double-sided card with a horizontal "Leader side" and a vertical "Leader Unit side."
- Each side has two aspect icons, a name, subtitle, trait(s), and abilities.
- Each player's deck must have exactly 1 leader, starting in the base zone on its Leader side.
- Deployed using the **Epic Action** ability on its Leader side.
- When defeated as a Leader Unit, it flips to its Leader side and moves to the owner's base zone, exhausted.

## Unit

- Depicts a Star Wars character or vehicle.
- Has a name, cost, power, HP, trait(s), and arena type.
- May have a subtitle, aspect icons, abilities, and a unique icon (⟡).
- Played by paying its cost and placing it in its designated arena (ground or space).
- Enters play exhausted and remains until defeated.
- Defeated when it has no remaining HP or by an ability.

## Upgrade

- Attaches to a unit.
- Has a name, cost, trait(s), power modifier, and HP modifier.
- May have aspect icons, abilities, and a unique icon (⟡).
- Played by paying its cost and attaching it to a unit in play.
- May have specific attachment restrictions.
- Can be attached to friendly or enemy units.
- Defeated when the attached unit leaves play or by an ability.

## Token

- Has a second type, such as "token upgrade."
- Set aside at the start of the game.
- Cannot be shuffled into decks or discarded.
- No limit on tokens available to a player.
- Examples:
  - Experience token: Gives +1 power and +1 HP to the attached unit.
  - [Shield](/docs/keywords/#shield) token: Prevents the next instance of damage to the attached unit.

## Card Anatomy

1. Name: Top of the card (also bottom for upgrades)
2. Subtitle: Under the name (if present)
3. Card Type: Top left of the card
4. Arena Type: Top right (for units)
5. Cost: Top left corner (non-base cards)
6. Aspects: Aspect icons on one side of the card
7. Power: Left side of unit cards
8. Power Modifier: Left side of upgrade cards
9. HP: Right side of unit cards, top left of base cards
10. HP Modifier: Right side of upgrade cards
11. Traits: Under the name (events), under the art (units), or bottom (upgrades)
12. Text Box: Contains card abilities
13. Credit Line: Bottom of the card, with credit and set information

## Interactions Between Card Types

- Units can be upgraded with upgrade cards.
- Events can affect multiple card types.
- Leaders can interact with other card types through their abilities.
- Bases can be affected by various card types and abilities.

## Deckbuilding Considerations

- Each deck must contain exactly 1 base and 1 leader.
- Minimum deck size is typically 50 cards (excluding base and leader).
- No more than 3 copies of a card with the same name in a deck.
- Unique cards (⟡) are limited to 1 copy per deck.

{{% alert context="warning" %}}
For more detailed information on each card type and their interactions, please refer to the [Glossary](/docs/glossary/) and other sections of the comprehensive rules.
{{% /alert %}}

## See Also

- [Game Zones](/docs/game-zones/)
- [Abilities and Effects](/docs/abilities-and-effects/)
- [Keywords](/docs/keywords/)
- [Deckbuilding Rules](/docs/setup-and-victory/#deckbuilding-rules)