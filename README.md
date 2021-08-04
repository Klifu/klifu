<p align="center">
<img src="https://github.com/Klifu/klifu/blob/main/assets/banner-dark.png" alt="banner" width="500" />

<p align="center">
Klifu is an online pokemon turn based game influenced by pokemongo and pokemon red. Klifu aims to build the core game logic which could be used to create any client.
</p>
</p>

> Under Development 🔨

## Table of Contents

- [Overview](#overview)
- [List of Official Game Clients](#list-of-official-game-clients)
	- [CLI](#cli)
		- [Installation](#installation)
		- [Usage](#usage)
- [Communication](#communication)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Maintainers](#maintainers)

## Overview
Klifu is a pokemon game build by the community as they like, that means the game mechanics is completely different from any other pokemon game you have played, taking inspiration from `pokemon red` and `pokemongo`. 


## List of Official Game Clients
As of now we are only working on our CLI client, but we have plans for more, stay tuned. 

|Client Name|Description|Github Repo|
|-----------|-----------|-----------|
|[`CLI`](#cli)|klifu cli client that run in your cli|[here](https://github.com/klifu/cli)|

### CLI
Klifu cli client, just install and play the game right from your CLI. 

#### Installation 
To run `klifu` in your cli, ensure that you have Node.js >= v10. [Install NodeJS via package manager](https://nodejs.org/en/download/package-manager/)

```
$ npm install -g @klifu/cli
```
This installs `klifu` globally on your system allowing you to run it from anywhere.  If you want to install it locally, Just remove the `-g` flag.

#### Usage
To get started run `klifu --help` and follow the help given to understand how to play. 

You can also check [the cli repo](https://github.com/klifu/cli) for detailed description of the game. 


## Communication 
We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have any questions.

- [Discuss, the official Klifu message board](https://github.com/Klifu/klifu/discussions)
- [Klifu FAQ](https://github.com/Klifu/klifu/discussions/categories/q-a)


If chat is more your speed, you can join our [Klifu Discord](https://discord.gg/ntyrnfAXqr)


## Project Structure
Klifu is very modular, the comlete game is divided into 
- [`@klifu/core`](https://github.com/klifu/core) the main game logic.
- [`@klifu/api`](https://github.com/klifu/api) the datastore api that stores our static game data. 
- [`@klifu/cli`](https://github.com/klifu/cli) the cli client for playing the game. 

and we have this repo for managing the project. 

## Contributing 
👍🎉 First off, thanks for taking the time to contribute! 🎉

- Before you jump off and start contributing I will encourage you to read our [CONTRIBUTING.md](./CONTRIBUTING.md) file. 

- Feel free to reach out to the [maintainers](#maintainers), if you have any query. 

- Every packages has instructions about setting up your local development enviornment, just head to a repo and follow the instructions. 

- We are managing our project using [zenhub](https://www.zenhub.com/), download the [zenhub extension](https://www.zenhub.com/extension) to check and actively take part in the development process. 


## Maintainers

| Souvik     | 0Verlord-41 |
| ----------- | ----------- |
| <img src="https://avatars3.githubusercontent.com/u/41781438?s=460&u=00c443438c07ac2ffaef48bef755067522abc4bc&v=4" height="100" width="100">     | <img src="https://avatars.githubusercontent.com/u/42108740?v=4" height="100" width="100">       |
| [souvikns](https://github.com/souvikns)   | [0Verlord-41](https://github.com/0Verlord-41)       |

### Where can you reach us?
- Just head over to [discussion](https://github.com/Klifu/klifu/discussions) and create a new discusion taging us. 
- Or ping us in discord, *same name as github username* 😉
