# Battleship
battleship game with c++
# Battleship Game

This is a C++ implementation of the classic Battleship game, created as a project for the Computer Science and Programming course (Term 14011). The project is designed to showcase your strategic thinking and coding skills.

## Table of Contents
- [Introduction](#introduction)
- [General Structure](#general-structure)
- [Game Rules](#game-rules)
- [Scoring](#scoring)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The objective of this project is to create a strategic battleship game where players compete to sink each other's ships. The game is played on an n x n grid, and each player starts with n ships. The game continues until one player loses all their ships.

## General Structure

- The game board is an n x n grid, with a border separating the player's area from the enemy's area.
- Players take turns to input coordinates to shoot at the enemy's grid.
- The game ends when one player has sunk all of the opponent's ships.
- Scoring is calculated based on a formula that considers the number of shots and remaining enemy ships.

## Game Rules

- Each player has n ships placed randomly in their area of the grid.
- Players take turns firing shots at the enemy's grid, trying to hit and sink the enemy's ships.
- Players can only shoot at coordinates along the border of the enemy's area.
- Hits are represented by '1' on the game board; misses are represented by '0'.
- Multiple shots at the same coordinates are not allowed.

## Scoring

Player scores are calculated using the following formula:

