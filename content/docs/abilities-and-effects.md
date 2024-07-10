+++
title = "Abilities and Effects"
description = "An overview of abilities and effects in Star Wars Unlimited"
date = 2024-06-21T00:00:00+00:00
updated = 2024-06-21T00:00:00+00:00
draft = false
weight = 50
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Understanding the various abilities and effects in Star Wars Unlimited"
toc = true
top = false
+++

Abilities and effects are core components of Star Wars Unlimited, defining how cards interact with each other and impact the game state. This section provides a comprehensive overview of the different types of abilities and effects, their resolution, and timing considerations.

## Table of Contents
1. [General](#general)
2. [Types of Abilities](#types-of-abilities)
3. [Effects](#effects)
4. [Resolving Abilities and Effects](#resolving-abilities-and-effects)
5. [Timing and Triggers](#timing-and-triggers)

## General

An ability is specialized game text that indicates how a card affects the game. If a card has multiple different abilities, each ability begins on a new line.

When a player resolves an ability, they resolve as much of the ability as possible, and ignore any part of the ability that cannot be resolved.

An effect is a non-cost part of a card ability that has the potential to change the game state. Some effects resolve separately from the ability that created them, or replace the standard resolution of the ability that created them.

## Types of Abilities

### Constant Abilities

- A constant ability is always in effect while the card it is on is in play. Constant abilities don't have any special styling.
- A constant ability immediately comes into effect when the card it is on enters play and remains in effect while the card is in play.
- Some constant abilities continuously check the game for a specific condition to be met for their effects to apply to the game. These abilities usually include the word "while."
- Constant abilities remain in effect even if the card they're on is exhausted.

Example: "While this unit is undamaged, it gains Sentinel."

### Triggered Abilities

- Triggered abilities have bold text indicating their triggering condition, followed by a colon and an effect.
- Common triggering conditions include "When Played", "When Defeated", and "On Attack".
- A triggered ability must resolve once its triggering condition is met unless the ability uses the phrase "you may."

Example: "**When Played**: Give an enemy unit -3/-3 for this phase."

### Action Abilities

- An action ability is an ability indicated by the bolded word "Action."
- Most action abilities have a cost in brackets that must be paid in order to use the ability.
- Using an action ability is one type of action a player can take during their turn.
- An Epic Action ability is a type of action ability that can only be used once per game.

Example: "**Action [Exhaust]:** Ready another unit you control."

### Event Abilities

- An event ability is an ability found in the text box of an event and is resolved when the event is played.
- When an event is played, it is placed in its owner's discard pile before its ability resolves.
- Events do not enter play; they move directly from the player's hand to their discard pile.

Example: "Deal 2 damage to target unit."

### Keyword Abilities

- A keyword or keyword ability is a card ability indicated with bold text and that has specific associated rules.
- A keyword ability resolves automatically unless its definition includes the word "may."
- If a card is given a keyword it already has, those keywords do not "stack" unless those keywords are followed by a numeral, a cost, or an em dash and ability text.

Example: "**Ambush**" (Allows a unit to ready and attack when played if there's a valid target)

## Effects

### Lasting Effects

- A lasting effect is a part of an ability that affects the game for a specified duration of time. Most lasting effects include the phrase "for this phase" or "for this attack."
- A lasting effect persists beyond the resolution of the ability that created it and for the duration specified by the ability, even if the ability that created the effect was on a card that left play.
- Multiple lasting effects can apply to the same unit at the same time. If a new lasting effect conflicts with an existing lasting effect, the new effect takes precedence.

Example: "It gets +3/+0 for this attack."

### Delayed Effects

- A delayed effect is created when a card ability indicates a future timing point or a future condition that may arise and an effect that will happen at that time.
- Delayed effects resolve automatically and immediately after their specified timing point or future condition occurs, before any other abilities triggered by that timing point or condition.
- Once created, a delayed effect will resolve at the specified timing point or condition, even if the ability that created it was on a card that left play.

Example: "At the start of the regroup phase, draw 1 card."

### Replacement Effects

- A replacement effect occurs when part or all of the standard resolution of a triggering condition or ability is replaced with an alternate resolution.
- Replacement effects are indicated by the words "instead" or "would."
- A replacement effect must be resolved immediately upon its condition being met, unless the effect uses the phrase "you may."
- When a replacement effect resolves, the standard resolution of the ability does not resolve and is ignored.

Example: "If damage would be dealt to attached unit, prevent that damage. If you do, defeat a Shield token on it."

## Resolving Abilities and Effects

1. When a player resolves an ability, they must resolve the effects of that ability in the order they are written.
2. If an ability allows a player to choose some number of options, they may resolve those options in any order.
3. If multiple delayed effects must be resolved at the same time, the player that controls the cards that created those delayed effects chooses the order in which those effects resolve.
4. If multiple replacement effects are triggered by the same condition, the player that controls the cards with the replacement effects chooses which effect(s) to resolve.

## Timing and Triggers

1. If an ability instructs a player to take multiple actions, that player performs each action sequentially. Any abilities triggered during or as a result of each action are considered nested abilities, and must be resolved before proceeding to the next action.
2. If both players have one or more delayed effects that must be resolved at the same time, the active player chooses one player at a time to resolve effects. When chosen, that player resolves all delayed effects created by cards they control in the order of their choice, and once they finish, the other player does the same for their effects.
3. If both players have one or more replacement effects triggered by the same condition, the controller of the affected object or the affected player chooses to resolve effects in any order until the condition no longer applies.

{{% alert context="info" %}}
For more detailed information on specific abilities and their interactions, please refer to the [Glossary](/docs/glossary/) and other sections of the comprehensive rules document.
{{% /alert %}}

## See Also

- [Card Types](/docs/card-types/)
- [Game Zones](/docs/game-zones/)
- [Turn Structure](/docs/turn-structure/)
- [Player Actions](/docs/player-actions/)
- [Keywords](/docs/keywords/)