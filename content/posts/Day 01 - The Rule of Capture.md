+++
date = '2024-12-01T04:20:13+01:00'
title = 'Day 01 - The Rule of Capture'
+++

Welcome to the **Advent of Go**, a 25 chapters long guide where each day is built upon the concepts of the previous ones.

This guide will not delve into the history or variations of Go, instead it will help you acquire the necessary knowledge and skills to perceive the depth of this game.

## Introduction

At its core, Go is a two-player turn-based game where one player uses black stones and the other uses white. Black always plays first. On each turn, players can either place a stone on an empty intersection of the board or pass their turn. Once placed, a stone cannot be moved. However, stones can be removed through **capture**.

![day01_introduction](/images/day01_introduction.png)
## How to capture ?

To capture stones, you first need to understand **liberties**. Liberties are the empty intersections adjacent to a stone. When you place a stone on the board, the lines extending from it lead to these adjacent empty spaces—its liberties.

![day01_stone](/images/day01_stone.png)

If another stone, whether yours or your opponent's, occupies an adjacent intersection, the stone loses that liberty. Groups of connected stones share their liberties, creating a unified set of liberties for the entire group.

![day01_liberties](/images/day01_liberties.png)

A stone's number of liberties also depends on its position on the board: 
- **Corner**: A stone in the corner has only two liberties (two edges of the board block it).
- **Side**: A stone on the side of the board has three liberties (one direction blocked by the board's edge). 
- **Center**: A stone placed in the center of the board has four liberties.

![day01_positions](/images/day01_positions.png)

## What Is Atari ?

**Atari** is a Japanese term for a situation where a stone or group of stones has only one liberty left. This state means the stone or group is in immediate danger of being captured on the opponent's next turn.

![day01_ataris](/images/day01_ataris.png)

Understanding atari highlights why the center offers more freedom and flexibility for stones.

## Capturing Stones

Capturing occurs when you place a stone on the final liberty of an opponent's stone or group of stones in atari. Captured stones are removed from the board and become **prisoners**.

![day01_capture](/images/day01_capture_before.png)
![day01_capture](/images/day01_capture_after.png)
## Atari Go

Now that you understand capturing, it's time to apply the concept in a simplified version of the game called **Atari Go**. The objective is to be the first to capture any number of stones.

## Proverb of the Day

> Don't follow proverbs blindly.

Proverbs in Go provide valuable guidance but aren’t infallible. While they are often true, situations will arise where the right move goes against what the proverb teaches. Experience will teach you when to adapt.
