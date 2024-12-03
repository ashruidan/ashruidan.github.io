+++
date = '2024-12-03T09:44:56+01:00'
title = 'Day 03 - The Suicide Rule'
+++

## Introduction

The **Suicide Rule** prevents self-capturing moves and has implications for **life and death** on the board.

## Self capture as illegal Moves

In Go, a player cannot place a stone on an empty intersection completely surrounded by their opponent's stones. Such a move would leave the stone with no liberties and is considered illegal.

![day03_illegal](/images/day03_illegal.png)

However, there is an exception: if the surrounding opponent's stones are also completely surrounded by your stones, the move is allowed. This is because, in capturing the opponent's stones, your stone regains its liberties.

![day03_legal](/images/day03_legal.png)

For example, in this diagram, placing a stone on the empty intersection is legal because it captures the surrounding stones:

![day03_capture](/images/day03_capture.png)

## The Concept of Eye

An **eye** is an empty intersection surrounded by a group of stones. The simplest form of an eye is the single point eye.

![day03_eye](/images/day03_eye.png)

To capture a group with an eye, you first need to remove all its external liberties and then fill the eye. However, creating one eye already makes a group much harder to kill.

What happens if the group has **two eyes** ?

![day03_twoeyes](/images/day03_twoeyes.png)

A group with two eyes is unconditionally alive because your opponent cannot fill both eyes in one move. This situation falls back into the Suicide Rule, making it impossible to fill both eyes.

Thus, **two eyes guarantee life** for your group.

## The False Eye

A **false eye** looks like an eye but can be filled by the opponent because it doesn’t have complete support from his stones.

![day03_falseeye](/images/day03_falseeye.png)

In this diagram, the marked point appears to be an eye, but it’s a **false eye**. If the opponent plays there, the entire group is at risk of being captured. Recognizing false eyes is a key skill for understanding life and death.

## Tsumego

Let’s put your knowledge to the test with some basic **tsumego** (life and death puzzles). These problems are designed to help you practice creating two eyes for your groups.

You can try this collection of puzzles on OGS :  
[OGS Problems](https://online-go.com/learn-to-play-go/defend)
## Proverb of the Day

> "Only enclosed groups can be killed"

A group is only at risk of capture if it is fully surrounded. An enclosed group must rely on creating two true eyes to ensure its survival. 
