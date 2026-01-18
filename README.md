# Rise of the Humble Knight – QA Manual Testing

## Project Overview
Rise of the Humble Knight is a 2D pixel art RPG developed in Unity, featuring exploration, interactive dialogue systems, and turn-based combat.

- Engine: Unity 2D
- Platform: PC
- Game Type: 2D RPG / Turn-Based Combat
- Status: Playable Prototype

This project was developed as a technical challenge for an indie RPG studio and resulted in a fully playable solo prototype with multiple environments, narrative progression, and combat systems.

## Core Objective
The player progresses through multiple environments, interacts with NPCs, completes a mini-game, and engages in turn-based combat encounters to complete the narrative from start to finish.

## QA Scope
The QA activities for this project focus on:
- Turn-based combat flow and UI interactions
- Dialogue system interactions and branching
- Gameplay state transitions between scenes
- Player decision handling during combat
- User experience consistency during critical gameplay choices

## Known Risk Areas
- Combat UI interactions and action selection
- Irreversible player choices during turn-based combat
- Missing confirmation or rollback options
- Scene transitions after combat encounters

## Visual QA Preview

The following preview demonstrates a gameplay issue identified during manual testing.  
In this scenario, selecting a healing action during turn-based combat cannot be reverted, preventing the player from choosing a different action and negatively impacting combat flow.

![Combat action cannot be reverted](Evidence/bug_combat_action_no_rollback.gif)

> Full reproduction steps, severity, and complete video evidence are documented in `Bug-Reports.md`.

## Test Artifacts
- 📄 [Manual Test Cases](Test-Cases.md)
- 🐞 [Bug Reports with Evidence](Bug-Reports.md)
