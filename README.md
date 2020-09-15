# Personal project --- A card game

## Why I make this game?


This game is inspired by the famous rogue-like card game *Slay the Spire*. I really like this *Slay the Spire*, so I make this small game for everyone who likes card games like me.

## Who may play it?

Every one who like to play card games are welcomed to play this game, and I appreciate your suggestions for making this game better.


## How to play this game?

In this game you will first select a character (rogue, warrior, mage etc) and the difficulty, then you will need to create your own desk. After creating desk, a random boss will be generated with Hp, and you will fight turn by turn.

The player always goes first. Each turn you will draw 5 cards from your desk and refill the energy. Your cards may cost combat resources(such like energy, mp for the mage, combo point for the rogue, fury for the warrior) but will help you to kill the boss.

In the boss's turn, it will use different skills, sometimes they may  attack, sometimes they may heal themselves(we make it constantly hit you for now). The aim of you is to make the boss's hp to 0.

Enjoy the game!

## Some features are still on the way!

Currently, the cards will only cost energy, we will make them cost mp,combat point and rage in the future.

We are working on the buffs and relic so that cards may have different effects and player will get relic after fight! 

We are also working on the shopping system so that player may use money for buying cards in shop!

## User stories phase 1
As a user, I want to be able to select the character.

As a user, I want to be able to add cards to my desk.

As a user, I want to be able to use cards during the battle.

As a user, I want to be able to view boss's info.

As a user, I want to be able to view my info.

As a user, I want to be able to view my desk.

As a user, I want to be able to end my turn.

## User stories phase 2 

As a user, I want to be able to save my desk before the battle

As a user, I want to be able to optionally load my desk from a file before card selection

## Instructions for Grader phase3 
You can generate the first required event by select different number of bosses.

You can generate the second required event by making your desk with multiple cards.

You can trigger my audio component by playing a card successfully during the battle

You can save the desk by clicking the "I want to save!" after card selection

You can reload the desk by clicking the load button 

## Phase 4: Task 2

In my code I have type hierarchy. The Boss,Mage,Warrior and Rogue class extend Character, and they override the update() method which updates the description.

## Phase 4: Task 3

Remove getDescription method in subclass and add it into super class "Character"

Rewrite the update method which will allow all subclass's descriptions have the same format.
