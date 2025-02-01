---
title: Dice Games
---

The [Day's Rest Tavern scene](../scenes/05-the-days-rest-tavern.md) gives the players the opportunity to partake in some card games (which will be dice games in practice) with the patrons of the tavern.
In this section we provide a sample game that you can have them play to simulate the card game.

Everyone puts in a starting bet - the patrons will match a bet of up to 1 GP to start with, the total pot should be ~5GP after all patrons and players have declared themselves in.
To avoid rolling so many dice, have all but one patron duck out after the "up the ante" stage.

## The Game

The game can be summarised as follows:

- Each player has a d4, d6, d12 and d20.
- The player with the highest dice total will win the pot.
However, rolling the maximum number on a dice causes it to "explode" - a player will be allowed to roll an identical dice one additional time to increase their score if this happens, but only after the "up the ante" phase.
- Everyone must put in a buy-in amount just to play the game, set this at something reasonable like 1 SP or a few CP.
- After the initial buy-in players will roll their dice, revealing two values and keeping the others hidden.
Another round of betting (akin to a poker ante) will happen, before totals are revealed and the winner determined.

More details on each stage of the game are provided below.
Multiple rounds of the game can be played, much like a game of poker consists of many hands until one person as won all the chips.
Players are free to leave after the end of a round if they feel they've lost enough or are happy with their winnings and want to cash out.

### Initial Ante

Initial buy-in bets are placed.
Starting with a random player, or the player to the left of whoever won the previous round, a buy-in amount is set.
All players must match this buy-in amount if they want to play in the round.
There is no opportunity to raise this initial buy-in amount, but players are under no obligation to match it if the first player sets a particularly high initial buy-in.

### Initial Roll

Each player who paid the initial ante puts their money into the central pot.

Each player then rolls their dice (d4, d6, d12, d20), keeping the results hidden from the other players and **not** resolving any exploding dice.

Once every player has rolled, each player **must** reveal their d20 and another one of their dice of their choice.
All other dice remain hidden.

### Up the Ante

In poker-style, starting from the player with the highest **revealed total** and proceeding clockwise, each player checks/matches the ante, raises the ante, or folds.

In the event of a tied total, the player who revealed the dice with the most faces (that isn't the d20) goes first.
If this is still a tie, the player who is nearest in clockwise turn order from the player who set the initial ante goes first.

Folding looses all money placed into the pot, including anything already bet during this round and then raised on top of.
Once all players have either folded or matched the highest bet on the table, proceed to the next phase.

### Reveal and Explode

All remaining players reveal their hidden dice.

Starting with the player who last upped the ante, resolve dice explosions to determine the total of each player.
The player with the highest total, **after** resolving explosions, wins the entire pot.
In the event of a tie, the pot is split between winners.

NOTE: Dice can explode multiple times.
If a player rolls a 4 on their d4 for example, then rolls another d4 for the explosion and **also** gets a 4, then they take *another* d4 and roll again.
Each dice adds to their total as did the previous.

## Example

3 players (`A`, `B`, `C`) pay the initial buy-in of 1 SP, and roll their dice.

Scores in **bold** are the ones that the players choose to reveal.

```bash
A : d4 - 2, **d6 - 5**, d8 - 2, **d20 - 19**
B : **d4 - 4**, d6 - 3, d8 - 7, **d20 - 20**
C : **d4 - 3**, d6 - 6, d8 - 8, **d20 - 13**
```

The player with the highest revealed total is tied between player `A` & `B`, however player `A` has revealed their d6 value compared to `B`'s d4, so `A` goes first.
Player `A` checks - seeing `B`'s d20 and d4 that are going to explode.
`B` then plays and opts to up the ante by 1 SP.
`C` elects to match `B`'s bet, hoping that their hidden d6 and d8s that are exploding will tip the balance.
`A` then folds, and since we are back to `B`'s turn with all players having folded or matched the highest bet yet, the up the ante phase is over.
The pot is how 5 SP (3 from buy-in, 2 from up the ante).

`B` then reveals his remaining dice, being the last player to up the ante.
His total is 4 + 3 + 7 + 20 = 34, and then his d4 and d20 explode.
He rolls again, getting a 2 on the d20 and a 3 on the d4.
Thus, his grand total is 4 + 3 + 7 + 20 + 3 + 2 = 39.

`C` then reveals their dice; with a score of 3 + 6 + 8 + 13 = 30.
They re-roll the d6 and d8, getting another 6 on the d6 and a 3 on the d8.
Their second d6 *also* explodes, so they roll another one and get a 4.
This gives a total of 3 + 6 + 8 + 13 + 6 + 4 + 3 = 43.

Player `C` wins and takes the entire pot of 5 SP, and the round ends.
