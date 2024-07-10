# Star Wars Unlimited: Player Actions

## Table of Contents
A. [Play a Card](#a-play-a-card)
B. [Attack With a Unit](#b-attack-with-a-unit)
C. [Use an Action Ability](#c-use-an-action-ability)
D. [Take the Initiative](#d-take-the-initiative)
E. [Pass](#e-pass)
F. [Important Notes](#f-important-notes)
G. [Timing and Priority of Actions](#g-timing-and-priority-of-actions)
H. [Complex Action Sequences](#h-complex-action-sequences)

During the [Action Phase](turn-structure.md#2-action-phase), players can take one of five actions on their turn:

## A. Play a Card
1. Choose a card from hand (or another zone if specified by an ability).
2. Pay the card's cost in [resources](game-zones.md#d-resource-zone), accounting for any modifiers.
3. Put the card into play ([unit](card-types.md#4-unit) or [upgrade](card-types.md#5-upgrade)) or resolve its ability ([event](card-types.md#2-event)).
4. Resolve any "When Played" [triggered abilities](abilities-and-effects.md#a5-triggered-abilities).

Example: Playing a unit card
- Choose a unit card from your hand
- Pay its cost by exhausting the required number of resources
- Place the unit in the appropriate arena (ground or space)
- Resolve any "When Played" abilities on the unit

Strategic Considerations:
- Consider the current board state and your opponent's available resources before playing a high-value unit.
- Use event cards to respond to your opponent's actions or to set up your own powerful plays.
- When playing upgrades, think about which units are most likely to survive and provide the best value for the upgrade.

## B. Attack With a Unit
1. Choose and exhaust a [ready](game-concepts.md#5-ready-and-exhausted) unit to be the attacker.
2. Choose a target: an enemy unit in the same [arena](game-zones.md#b-ground-arena) or the opponent's [base](game-zones.md#a-base-zone).
3. Resolve any "On Attack" [triggered abilities](abilities-and-effects.md#a5-triggered-abilities).
4. Deal combat damage simultaneously (attacker to defender/base, defender to attacker).
5. Resolve any "When Defeated" abilities for [defeated](game-concepts.md#6-defeating-cards) units.
6. Complete the attack and resolve any relevant abilities.

Example: Attacking with a unit
- Exhaust your 3/2 unit to attack an opponent's 2/3 unit
- Resolve any "On Attack" abilities
- Deal 3 damage to the enemy unit and receive 2 damage
- The enemy unit is defeated; resolve its "When Defeated" ability if it has one

Strategic Considerations:
- Evaluate whether it's more beneficial to attack an enemy unit or the opponent's base.
- Consider potential counter-attacks when deciding which unit to attack with.
- Use units with keywords like [Overwhelm](keywords.md#d-overwhelm) or [Raid](keywords.md#e-raid-x) to maximize attack value.

## C. Use an Action Ability
1. Choose a card with an [action ability](abilities-and-effects.md#a1-action-abilities).
2. Pay the ability's cost (if any).
3. Resolve the ability's effect.

Example: Using an action ability
- Choose a unit with the ability "Action [Exhaust]: Deal 1 damage to a unit"
- Exhaust the unit to pay the cost
- Choose a target unit and deal 1 damage to it

Strategic Considerations:
- Weigh the value of using an action ability against playing a card or attacking.
- Save powerful action abilities for critical moments in the game.
- Consider the timing of your action abilities in relation to your opponent's likely plays.

## D. Take the Initiative
1. Take control of the initiative counter.
2. Flip the initiative counter to its "taken" side.
3. After taking the initiative, the player cannot use their turn to take any further actions for the rest of that round's action phase.
4. The player is considered to have "passed," and they automatically "pass" for all remaining turns they would take that phase.
5. Only one player can take this action per round.

Example: Taking the initiative
- Decide to take the initiative during your turn
- Take control of the initiative counter and flip it to its "taken" side
- You cannot take any more actions this phase, but you will go first next round

Strategic Considerations:
- Take the initiative when you want to secure first action in the next round, especially if you have a powerful play planned.
- Consider taking the initiative if you're in a disadvantageous position and want to reset the tempo of the game.
- Be aware that taking the initiative means giving up all remaining actions in the current round.

## E. Pass
- Declare that you are passing your turn.
- You may pass even if other actions are available.
- When both players pass consecutively, the Action Phase ends.

Example: Passing
- Decide to pass your turn, even if you have playable cards or available actions
- If your opponent also passes on their next turn, the Action Phase ends

Strategic Considerations:
- Pass when you want to conserve resources or force your opponent to act.
- Use passing to bait your opponent into overcommitting before you make your move.
- Consider the risk of passing if your opponent might take the initiative.

## F. Important Notes
- Players must change the game state when they take any action other than passing during their turn. If a chosen action would not change the game state, a player must choose a different action to take or pass.
- Some abilities allow players to take actions outside of their turn or as nested actions.
- Players cannot take more than one action per turn unless specified by a card ability.
- [Ambush](keywords.md#a-ambush) allows a unit to attack as a nested action when played.
- [Epic Action](abilities-and-effects.md#a1-action-abilities) abilities can only be used once per game.

## G. Timing and Priority of Actions

1. Turn Order: 
   - Players alternate taking actions during the Action Phase.
   - The player with the initiative takes the first action each round.

2. Responding to Actions:
   - Players cannot directly interrupt an opponent's action unless they have a card that specifically allows it.
   - After each action, there is a window for triggered abilities to resolve before the next player's turn.

3. Nested Actions:
   - Some abilities allow for nested actions (actions taken during the resolution of another action).
   - Nested actions are fully resolved before returning to the main action sequence.

4. Priority in Simultaneous Effects:
   - If multiple triggered abilities would resolve simultaneously, the active player chooses the order for their abilities, then the opponent chooses the order for theirs.
   - Effects controlled by the active player always resolve first in case of a tie.

5. End of Round:
   - The Action Phase continues until both players pass consecutively.
   - Taking the initiative counts as passing for all remaining turns in the round.

## H. Complex Action Sequences

Here are flowcharts for some complex action sequences:

1. Playing a Card with "When Played" Abilities:
```
Choose Card --> Pay Cost --> Put Card into Play
                                  |
                                  v
              Resolve "When Played" Abilities (if any)
                                  |
                                  v
              Resolve Any Triggered Abilities from Other Cards
                                  |
                                  v
                        End of Action
```

2. Attacking with a Unit:
```
Choose Attacker --> Exhaust Attacker --> Choose Target
         |                                    |
         v                                    v
Resolve "On Attack" Abilities <---- Deal Combat Damage
         |                                    |
         v                                    v
Resolve "When Damaged" Abilities      Resolve "When Defeated" Abilities (if any)
         |                                    |
         v                                    v
Resolve Any Other Triggered Abilities   End of Action
```

3. Using an Action Ability with Nested Actions:
```
Choose Action Ability --> Pay Cost (if any) --> Begin Resolving Effect
                                                        |
                                                        v
                                          Does Effect Allow Nested Action?
                                                   /            \
                                                 Yes            No
                                                 /                \
                                     Perform Nested Action    Continue Resolving Effect
                                               |                    |
                                               v                    v
                               Return to Main Effect      End of Action
```

These flowcharts illustrate the sequence of events for complex actions, helping players understand the order of operations and potential decision points during their turns.

---

For more information on game zones, see the [Game Zones](game-zones.md) section.
For details on card types, refer to the [Card Types](card-types.md) section.
For information on abilities and effects, check the [Abilities and Effects](abilities-and-effects.md) section.