# What the Walls Remember

**What the Walls Remember** is a psychological horror game developed in Unreal Engine 5.  
The game explores adaptive horror by allowing the house to react to player behavior, using systems that track movement patterns, hesitation, backtracking, and tension.

This project was developed as a team project, with my primary contributions focused on gameplay systems, player-behavior tracking, adaptive horror mechanics, and supporting game systems.

---

## About the Game

*What the Walls Remember* follows Eddie Carter, a local news journalist desperate to uncover a story that could define his career.

His investigation leads him to an unassuming suburban house with a disturbing history. Multiple families have lived within its walls, and every one of them has died violently. Despite the pattern, no suspect has ever been identified, and the cases have long gone cold.

After discovering that the deaths are far too consistent to be coincidence, Eddie enters the abandoned home searching for answers. Inside, he uncovers clues suggesting that the house itself may be connected to the murders.

As reality begins to fracture, Eddie discovers that the home remembers everything — and it may not want its secrets uncovered.

---

## Gameplay

The first level introduces the player to the house and establishes the psychological-horror mechanics used throughout the game.

Rather than relying on combat, the level focuses on:

- Environmental exploration
- Investigating clues
- Psychological horror events
- Player-driven pacing
- Dynamic tension
- Environmental storytelling
- Adaptive reactions from the house

The player's initial objective is simple:

> **Look for anything that might explain what happened here.**

As the player explores, the game begins collecting information about how they move through and interact with the environment. This behavior can then influence how the house responds.

---

## Adaptive Horror System

One of the primary technical goals of the project was creating a horror experience that could react to how the player behaves rather than relying entirely on predetermined scares.

### House Memory Manager

The **House Memory Manager** tracks player behavior throughout the level.

Examples of tracked behavior include:

- Movement speed
- Hesitation
- Backtracking
- Exploration patterns

These measurements can be used to build a behavioral profile of the player and provide information to other gameplay systems.

### AI Director

The **AI Director** manages the pacing of horror events.

Instead of constantly triggering scares, the system considers factors such as:

- Current tension
- Cooldown periods
- Player behavior
- Previous events

This allows the game to create periods of tension and release rather than overwhelming the player with continuous scripted events.

The long-term goal is for different players to experience variations in how the house attempts to create tension.

---

## My Contributions

My primary responsibilities on the project included:

- House Memory Manager
- Player behavior tracking
- Player behavior classification
- AI Director
- Tension and cooldown systems
- Entity behavior systems
- Debug visualization tools
- Main menu and pause menu
- Player interaction prompts
- Audio integration
- Key and locked-door interactions
- Environmental horror events
- End-of-level trigger and game flow

I also contributed to debugging, integration, gameplay testing, and preparing packaged builds of the game.

---

## Example Horror Events

The level contains environmental events designed to create tension without requiring combat.

Examples include:

- Lighting and flickering events
- Shadow appearances
- Object/doll events
- Audio cues
- Environmental changes
- Triggered entity behavior

These events can be coordinated with the game's tension-management systems to control pacing.

---

## First Level

The first level establishes the visual tone of the game and teaches the player how to "read" the house.

The level gradually introduces the idea that the environment may be responding to the player's behavior while avoiding direct explanations of the underlying systems.

<img width="1289" height="707" alt="What the Walls Remember - First Level" src="https://github.com/user-attachments/assets/11c3ee82-3aa8-4663-8f2d-cc4938196f13" />

---

## Suspenseful Moments

Environmental events and lighting are used to build tension as the player explores the house.

<img width="784" height="611" alt="What the Walls Remember - Suspenseful Moment" src="https://github.com/user-attachments/assets/8f790527-279b-4e91-a540-2566e7eb19d9" />

---

## Technology

- **Engine:** Unreal Engine 5
- **Game Systems:** Unreal Engine Blueprints
- **Version Control:** Git / GitHub
- **Development:** Team-based game development

---

## Software Engineering Concepts

This project provided experience with several software engineering and game-development concepts, including:

- Event-driven gameplay systems
- State and behavior tracking
- Modular gameplay architecture
- AI/game-director systems
- Debugging and visualization tools
- Gameplay event coordination
- Team-based development
- Version control
- Iterative testing and refinement

---

## Project Status

The project has progressed through Alpha and Beta lifecycles to this point.

Core gameplay systems, environmental events, player interaction systems, and the adaptive horror framework have been implemented.

---

## Team Project

*What the Walls Remember* was developed collaboratively as a team project.

This repository is maintained as part of my software engineering portfolio and highlights the systems and features that I contributed to during development.
