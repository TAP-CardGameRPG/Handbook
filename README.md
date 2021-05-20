<p align="center">
  <img src="images/logo.png" width="256"/>
</p>

---

# Table of Contents
- [Table of Contents](#table-of-contents)
- [About](#about)
- [Terminology Reference](#terminology-reference)
  - [Cards vs Decks vs Bags](#cards-vs-decks-vs-bags)
  - [Campaigner](#campaigner)
  - [Protagonist](#protagonist)
  - [Actor](#actor)
- [Board Layout](#board-layout)
  - [Player's Layout](#players-layout)
    - [Field](#field)
    - [Player Reference](#player-reference)
  - [Campaigner](#campaigner-1)
- [Skills](#skills)
  - [Active Skills](#active-skills)
  - [Passive Skills](#passive-skills)
  - [Requirements](#requirements)
- [Items](#items)
  - [Inventory](#inventory)
- [Equipment](#equipment)
  - [Held Equipment](#held-equipment)
  - [Worn Equipment](#worn-equipment)
- [Status Effects](#status-effects)
- [Character Struggles](#character-struggles)
  - [Physical Struggles](#physical-struggles)
  - [Mental Struggles](#mental-struggles)
- [Attributes](#attributes)
- [Leveling](#leveling)
  - [Experience](#experience)
- [Currency](#currency)
- [Relationships](#relationships)
  - [Allies](#allies)
  - [Friends](#friends)
  - [Enemies](#enemies)
  - [Adversaries](#adversaries)
- [Quirks](#quirks)
- [Character Backstory](#character-backstory)

---

# About

TAP is a collective card game based role playing game. In the game of TAP, the setting and mood are just as important as the strategy and wit, the atmosphere creates a world saturated in imagination and cunning. The only limits in the game rest between the imagery in your mind and the cards in your hand.

# Terminology Reference

Throughout this document, there are several terminologies that are used constantly. These terminologies and their meanings are listed here for your convenience.

## Cards vs Decks vs Bags

In the game, there terms "Cards", "Decks" and "Bags" are used when describing objects or locations in the game. While these three terms describe similar concepts, they have unique differences.

* **Card:** A card is an unmodifiable constant in the world that is used to describe an object or initialize a deck. An example of this might be an augmentation that can be applied to an item. The augmentation itself cannot be modified, but it can be added to an item deck to modify that item.

* **Deck:** A deck is a unique object within the game. This can be an item instance, a character, a scene, and so on. All of the cards within this deck are used to describe various aspects of this object and how this object should behave. It's worth noting that a deck may often consist of a single card, such as a generic apple that has no note-worthy properties. A deck containing only a single card should not be confused with a card.

* **Bag:** A bag is simply used to hold a list of decks or cards. It itself is not an object but a collection of objects or modifiers. An example of this might be a player's inventory that contains a list of item decks.

* **Infinite Bag\*:** An infinite bag is a special type of bag who's contents are, well, infinite. It is assumed that an infinite bag contains an infinite amount of a single, specific card. This is often used when containing things such as money that is not being held by any player.

## Campaigner

The Campaigner is the player who's job it to progress the story. While they do not have a single actor that they control, unlike other players, they take on the role of all other entities in the game. Main characters, monsters, environments, etc. It is their job to progress the story of the campaign above all else.

The campaigner is given a series of missions to complete by the chosen senario of the session and must guide the actors along this storyline using any available resources in their disposal in order to complete these missions and move ahead.

## Protagonist

All players who choose the role of an protagonist take control of an actor to play as one of the protagonists in the storyline. Their job is to grow stronger and strive to complete the missions provided to them by the campaigner.

## Actor

An actor is a being that exist within the game. This can be a player's character, a monster, a merchant in the market, a random cow in a grassy field, or a robot on some spaceship on the other side of the galaxy. All of these entities are considered actors within the game.

# Board Layout

The layout of the cards on the board is an important detail to consider when playing the game. The position of these cards are used to express the current state of the game, the environment setting, the current actions that each player or NPC is preforming, and much more. The layout of the board is different for the player and the campaigner.

## Player's Layout

![Player Layout Diagram](images/TAP%20player%20zones.png)

The player's layout has two major regions. The **Field** and the **Player Reference**. The field consists of individual cards that make up the current condition and move set for the player. These are where cards are placed that are used for preforming actions and showing off turn-critical information quickly and easily. Meanwhile, the Player Reference region is used for storing the long term information about the character. Things that don't change very often or information that doesn't need to be present in each turn.

The player layout has a quite large Field region due to how many cards need to be considered for each action every turn. In contrast, the player has a fairly modest sized Reference region as most of the information that is backlogged can easily be stored in decks or bags as needed.

### Field

* **Active Skill Slots:** These card slots are where the player can place down active skill cards each turn. Players can place up to 6 active skill cards in a single turn. The cards can be placed anywhere within these 6 given slots. See [Active Skills](#active-skills) for more information. If the player is using an item alongside (or instead of) a skill, the item card is also placed here in an active skill slot.

* **Passive Skill Slots:** These card slots are where the player can place down passive skills that they what to activate. Cards that are placed in these slots will remain on the field until the player decides to remove them for any reason or the game requires them to be removed as needed. (I.e. no longer has enough stamina). See [Passive Skills](#passive-skills) for more information.

* **Left/Right Handed + Item/Weapon Slots:** The player is allowed to have up to two items or weapons equipped at any time, unless otherwise stated by the game. These items or weapons may be equipped in these card slots. A common example of this might be equipping a sword in one hand and a shield in the other. If an item or weapon being held requires two hands to hold, it must be placed in the center of the two card slots and prevent any other item or weapon from being held until it is unequipped. See [Held Equipment](#held-equipment) for more information. Certain cards or custom game rules may add certain benefits for which hand is holding which item. (I.e. extra accuracy when using primary hand instead of offhand.)

* **Equipment Slots:** Equipment that is being worn is placed in these slots. Each slot indicates a specific location in which the equipment is being worn. Wearing a hat, for example, would go in the head slot. Any equipment that is not one of the five primary locations is considered an accessory and is placed in the accessory slot. In the base rules of the game, only one item can be equipped in each of these slots. See [Worn Equipment](#worn-equipment) for more information.

* **Status Effect Slots:** If the player has any activate status effects, they are placed in these six slots. This includes both positive and negative status effects as needed. These status effects will remain on the field in these given slots until they are cleared for any reason. See [Status Effects](#status-effects) for more information.

* **Physical Struggle Slots:** If the player has any physical struggles, they can be placed in any of these six provided slots. See [Physical Struggles](#physical-struggles) for more information.

* **Mental Struggle Slots:** If the player has any mental struggles, they can be placed in any of these six provided slots. See [Mental Struggles](#mental-struggles) for more information.

* **Attribute Slots:** Each of the player's 6 attributes are placed in the six corresponding attribute slots. These display the player's base attribute values to use when preforming modifier calculations and skill rolls. See [Attributes](#attributes) for more information.

### Player Reference

* **Experience Slot:** See [Experience](#experience) for more information. // TODO

* **Money Slot:** See [Currency](#currency) for more information. // TODO

* **Skills Slot:** See [Skills](#skills) for more information. // TODO

* **Inventory Slot:** See [Inventory](#inventory) for more information. // TODO

* **Allies Slot:** See [Allies](#allies) for more information. // TODO

* **Friends Slot:** See [Friends](#friends) for more information. // TODO

* **Enemies Slot:** See [Enemies](#enemies) for more information. // TODO

* **Adversaries Slot:** See [Adversaries](#adversaries) for more information. // TODO

* **Tragic Backstory Slot:** See [Character Backstory](#character-backstory) for more information. // TODO

* **Quirk Slots Slot:** See [Quirks](#quirks) for more information. // TODO

## Campaigner

![Campaigner Layout Diagram](images/TAP%20campaigner%20zones.png)

// TODO

# Skills

// TODO

## Active Skills

// TODO

## Passive Skills

// TODO

## Requirements

Some skill cards, both passive and active skills, have requirements that must be met in order for them to be placed on the field. These skill requirements are listed on the card. These requirements may target the user, the ally party, the enemy, the enemy party, or the entire field. Some common skill requirements are as follows:

* Requires Passive Skill (Or skill category)
  * Requires that a specific passive skill, is present on the target.
  * Example: Cannot use backstab unless using the stealth skill.
* Requires Active Skill (Or skill category)
  * Requires that the user players this card alongside another active skill, or in direct response to an active skill.
  * Example: The bargaining skill cannot be used unless someone is using the trade skill.
* Requires Item (Or item category)
  * Requires the item to be played alongside this skill card in a combo, or in direct response to the enemy using the specified item.
  * Example: Bind Opponent cannot be used without a rope-like item.
* Requires Equipment (Or equipment category)
  * Requires that a specific piece of equipment be worn or held by the target.
  * Example: Stab cannot be used unless holding a sharp object.
* Requires Attribute Range
  * Requires that the base attribute value for the specified attribute 
  * Example: Charisma must be above 10 to use Warm Smile.
* Requires Environment State
  * Requires a certain property of the environment to be present.
  * Example: Shadow Stealth requires a dark environment.

# Items

// TODO

## Inventory

// TODO

# Equipment

// TODO

## Held Equipment

// TODO

## Worn Equipment

// TODO

# Status Effects

// TODO

# Character Struggles

// TODO

## Physical Struggles

// TODO

## Mental Struggles

// TODO

# Attributes

// TODO

# Leveling

// TODO

## Experience

// TODO

# Currency

// TODO

# Relationships

// TODO

## Allies

// TODO

## Friends

// TODO

## Enemies

// TODO

## Adversaries

// TODO

# Quirks

// TODO

# Character Backstory

// TODO