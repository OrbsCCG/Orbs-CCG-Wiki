# Glossary

Some cards have abilities that are denoted by keywords. These keywords have a specific meaning and are used to make the card text shorter and more readable. The following is a list of keywords and their meanings.

## Aegis

Targeting permanents with Aegis by anyone other than its controller costs that much additional energy. This only applies to invoked cards and activated abilities for now, although that may change in the future to also apply to targeted triggered abilities.

[[Velken Engineer]]

Velken Engineer is an example of a card with Aegis. If an oponent wanted to use a spell to kill this creature, like Flame Spike, they would have to pay 1 extra energy in this case.

## Banished Zone

To banish a card from the field, place it in a special zone called the banished zone. Cards in the banished zone cannot be interacted with any longer. Banishing does not count as dying.

[[Banish]]

You may want to banish a card to get around abilities that trigger when a card dies, or abilities like indestructible.

## Boost Counters

**Boost counters** are a type of counter that can be placed on a minion. They give the minion +1/+1 for each Boost counter on it.

![Meditating Monk with 2 Boost counters](/wiki-assets/cards/meditating_monk_boost_counters.png)

The Meditating Monk card gets a Boost counter whenever you gain health. This lets the minion get stronger as the game progresses. Normally Meditating Monk is a 3/3, but with 2 Boost counters as in the above picture, it becomes a 5/5. Boost counters are represented by a number in the top right corner of the card.

## Coveted

At the end of battle, if you were dealt battle damage and control a permanent with the **Coveted** keyword, your opponent gains control of that permanent.

[[The Orb of Destruction]]

## Deathknell

Deathknell abilities occur when the card is destroyed in some way. They do not occur if the card is banished or otherwise removed from play without being destroyed.

[[Fireblazer]]

Fireblazer will deal 1 damage to any target when it dies because of its Deathknell ability.

## Defensive

A minion with Defensive cannot attack as normal.

[[Cavern Barrier]]

Cavern Barrier is a good defensive minion. It will block for you, but it can't attack.

## Destroy

Destroyed permanents are placed into the graveyard. If they have a Deathknell ability, that ability will trigger.

[[Execute]]

Execute will destroy any minion, regardless of how much health it has.

## Dueling

