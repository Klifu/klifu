# Klifu Game Flow 
![](https://img.shields.io/badge/Under-Development-yellow)

> As of now klifu supports only **gen1**.

## Introduction 
This document is the complete game flow of klifu. We will talk about all the rules and the game logic that is being used to build the game. Building klifu, we have taken inspiration from pokemongo and pokemon red, the two seperate but extremely popular. You will find a lot of similarities in the game. The complete game logic is built on typescript and you can check it [here](https://github.com/klifu/core). 


> Before diving into the game flow, I would like to clarify that the [core](https://github.com/klifu/core) library only deals with the game logic and not with storing game progress. 



## Table Of Contents
- [Getting Started](#getting-started)
- [Catching Pokemons](#catching-pokemons)
	- [Encountering wild pokemons](#encountering-wild-pokemons)
	- [How to catch a wild pokemon?](#how-to-catch-a-wild-pokemon)
- [Battling pokemons](#battling-pokemons)
	- [Catch Battle Mode](#catch-battle-mode)
	- [NPC Battle Mode](#npc-battle-mode)
	- [PVP Battle Mode](#pvp-battle-mode)
- [Pokemon Stats](#pokemon-stats)

## Getting Started
Just like any other pokemon game, you start klifu by choosing your starter pokemon. You get a choice between `Bulbasaur`, `Charmander`, `Squirtle`. Your starter pokemon is very crucial as you need it to catch new wild pokemons. 

## Catching Pokemons 
To catch pokemon, we took some inspiration from pokemongo. In more tradiational turn based pokemon game just like pokemon red you can only catch rare pokemons when you clear levels or earn badges. But in **klifu** you can catch legendary pokemon even if you are just starting the game. Encountering new pokemons is just a matter of chance. 

### Encountering Wild Pokemons
In **klifu** encountering wild pokemons is like pulling a lucky draw. The pokemons in are divided into the following rarities. 

|rarity|Symbol|Chance %|
|------|------|--------|
|common|**C**|`60%`|
|rare|**R**|`20%`|
|super rare| **SR**| `12%`|
|ultra rare| **UR**| `6%` |
|legendary| **L** | `2%` |

So you do have a chance to encounter a lengandary pokemon early in game, but it is very less likely. 

### How to catch a wild pokemon?
You catch a wild pokemon by droping it's health and then throwing a pokeball to catch it. Low level pokemons are so weak that you dont even need to fight it for catching. If while fighting the wild pokemon faints, you dont get to catch it, so be carefull while attacking. 



## Battling Pokemons 
In klifu there are a three modes of battle which will occur,

|Battle Mode | Description|
|------------|------------|
|Catch Battle|You battle a wild pokemon to drop it's hp to eventualy capture it.|
|NPC Battle  |You battle against a NPC bot. Mostly gym battles|
|PVP Battle  |You battle another player over internet|

### Catch Battle Mode 
This is a battle mode where you the user play against a wild pokemon in order to catch it. 

#### Rules 
- You can have atmost 6 pokemons.
- Your opponent is only one pokemon. 
- Battle ends when any of these situations occur
	- The wild pokemon faints
	- Your all 6 pokemons faints
	- You catch the wild pokemon
- If the wild pokemon faints then you dont get to catch it. 

### NPC Battle 
This is a battle mode where you the user play against NPC bot for badges. 

#### Rules 
- You can have atmost 6 pokemons. 
- Our opponent has predefined pokemons. 
- Battle ends when any of these situations occur 
	- All of your pokemon faints.
	- All of the NPC's pokemons faints. 

### PVP Battle
This is a battle where you can play with other players over internet. 

> This feature is planed for the future. 

#### Rules 
- You must have 6 pokemons. 
- Your opponent has 6 pokemons. 
- Battle ends when any of these situations occur
	- All of your pokemon faints. 
	- All of your opponents pokemon faints.

---

## Pokemon Stats
