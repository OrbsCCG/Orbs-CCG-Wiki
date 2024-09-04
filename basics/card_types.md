# Card Types

## Overview

There are six card types in Orbs CCG: Minions, Objects, Actions, Locations, Energizers, and Secrets. Each card type has different rules for how it affects the game. This document will explain the rules for each card type. While there are six card types, only four card types are present on cards: Minions, Objects, Actions, and Locations. Any type of card can become an Energizer or Secret, but those types are not present on cards.

## Minions

Minions are the primary way to deal damage to your opponent. They are played from your hand and can attack your opponent during the battle phase. Minions can also block your opponent's minions, to prevent damage from being dealt to you. Minions have a power value, representing how much damage they deal, and a health value, representing how much damage they can take before being destroyed. Damage is cleared at the end of every clear phase, which happens at the end of the turn in live play, and after the defensive battle in async play.

Minions can have abilities that affect the game in some way. Some abilities are triggered abilities, which activate when a certain condition is met. Other abilities are static abilities, which are always active. Minions can also have keywords, which are abilities that are common to many cards. For example, a minion with the [Speedy](../rules/glossary.md#speedy) keyword can attack or exhaust the turn it enters play. Finally, some minions have [Entrance](../rules/glossary.md#entrance) or [Deathknell](../rules/glossary.md#deathknell) abilities, which are triggered abilities that trigger when the minion enters or dies.

Some example minion cards include: Forest Troll, Friendly Giant, Fireblazer, Bug Breeder, Mind Goblin, and Avid Conqueror.

[[Friendly Giant]]

## Objects

Objects are permanents that affect the game in some way other than by attacking or blocking. They are played from your hand and typically have some sort of ability. Objects can be destroyed by certain cards, but they do not take damage.

Some example object cards include: Capturing Mirror, Mistfoil, Lost Key, The Orb of Hostility, and The Orb of Destruction.

[[The Orb of Destruction]]

## Actions

Actions are cards that are played from your hand and have an immediate effect. They are not permanents, so they are placed into the graveyard after they resolve. Actions can have a variety of effects, such as dealing damage, drawing cards, or destroying permanents. You can't deny that actions are an important part of Orbs CCG.

Some example action cards include: Banish, Deny, Execute, Fire Rain, Invigorate, and Half Life.

[[Fire Rain]]

## Locations

Locations are permanents that affect the game in some way while they are in play. They are similar to objects, but are not vulnerable to cards that can destroy objects. There can only be one location in play at a time, so playing a new location will replace the old one.

Some locations have the [Homeland](../rules/locations.md#homeland) subtype. The player going last in the game may start with a [Homeland](../rules/locations.md#homeland) location of their choice in play. This gives them some compensation for going second, as otherwise the first player's tempo advantage would be quite strong such that you'd always want to go first.

Some example location cards include: Deep Blue Sea, Enlightened Village, Active Volcano, Cave of the Recluse, and Ant Colony.

[[Cave of the Recluse]]

## Energizers

Energy is a resource that is used to play cards, and it is generated primarily with Energizers. Once during your turn, you may energize a card from your hand, which means you put it into play upside down. It has no abilities other than its energy generating ability, which generates one energy of its color. However, multicolor cards generate one colorless energy, since they aren't imbued with the full energy of any of their colors.

Energizers are technically named "Energized [original card name]", have 0 energy value, have the colors of their original card (or colorless if they were a multicolor card). This is relevant, for example, with some Homelands (Crimson Crags, Dark Wasteland, Deep Blue Sea, Enlightened Village, Underground Cavern, Verdant Forest) whose abilities have conditions like "Activate only if the number of green energizers you control is at least half the number of energizers you control." What this means is you can't use the ability if you have 1 green energizer and 2 non-green energizers, since half of 3 is 1.5, and you only have 1 green energizer.

## Secrets

Secrets are cards with the Secret ability, allowing them to be played face down. Invoking a card as a secret costs its "To Secret" energy cost, which is just 2 total energy (although some might require specific colors). They can later be invoked for their "From Secret" cost.

Some secrets might also have a timing condition that lets them get invoked for their alternative cost at other times, provided the timing condition is met. However, if they are not used immediately after the timing condition is met, then the player will have missed the timing, and they won't be able to use the alternative cost. In async play, secrets with timing conditions will be automatically invoked when the timing condition is met, allowing for some interactivity during the opponent's turn.

Interfere is a card that can be invoked face down as a secret.

[[Interfere]]

As you can see from its Secret ability, Interfere can be played face down then later used to negate other cards.
