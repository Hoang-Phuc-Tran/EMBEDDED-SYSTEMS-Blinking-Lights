
https://github.com/Hoang-Phuc-Tran/EMBEDDED-SYSTEMS-Blinking-Lights/assets/120700092/ed8a089c-a5dc-4bb3-8ed2-e37deb1702f3

# STM32 LED Game Project

Welcome to the STM32 LED Game Project! In this repository, we delve into the world of interactive LED manipulation using the STM32 board.

## Quick Overview

This project presents an engaging game that brings together the lights and buttons on the STM32 board. The goal is simple yet exciting: you will implement a game where the lights blink in a pattern you specify until you press the button. Your success is determined by whether you manage to press the button when the target light is on. 

## How It Works

- **Gameplay**: Use the command `ptGame delay pattern target` . The lights will blink in the specified pattern repeatedly until you press the button. If you press the button when the target light is on, you win; otherwise, the game continues.
- **Winning**: If you win, all the lights blink twice simultaneously.
- **Losing**: If you lose, only the target light remains on until the next game is played.

## Example

For instance, consider the command: ptGame 500 43567011 5

This runs the game with a delay of 500ms between lights and cycles the lights in the pattern 4, 3, 5, 6, 7, 0, 1, 1. Winning is achieved by pressing the button when the light numbered 5 is on.
