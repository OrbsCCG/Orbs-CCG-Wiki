# Turn Structure

## Overview

Each turn unfolds in a series of phases, and these phases are different depending on whether you are in an async or live game. However, both games have the same types of phases, just in different orders. Here is a summary of the different types of phases, followed by the ordering of the phases for each type of game.

## Pregame

While not technically part of the turn, before a game begins, there is a "pregame". One player is randomly chosen to decide whether to play first or second. The player who goes first does not draw a card on their first turn. This is to balance the tempo advantage of going first. Further, the player going second gets to start with their choice of [Homeland](../rules/locations.md#homeland) location from their deck in play.

[//]: # 'player 1 starts with 7 cards and player 2 with 8?'

## Main Phase

The main phase is when the current player (the player whose turn it is) can invoke cards from their hand, energize one card per turn, and play objects and secrets. The main phase is generally where the player develops their board.

At the start of the first main phase of a player's turn, their permanents all unexhaust, and they draw a card. This happens automatically.

## Battle Phase

The battle phase is when the current player can attack with their minions. The defending player can choose to block any number of the attacking minions, or none. If a minion is blocked, it deals damage to the blocking minions, and the blocking minions deal damage back. If a minion is not blocked, it deals damage to the defending player. In async play, there are actually two battle phases, a defensive battle phase at the start of your turn, and an offensive battle phase at the end of your turn. You can think of it as the battle phase being carried over from the end of one turn to the start of the opponent's turn.

An attacking minion can be blocked by more than one minion at a time. If a minion is blocked by multiple minions, it distributes its damage among each of them, and each of them deals damage back. In live play, the attacking player can choose how to distribute damage, however in async play the game will automatically distribute damage for the player.

## Clear Phase

At the end of a clear phase, all damage and temporary effects are removed from permanents in play. This means that if you did not deal enough damage to kill a minion, it will be back to full health at the end of the clear phase. In live play, the clear phase happens at the end of each turn, but in async play it happens after the defensive battle phase. This means that, in async play, a player can use temporary abilities on their minions during their turn, then attack, and these temporary abilities will still work through the rest of the battle even though it takes place during the next turn.

## Live Game Phase Order

In a live game, the phases go: main 1, battle, main 2, clear. This means that you can play cards, attack, play more cards, then everything is reset for the next turn.

## Async Game Phase Order

In an async game, the phases go: defensive battle, clear, main, offensive battle. This means that, at the start of your turn, you have to defend against any incoming attackers. The defensive battle phase is skipped if there are no attackers. Then there is a clear phase, where all damage and temporary effects are reset back to normal. Then the main phase happens, where your permanents unexhaust, and you draw a card, then get an opportunity to play cards. Finally, you can attack with your minions.

Compared with the Live Game Phase Order, you're only missing the second main phase, so remember to cast everything you want before combat.
