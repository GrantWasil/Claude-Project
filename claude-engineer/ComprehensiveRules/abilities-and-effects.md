# Star Wars Unlimited: Abilities and Effects

## Table of Contents
A. [Types of Abilities](#a-types-of-abilities)
B. [Effects](#b-effects)
C. [Resolving Abilities and Effects](#c-resolving-abilities-and-effects)
D. [Timing and Triggers](#d-timing-and-triggers)
E. [Nested Abilities and Actions](#e-nested-abilities-and-actions)
F. [Resolving Multiple Triggered Abilities](#f-resolving-multiple-triggered-abilities)
G. [Ability and Effect Interactions](#g-ability-and-effect-interactions)

## A. Types of Abilities

### A.1. Action Abilities
- Indicated by the bolded word "Action" or "Epic Action"
- Usually have a cost in brackets
- Using an action ability counts as the player's action for the turn (see [Player Actions](player-actions.md))
- Examples:
  - "Action [Exhaust]: Deal 1 damage to a unit."
  - "Action [2 Force]: Draw a card."
  - "Epic Action [Destroy this unit]: Defeat all units in the ground arena."

### A.2. Constant Abilities
- Always in effect while the card is in play
- Don't have any special styling
- Remain in effect even if the card is [exhausted](game-concepts.md#5-ready-and-exhausted)
- Examples:
  - "While this unit is undamaged, it has Sentinel."
  - "Your opponent's units lose all abilities."
  - "Your base has +5 health."

### A.3. Event Abilities
- Found in the text box of [event cards](card-types.md#2-event)
- Resolved when the event is played
- Examples:
  - "Deal 2 damage to each unit in the ground arena."
  - "Ready all your units. You may move each of your units to an adjacent arena."
  - "Search your deck for a unit with cost 3 or less and put it into your hand. Shuffle your deck."

### A.4. Keyword Abilities
- Indicated with bold red text
- Have specific associated rules
- Examples: Ambush, Grit, Overwhelm, Raid, Restore, Saboteur, Sentinel, Shielded
- For detailed explanations, see the [Keywords](keywords.md) section
- Additional examples:
  - "Ambush (This unit can attack the turn it enters play.)"
  - "Overwhelm 2 (This unit deals 2 excess damage to the opposing base when it defeats a unit.)"
  - "Shielded (Prevent the first instance of damage that would be dealt to this unit each round.)"

### A.5. Triggered Abilities
- Have bold text indicating their triggering condition
- Start with "When" or "On", followed by a colon and an effect
- Examples:
  - "When Played: Draw a card."
  - "When Defeated: Deal 1 damage to each enemy unit."
  - "On Attack: This unit gets +2 power for this attack."

## B. Effects

### B.1. Lasting Effects
- Affect the game for a specified duration
- Often include phrases like "for this phase" or "for this attack"
- Persist beyond the resolution of the ability that created them
- Examples:
  - "This unit gets +2/+2 for this phase."
  - "Until the end of the turn, your opponent cannot play events."
  - "For the rest of the game, your units have Overwhelm 1."

### B.2. Delayed Effects
- Created when an ability indicates a future timing point or condition
- Resolve automatically after their specified timing point or condition occurs
- Examples:
  - "At the start of your next turn, draw a card."
  - "At the end of this phase, deal 1 damage to each unit."
  - "The next time you play a unit this turn, reduce its cost by 2."

### B.3. Replacement Effects
- Replace part or all of the standard resolution of a triggering condition
- Indicated by the words "instead" or "would"
- Examples:
  - "If this unit would be defeated, instead heal all damage from it."
  - "If you would draw a card, instead look at the top 2 cards of your deck and put one into your hand and the other on the bottom of your deck."
  - "The first time each turn that you would gain Force, instead gain that much Force plus 1."

## C. Resolving Abilities and Effects
- Resolve abilities in the order they are written
- For choices, the player may resolve options in any order
- Abilities that affect both players simultaneously are resolved simultaneously
- If not simultaneous, the controlling player chooses the order

## D. Timing and Triggers
- Triggered abilities resolve at the next available opportunity
- Multiple triggers controlled by one player: that player chooses the order
- Multiple triggers controlled by both players: active player chooses who resolves first
- If both players must resolve triggered abilities on cards they control at the same time:
  1. The active player chooses one player to resolve abilities.
  2. The chosen player resolves all abilities triggered on cards they control in the order of their choice.
  3. Once they finish, the other player does the same on cards they control.
- If an ability instructs a player to "ignore" a keyword ability or aspect penalty:
  - For keywords: Treat the ignored ability as inactive for the specified duration
  - For aspect penalty: Pay the cost of the card without adding the aspect penalty, but the card still retains its aspect icons

## E. Nested Abilities and Actions
- Abilities triggered during the resolution of another ability are "nested"
- Nested abilities must be fully resolved before returning to earlier ability layers
- Example: 
  1. Player A plays a card that defeats an enemy unit. 
  2. The defeated unit has a "When Defeated" ability that triggers.
  3. This "When Defeated" ability is resolved before any other abilities that triggered from the initial card play.

## F. Resolving Multiple Triggered Abilities

When multiple triggered abilities occur simultaneously, follow this flowchart to resolve them:

```
[Start]
     |
     v
Is there more than one triggered ability?
     |
   +---+
   |   |
  Yes  No
   |   |
   |   v
   | Resolve the single ability
   |
   v
Are all triggers controlled by the same player?
   |
 +---+
 |   |
Yes  No
 |   |
 |   v
 | Active player chooses which player resolves first
 |
 v
Controlling player chooses order of resolution
     |
     v
Resolve abilities one at a time
     |
     v
Check for new triggers after each resolution
     |
     v
[End]
```

## G. Ability and Effect Interactions

Understanding how different abilities and effects interact is crucial for mastering Star Wars Unlimited. Here are some key interactions to keep in mind:

1. Constant Abilities vs. Temporary Effects:
   - Temporary effects (e.g., "until end of turn") override constant abilities for their duration.
   - Example: If a unit has a constant ability "This unit has Sentinel" and is affected by "This unit loses all abilities until end of turn," it will not have Sentinel for that turn.

2. Layering Effects:
   - When multiple effects modify a unit's stats, apply them in the order they were created.
   - Example: If a 2/2 unit gets "+1/+1 until end of turn" and then "+2/+0 for this attack," it becomes a 5/3 unit for that attack.

3. Replacement Effects and Prevention:
   - If multiple replacement effects would apply to the same event, the affected player chooses the order in which to apply them.
   - Prevention effects create replacement effects that prevent some or all of a damage event.
   - Example: If a unit with "Prevent the first 2 damage dealt to this unit each turn" would be dealt 3 damage, it prevents 2 damage and takes 1.

4. Triggered Abilities and State-Based Effects:
   - State-based effects (like defeating a unit with 0 health) are checked before triggered abilities resolve.
   - Example: If a 1/1 unit has "When this unit is defeated, deal 1 damage to target unit" and takes 1 damage, it will be defeated before its ability resolves, but the ability will still trigger and resolve.

5. Keyword Interactions:
   - Some keywords have specific interactions with each other or with certain effects.
   - Example: A unit with both Ambush and "When Played" abilities can use its Ambush to attack before its "When Played" ability resolves.

6. Timing Conflicts:
   - When abilities would trigger at the same time but have conflicting results, apply the following priority:
     1. Prevention effects
     2. Replacement effects
     3. Triggered abilities
   - Example: If one effect says "The next time you would draw a card this turn, don't" and another says "At the start of your turn, draw a card," the prevention effect takes precedence, and you don't draw.

Understanding these interactions will help you make better strategic decisions and resolve complex game states accurately.

---

For more information on card types, see the [Card Types](card-types.md) section.
For details on game concepts, refer to the [Game Concepts](game-concepts.md) section.
For information on specific keywords, check the [Keywords](keywords.md) section.