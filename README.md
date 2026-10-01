# Elemains: Tales of Altos

### Scratch Demo — Alpha v6.0

**Elemains** (EL-eh-mains) is a creature-collecting RPG that I designed, programmed, illustrated, wrote and scored on my own. This repository contains the complete source of the playable Scratch demo, **Alpha v6.0**.


## Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Inspirations](#inspirations)
- [The demo](#the-demo)
- [Features](#features)
- [Original soundtrack](#original-soundtrack)
- [Technical overview](#technical-overview)
- [How to play](#how-to-play)
- [What this project gave me](#what-this-project-gave-me)
- [In development](#in-development)

---

## Overview

In the region of Altos, creatures called **Elemains** live everywhere, but only a rare few people — **Mages** — can bond with them and channel their power in battle. The player is a young Mage from the snowy mountain town of Nova Town. When a group of thieves breaks into the town library and steals years of research on Elemains, the player sets out to rebuild that research by finding and catching Elemains across the region, and to track down the people who took it.

| | |
|---|---|
| **Genre** | Creature-collecting RPG |
| **Built in** | Scratch 3.0 |
| **Made by** | Dream Arishtene: design, programming, art, animation, writing, music and sound |
| **Timeline** | November 2021 – January 2026 · started at 14, released after four years |
| **Playable creatures** | 35 Elemains, each with stats, types, moves and evolutions |
| **Moves** | 104, across 14 types |
| **Project size** | 61 sprites · ~21,800 code blocks · 907 costumes · 267 sounds · 250 variables · 106 data lists · 222 broadcast messages |

---

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/2a8d23bf-12e9-4cac-98c3-1e3bada81421" width="49%" alt="Elemains screenshot 1" />
  <img src="https://github.com/user-attachments/assets/5cf234c1-ed86-45bb-860e-75a45260615b" width="49%" alt="Elemains screenshot 2" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/9a3f0a10-19c1-4abb-8c3b-4b857be03362" width="49%" alt="Elemains screenshot 3" />
  <img src="https://github.com/user-attachments/assets/cc32ca48-9929-4c62-bf3b-c039e21632b3" width="49%" alt="Elemains screenshot 4" />
</p>

---

## Inspirations

Elemains comes from a lifetime of playing Nintendo games, and each of my biggest influences shaped a different part of it.

- **Pokémon** — the foundation. Collecting creatures, building a team, turn-based battles with a type chart, and a journey across a region told through its towns and routes. Pokémon taught me what makes that loop so hard to put down, and the challenge I set for myself was to build my own version of it from nothing.
- **The Legend of Zelda** — the sense that the world is hiding something. Secret areas off the main path, tools that change how you explore, and the reward of looking somewhere you weren't told to look. That thinking became the demo's hidden grotto and its toolbox of items.
- **Animal Crossing** — a world that runs on its own clock. The real-time day/night cycle, the farm, and the quiet, lived-in feel of Nova Town all come from wanting Altos to feel like a place you live in, not just a place you pass through.
- **Nintendo's music** — studying these soundtracks closely changed how I think about games (more in [Original soundtrack](https://youtube.com/playlist?list=PLpAaGWbGhL5fKDwRmSsaYEXa1QUwzfNXr&si=oNhCAfhGIXfykpBj)).

---

## The demo

Alpha v6.0 is the opening chapter of the game, roughly from leaving home to earning your first badge.

**The journey through the demo:**

1. **Nova Town.** Choose your character, then meet Hilda, the town librarian, and Christy, the girl she raised. Hilda's research has just been stolen by thieves in strange futuristic clothing.
2. **Hilda's library.** Choose a partner Elemain — **Shruddle**, **Obsile** or **Akello** — and receive your Mage Kit.
3. **Trail 1.** A snowy downhill trail with your first wild encounters and a guided tutorial battle.
4. **Port Northa.** Visit the **Ele-Co center** to heal and store your Elemains, and pick up a lead: the thieves may have fled by boat.
5. **Trail 2 and Ranchem Village.** Head inland to a rustic farming village to get a boat pass from Christy's family.
6. **The Ranchem Arena.** Enter a tournament against four Mages for the right to face Nash, the village's Ace Mage, and earn your first **King's Badge**.
7. **Setting sail.** Earn the boat pass and head out toward the Napora District, where the demo ends.

**Wild Elemains in the demo:**

| Area | Encounters |
|---|---|
| Trail 1 | Frosbi (40%), Rollent (30%), Tyder (20%), Prispup (10%) |
| Trail 2 | Sleepig (38%), Frosbi (38%), Fizzle (20%), Coteep (3%, rare) |

There are also trainer battles, a hidden grotto, a secret achievement and more Elemains to find for players who explore.

---

## Features

### World and exploration
- Scrolling overworld with multiple connected areas, interiors and doors
- Real-time day/night clock
- Region map with locations that unlock as you discover them
- Hidden grotto and secret areas
- 30+ named NPCs with portrait dialogue, plus an objective tracker that guides the story
- Cutscenes, an animated title sequence and an 18-step tutorial
- Boat travel, with an animated sailing sequence

### Battle
- Turn-based battles with **Attack**, **Bag** and **Flee**
- Speed-based turn order
- A damage formula built on attack and defense stats, a same-type attack bonus and a full type-effectiveness chart
- 104 moves with power, stamina cost, stat buffs and debuffs, status effects and trapping effects
- Wild battles, trainer battles and a multi-round **arena tournament** with an announcer, a crowd and a final Ace Mage battle
- XP, leveling and evolution, including evolution by item
- Shiny Elemains

### Collection and progression
- Catching with three tiers of Cores, each with its own catch rate
- Six-Elemain party plus storage at the Ele-Co center
- In-game library that records every Elemain you discover
- Shop, healing items, Repels and two currencies
- Toolbox with a fishing rod, saddle, rock piercer and watering can
- Riding Elemains with a saddle
- Farm
- King's Badge award sequence
- Achievements for catching, discovering, exploring, shinies and a secret

### Options
- Male or female player character and a custom name
- **Nuzlocke mode**, an optional permadeath challenge
- **Save codes**: the entire game state is encoded into one copyable string and fully restored from it

---

## Original soundtrack

I composed the soundtrack for Elemains. Every major location and moment has its own theme, written to match the feeling of that place.

| Exploration | Battle | Story and events |
|---|---|---|
| Nova Town | Wild Encounter | Elemains Intro |
| Nova Library | Wild Battle | Trainer Meet |
| Trail 1 | Trainer Battle | Evolution |
| Trail 2 | Stadium Battle | Ele-Co Center |
| Ranchem Fields | Final Stadium Battle | Stadium Entrance |
| Ranchem Village | Fusion Battle | Stadium Results |
| Port Northa | | |
| Roko Docks | | |
| Hidden Grotto | | |

Writing this music meant studying the soundtracks of the games that inspired me, the way a student studies the masters: how each town gets a melody you'd recognize anywhere; how route music keeps you moving; how a battle theme builds tension in its first few seconds; and how one motif can return in different forms across a whole game. Hearing my own tracks play in the places I built is one of the most rewarding parts of this project.

> **Note:** Two tracks in the Alpha v6.0 project file — "Trainers Meet 2" from the *Pokémon Brick Bronze* soundtrack and "Jubilife City (Night)" from *Pokémon Diamond & Pearl* — are temporary placeholders. They are not my work and will be replaced with original compositions in an upcoming update.

---

## Technical overview

Scratch has no classes, no structured data types and no file storage. Building a full RPG inside those limits meant designing my own patterns:

- **A database built from parallel lists.** Every Elemain's stats, types, evolution data, EXP yield, default moves and description live in lists that share an index, like columns in a table. The 104-move database works the same way: name, type, power, stamina, buff, status, trap, chance and special effects.
- **Event-driven architecture.** 222 broadcast messages coordinate battles, cutscenes, menus, dialogue and area transitions across 61 sprites.
- **A global state machine.** Flags such as `Battling?`, `Menu?`, `cutscene?` and `transition?`, together with a story checkpoint variable, control what the game is allowed to do at any moment.
- **Weighted randomness.** Encounter tables, catch chances and status effects all use weighted random selection.
- **Clone-based instancing** for NPCs, interface elements, text and effects.
- **A custom text engine** that draws dialogue character by character with per-letter spacing and effects.
- **Serialization.** The save-code system flattens the party, storage, levels, items, progress and settings into a single string and rebuilds the game from it.
- **Vector art.** Every creature, character, environment and interface element is a hand-drawn SVG.

---

## How to play

1. Download the `.sb3` file from this repository's **Releases** page.
2. Go to [scratch.mit.edu](https://scratch.mit.edu), select **Create**, then **File → Load from your computer**, and open the file.
3. Click the green flag, then press **Space** to start.

**Controls:** arrow keys or WASD to move · Space to talk, interact and advance dialogue · mouse for menus and battles

> The project file is about 150 MB, which exceeds GitHub's 100 MB per-file limit, so it is distributed as a Release asset rather than committed to the repository.

---

## What this project gave me

The demo ends with a message to the player: *"Thanks for playing the game I've been dreaming of making since I was a kid."* That's the truest description of this project. Building it, then stepping back to study it critically and plan what it should become, has shaped how I think, how I build, and what I believe I'm capable of.

### Thinking in systems

A creature-collecting RPG is dozens of systems that depend on each other. Battles need stats, stats need a database, the database needs to be saved, saving needs the state of every other system, and the story decides when any of it can happen. Building all of that in Scratch, without the tools a professional language provides, made me understand *why* those tools exist. By the time I learned what classes, arrays of objects, enums and state machines were, I had already built the hard version myself, so I knew exactly what problem each one solved.

### Professional growth
- **Taking honest criticism:** I put years of work in front of a hard critique and used it to find what truly makes Elemains different, rather than defending what I had
- **Documentation:** turned ideas that only lived in my head into a full game design document, a style guide, a creature and move database, and a technical reference that someone else could work from
- **Planning in phases:** learned to finish a foundation before building on top of it
- **Persistence:** a project this size isn't finished in a weekend; Elemains taught me to keep coming back and keep raising the standard

### Where it has taken me

Everything I learned here has carried into my other work: writing C# in **Unity**, building real-world mobile apps for a family business client with **React Native, Expo and Firebase**, and working alongside AI coding tools by writing precise specifications, reviewing the code they produce, and testing every critical feature by hand on a real device.

### The biggest lesson

The gap between a project and a product isn't talent. It's structure, honesty about what isn't working yet, and the willingness to rebuild something you're proud of so it can become what it was meant to be. I built a full RPG in a tool designed for beginners. Now I'm building it again, and I understand why every piece is there.

---

## In development

Alpha v6.0 is the foundation, not the finish line. The full version of Elemains is in active development as a complete rebuild in **Unity**, designed **mobile-first**, with a larger region, a much bigger roster of Elemains and the rest of the story. More will be shared as it gets closer to release.

---

*Elemains: Tales of Altos, including its characters, creatures, artwork, music and story, is original work. Source is shared for portfolio and demonstration purposes only; no reuse, redistribution, or derivative works permitted. All rights reserved.*