[//]: # 'WIP'

## Entrance

[//]: # 'WIP'

Entrance is a keyword that triggers an ability when a permanent enters the field.

[[Abyssal Spirit]]

In this case, when this minion enters the field, your opponent loses health based on the ammount of black minions you control, bringing them closer to death.

## Exhaust

Cards become exhausted when they attack or use an ability that requires exhausting. Exhausted cards cannot attack or use abilities that require exhausting since they are already exhausted. Cards cannot attack or use abilities that require exhausting the first turn they enter play unless they have the Speedy keyword. Cards automatically unexhaust at the start of your first main phase each turn.

[[The Orb of the Sun]]

The Orb of the Sun will exhaust in order to generate energy. This means you can only use it once per turn (unless you have a way to unexhaust it).

## Fearsome

Minions with Fearsome can only be blocked by two or more minions at a time.

[[Zombie Horde]]

It'll take more than one minion to block the Zombie Horde!

## First Shot

Minions with First Shot deal battle and duel damage before other minions without First Shot.

[[Nexi Trebuchet Team]]

Nexi Trebuchet Team is a good example of a card with the **First Shot** keyword, but only when it is attacking. This means that it will deal its battle damage before other minions without **First Shot**.

## Flyer

A minion with the **Flyer** keyword can only be blocked by other minions with the [Flyer](./glossary.md#flyer) keyword or minions with the [Range](./glossary.md#range) keyword.

[[Mystic Pelican]]

## Health Hitter

A minion with **Health Hitter** gains health for its controller when it deals damage. This is a great way to keep yourself alive while attacking your opponent! If you are being attacked by a Health Hitter, you may want to block it rather than try to outrace it, since it is difficult to beat an opponent who is gaining health every turn.

[[Magus of the Light]]

## Invincible

A minion with the **Invincible** keyword cannot be destroyed by damage or "destroy" abilities as normal.

[[Protector of Orbs]]

Protector of Orbs will give a Construct the Invincible keyword temporarily, preventing that other Construct from being destroyed.

## Invoke

When you **invoke** a card, you play it from your hand. The card is then put on the stack as an invocation. The card is not considered to be in play until the invocation resolves, which in live play requires both players to pass priority. In async play, just the player whose turn it is needs to pass priority. If you have the auto-pass after invoking my own cards setting enabled, you will not need to manually pass priority after invoking your own cards, since the game will do it for you.

Some cards may be able to target an invocation on the stack. This is a way to interact with cards that are not yet in play. For example, Interfere can _negate_ an invocation on the stack.

## Leaves the Field

Some cards have abilities that trigger when they "Leave the field," which means it triggers if they die, are banished, are returned to your hand, or anything else that would cause them to leave the field.

[[Intrepid Adventurer]]

Intrepid Adventurer draws you a card when it leaves the field. This is most likely to happen when it dies. It's also a great target for levelling up, since the original card is banished when you level it up.

## Level Up

When you **level up** a minion card, you search your deck for a minion card with energy value 1 or 2 greater, whose colors and subtypes are a superset of the original minion's properties. The new card replaces the old one. If you didn't find a card, instead put 2 Boost counters on the original minion.

[[Eager Apprentice]]

For example, Eager Apprentice, a yellow Human that costs 2 total energy, can level up into Nexi Trebuchet Team (it costs 3 total energy, is yellow, and a Human) or Avian Lightbearer (it costs 4 total energy, is yellow, and Human). It couldn't level up into a card that costs 5 or more energy, or a card that is not yellow or Human.

[[Avian Lightbearer]]

Note that colorless cards can level up into any card of the appropriate energy cost and subtypes, regardless of the color, since colorless is not a color.

## Lethal

Any amount of damage from minions with Lethal is sufficient to destroy another minion.

[[Toxic Scarab]]

For example, Toxic Scarab only has 1 power, but it can destroy any minion it damages, no matter how much health that minion has, because it has the Lethal keyword.

[//]: # 'will need to explain how to assign damage if minion has for example 2 power, if it works like deathtouch in mtg'

## Liquidate

Liquidated [permanents](./glossary.md#permanent) are placed into the graveyard.

[[Devoured by Sharks]]

Devoured by Sharks is a good example of a card with the **Liquidate** keyword. It forces your opponent to put two of their permanents from the field into their graveyard.

## Nimble

Cards with **Nimble** may be invoked at any time. This means that, during live play, they may be invoked during an opponent's turn, during battle, or even while another card or ability is on the stack. For async play, while you do not manually take any game actions during an opponent's turn, your **Nimble** Secrets will auto-invoke themselves if their timing condition is met.

Remember that async play does not allow you to cast other cards during your opponent's turn, however in async play, some Nimble secrets can activate on their own.

[[Mind Goblin]]

Mind Goblin is a good example of a card with the **Nimble** keyword. It can be invoked at any time, even during your opponent's turn.

[[Tree Nuts]]

If you have a Mind Goblin in play and another **Nimble** card in the hand, such as Tree Nuts, invoking that card during your opponent's turn will let you draw a card with Mind Goblin's triggered ability. Mind Goblin + Tree Nuts = synergy!

[[Nocturnal Kraken]]

Note that all activated abilities have the normal timing restriction that prevents them from being invoked during an opponent's turn, during battle, or while another card or ability is on the stack. Some abilities have the **Nimble** keyword, which allows them to be used at any time. For example, Nocturnal Kraken has two abilities, the first of which can only be used with non-Nimble timing, while the second can be used at any time you have priority.

## Overwhelming

[//]: # 'WIP'

Remaining battle damage follows through the player

## Permanent

A **permanent** is a card that remains in play after it is invoked (invoked means it is played). Unlike action cards, it is not discarded at the end of the turn. Minions, objects, energizers, and secrets are all permanents.

## Range

A minion with the **Range** keyword can block minions with the [Flyer](./glossary.md#flyer) keyword.

[[Ageless Hyperion]]

## Search Your Deck

When a card instructs you to search your deck for a card, you may look through your deck and take the card you want. After searching your deck, you always shuffle it. You may choose not to find a card if you wish.

[[Campaign Recruiter]]

Campaign Recruiter is a good example of a card that lets you search your deck to find Knight cards.

## Spark Jars

**Spark Jars** are a type of token that can be used to improve the next non-battle damage you'd deal, or an Elemental's power. They are created by various cards, such as Spark Prospector. The Spark Jar token is considered to have subtypes Elemental and Construct, and has the abilities: "Liquidate: The next time a source you control would deal non-battle damage, it deals that much damage plus 1 instead." and "Liquidate: Target Elemental minion you control gains +1/+0 until the next clear." Basically, it allows your cards and Elemental minions to deal 1 more damage than they normally would.

If you want to use a Spark Jar's ability, you must do so before the damage is dealt. Once the damage is dealt, it would be too late to activate the ability.

Spark Jars are also Speedy, meaning they can be used the turn they are created.

[[Spark Jar Token]]

## Speedy

A permanent with **Speedy** can attack and use abilities that require exhausting the turn it enters play. (Normally, only energizers can exhaust the turn they enter play.) For example, Agnu's Hellraisers can attack the turn it enters play.

[[Agnu's Hellraisers]]

## Unblockable

An **Unblockable** minion cannot be blocked by an opponent's minions.

[[Secretive Spy]]

With this minion, you can give it unblockable for the price of a card, making it easier for you to draw the card back when dealing combat damage with Secretive Spy.

## Unique

Cards with the **Unique** keyword cannot be invoked if you already control another card with the same name. You can still energize the card, however. **Unique** cards represent one-of-a-kind characters or items, typically with a unique name.

[[The Orb Of The Pack]]

[//]: # 'What happens if oponent steals an orb like this one, I play another one and then steal the first one after dealing combat damage with the coveted ability? Do I keep to play both? can this happen then with more?'

## Unlimited

A deck may contain any number of cards with the **Unlimited** keyword. This means that the rule of 5 times this card in the deck is not

[[Go To Hell]]
