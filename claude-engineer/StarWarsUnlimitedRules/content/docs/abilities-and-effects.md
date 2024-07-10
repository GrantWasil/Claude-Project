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

An ability is specialized game text that indicates how a card affects the game. If a card has any printed abilities, they are found in the text box of that card.

An [upgrade](/docs/card-types/#upgrades) can give an ability to a [unit](/docs/card-types/#units) if that upgrade indicates that the attached unit "gains" the ability; treat the unit as having the ability in its text box for as long as the upgrade is attached to it.

Unless otherwise specified, a player controls the abilities on cards they play and control.

An effect is a non-cost part of a card ability that has the potential to change the game state. Some effects resolve separately from the ability that created them, or replace the standard resolution of the ability that created them.

## Types of Abilities

### Constant Abilities

- A constant ability is always in effect while the card it is on is in play. Constant abilities don't have any special styling.
- A constant ability immediately comes into effect when the card it is on enters play and remains in effect while the card is in play.
- Some constant abilities continuously check the game for a specific condition to be met for their effects to apply to the game. These abilities usually include the word "while."
- Constant abilities remain in effect even if the card they're on is exhausted.

Example: "While this unit is attacking, it gets +2 power."

### Triggered Abilities

- Triggered abilities have bold text indicating their triggering condition, starting with the word "When" or "On", followed by a colon and an effect.
- For a triggered ability to resolve, the card with the ability must be in play when the triggering condition occurs, unless the ability specifies that it can be triggered from an out-of-play zone.
- A triggered ability must resolve once its triggering condition is met unless the ability uses the phrase "you may."

Example: "**When this unit enters play:** Draw a card."

### Action Abilities

- An action ability is an ability indicated by the bolded word "Action."
- Most action abilities have a cost in brackets that must be paid in order to use the ability.
- Using an action ability is one type of [action](/docs/player-actions/) a player can take during their turn.
- An Epic Action ability is a type of action ability that can only be used once per game.

Example: "**Action [Exhaust]:** Ready another unit you control."

### Event Abilities

- An event ability is an ability found in the text box of an [event](/docs/card-types/#events) and is resolved when the event is played.
- When an event is played, it is placed in its owner's [discard pile](/docs/game-zones/#discard-pile) before its ability resolves.
- An event ability must be resolved as completely as possible. Any part of the event ability that cannot be resolved is ignored.

Example: "Deal 2 damage to target unit."

### Keyword Abilities

- A keyword or keyword ability is a card ability indicated with bold red text and that has specific associated rules. For more details, see the [Keywords](/docs/keywords/) section.
- A keyword ability resolves automatically unless its definition includes the word "may."
- If a card is given a keyword it already has, those keywords do not "stack" unless those keywords are followed by a numeral, a cost, or an em dash and ability text.

Example: "**Ambush**" (Allows a unit to ready and attack when played if there's a valid target)

## Effects

### Lasting Effects

- A lasting effect is a part of an ability that affects the game for a specified duration of time. Most lasting effects include the phrase "for this phase" or "for this attack."
- A lasting effect persists beyond the resolution of the ability that created it and for the duration specified by the ability, even if the ability that created the effect was on a card that left play.

Example: "Target unit gets +3 power for this phase."

### Delayed Effects

- A delayed effect is created when a card ability indicates a future timing point or a future condition that may arise and an effect that will happen at that time.
- Delayed effects resolve automatically and immediately after their specified timing point or future condition occurs, before any other abilities triggered by that timing point or condition.

Example: "At the end of this phase, destroy this unit."

### Replacement Effects

- A replacement effect occurs when part or all of the standard resolution of a triggering condition or ability is replaced with an alternate resolution. This alternate resolution is the "replacement effect."
- Replacement effects are indicated by the words "instead" or "would."
- A replacement effect must be resolved immediately upon its condition being met, unless the effect uses the phrase "you may."

Example: "If this unit would be defeated, instead return it to your hand."

## Resolving Abilities and Effects

1. When a player resolves an ability, they must resolve the effects of that ability in the order they are written.
2. If an ability allows a player to choose some number of options, they may resolve those options in any order.
3. If an ability that affects both players can be resolved simultaneously, resolve the ability simultaneously. Otherwise, the player that controls the card with the ability can choose the order in which each player is affected by the ability.

## Timing and Triggers

1. A triggered ability is considered to resolve during the same turn or game step that it was triggered. For more information on turn structure, see the [Turn Structure](/docs/turn-structure/) section.
2. Resolving a triggered ability is not the same as taking an action. A player can resolve a triggered ability outside of their turn.
3. If an ability triggers during or as the result of a non-attack action, resolve that ability at the next available opportunity after that action is fully completed.
4. If an ability triggers during an attack, resolve that ability at the appropriate timing point within that attack.
5. If a player must resolve multiple triggered abilities on cards they control at the same time, that player chooses the order in which to resolve those abilities.
6. If both players must resolve triggered abilities on cards they control at the same time, the active player chooses one player at a time to resolve abilities. When chosen, that player resolves all abilities triggered on cards they control in the order of their choice, and once they finish, the other player does the same on cards they control.
7. After resolving a triggered ability "A", if any new abilities were triggered while resolving it, the new abilities are considered "nested abilities" and must be resolved before any other abilities triggered at the same time as ability "A".

{{% alert context="info" %}}
For more detailed information on specific abilities and their interactions, please refer to the [Glossary](/docs/glossary/) and other sections of the comprehensive rules document.
{{% /alert %}}

## See Also

- [Card Types](/docs/card-types/)
- [Game Zones](/docs/game-zones/)
- [Turn Structure](/docs/turn-structure/)
- [Player Actions](/docs/player-actions/)
- [Keywords](/docs/keywords/)