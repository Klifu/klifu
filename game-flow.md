# Klifu Game Flow 

> As of now klifu supports only **gen1**.

## Introduction 
This document is the complete game flow of klifu. We will talk about all the rules and the game logic that is being used to build the game. Building klifu, we have taken inspiration from pokemongo and pokemon red, the two seperate but extremely popular. You will find a lot of similarities in the game. The complete game logic is built on typescript and you can check it [here](https://github.com/klifu/core). 


> Before diving into the game flow, I would like to clarify that the [core](https://github.com/klifu/core) library only deals with the game logic and not with storing game progress. 



## Table Of Contents
- [Getting Started](#getting-started)
- [Catching Pokemons](#catching-pokemons)
	- [Encountering wild pokemons](#encountering-wild-pokemons)

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


