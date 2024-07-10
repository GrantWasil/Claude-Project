# Star Wars Unlimited: Setup and Victory Conditions

## Table of Contents
1. [Game Setup](#1-game-setup)
2. [Victory Conditions](#2-victory-conditions)
3. [Mulligan Strategies and Opening Hand Evaluation](#3-mulligan-strategies-and-opening-hand-evaluation)

## 1. Game Setup
1.1. **Put bases into play**: Each player places their [base](card-types.md#1-base) at the top and center of their own [play area](game-zones.md#i-play-area).

1.2. **Put leaders into play**: Each player places their [leader](card-types.md#3-leader) into play below their base, Leader side faceup.

1.3. **Determine the first player**: Randomly choose a player. That player decides which player begins the game with the [initiative counter](game-concepts.md#3-players-and-turn-structure).

1.4. **Shuffle decks and draw opening hands**: Each player shuffles their [deck](game-zones.md#e-deck), then draws 6 cards.

1.5. **Choose whether to take a mulligan**: Each player may take one mulligan by shuffling their entire hand into their deck and drawing a new hand of 6 cards. The player with the initiative decides first, then their opponent decides.

1.6. **Resource two cards**: Each player chooses two cards from their hand and puts them into play as [resources](game-concepts.md#8-resources-and-costs), facedown and [ready](game-concepts.md#5-ready-and-exhausted).

1.7. **Begin the first round**: Start with the first [action phase](turn-structure.md#2-action-phase).

### Visual Guide for Game Setup

```
[Player 1]
+----------------+----------------+----------------+
|     Deck       |      Hand      |   Discard Pile |
+----------------+----------------+----------------+
|                |                |                |
|  Space Arena   | Resource Zone  |  Ground Arena  |
|                |                |                |
+----------------+----------------+----------------+
|                |    Base        |                |
|                |   Leader       |                |
+----------------+----------------+----------------+
|                |                |                |
|  Ground Arena  | Resource Zone  |   Space Arena  |
|                |                |                |
+----------------+----------------+----------------+
|   Discard Pile |      Hand      |     Deck       |
+----------------+----------------+----------------+
[Player 2]

      Initiative Counter (placed between players)
```

## 2. Victory Conditions
The game ends immediately when one of the following conditions is met:

2.1. **Base Destruction**: If a player's base reaches 0 remaining HP and is defeated, that player loses the game, and their opponent wins.

2.2. **Concession**: A player can concede the game at any time, immediately losing the game.

2.3. **Empty Deck**: If a player would draw a card from their empty deck, they instead deal 3 damage to their base for each card they would draw. If this causes their base to reach 0 HP, they lose the game.

2.4. **Simultaneous Base Destruction**: In the case where both players' bases reach 0 remaining HP at the same time, the game ends in a draw.

**Note**: Once a player's base has 0 remaining HP, they cannot take any actions, and cannot resolve any abilities or effects.

### Examples of Victory Scenarios

1. **Base Destruction Example**:
   Player A's base has 2 HP remaining. Player B attacks with a unit that has 3 power. The attack deals 3 damage to Player A's base, reducing it to 0 HP. Player A immediately loses the game, and Player B wins.

2. **Empty Deck Victory**:
   Player A has 1 card left in their deck and 4 HP on their base. They play an event card that says "Draw 3 cards." They draw their last card, then must deal 6 damage (3 for each of the 2 cards they couldn't draw) to their base. This reduces their base to 0 HP, causing them to lose the game.

3. **Concession During Complex Game State**:
   Player B is facing a powerful board state from Player A, with multiple threats and little hope of turning the game around. Even though their base still has 10 HP, Player B decides to concede, giving the victory to Player A.

4. **Simultaneous Base Destruction**:
   Both players have 2 HP left on their bases. Player A plays an event that deals 2 damage to each player's base. Both bases reach 0 HP simultaneously, resulting in a draw.

5. **Last-Second Victory**:
   Player A has 1 HP left on their base, while Player B has 5 HP. It's Player A's turn, and they play a combination of cards that allows them to deal 5 damage to Player B's base, securing an unexpected victory.

## 3. Mulligan Strategies and Opening Hand Evaluation

When deciding whether to keep your opening hand or take a mulligan, consider the following factors:

### 3.1 Resource Curve
- Aim for a mix of low-cost and high-cost cards.
- Ideally, have at least 2-3 cards you can play in the first few turns.

### 3.2 Aspect Balance
- Ensure you have cards that match your leader and base aspects to avoid [aspect penalties](game-concepts.md#7-aspects-and-unique-cards).

### 3.3 Unit-to-Event Ratio
- Look for a balance between units and events.
- Having at least 2-3 units in your opening hand is generally desirable.

### 3.4 Synergy with Leader
- Consider cards that work well with your leader's abilities.

### 3.5 Counter-Play Options
- If you know your opponent's strategy, consider keeping cards that can counter it.

### Example Mulligan Scenarios:

1. **Keep**: 2 low-cost units, 1 mid-cost unit, 2 events, 1 high-cost unit
   Reasoning: Good resource curve, mix of units and events, options for early plays.

2. **Mulligan**: 4 high-cost units, 2 off-aspect events
   Reasoning: No early plays, risk of dead draws due to aspect penalties.

3. **Keep**: 3 on-aspect low-cost units, 2 mid-cost events, 1 resource-generation card
   Reasoning: Strong early game presence, ability to ramp into bigger plays.

4. **Consider Mulligan**: 2 low-cost units, 4 high-cost cards
   Reasoning: While there are some early plays, the hand is too top-heavy and risks falling behind.

Remember, the decision to mulligan should be based on your deck's strategy, your knowledge of the meta-game, and your personal playstyle. Sometimes, a risky keep can pay off if it aligns well with your overall game plan.

---

For more information on game concepts, see the [Game Concepts](game-concepts.md) section.
For details on turn structure, refer to the [Turn Structure](turn-structure.md) section.