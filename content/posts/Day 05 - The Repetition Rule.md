+++
date = '2024-12-05T12:20:37+01:00'
title = 'Day 05 - The Repetition Rule'
+++

## Introduction  

In a typical game of Go, every move leads to a new and unique position. However, there is a special scenario where the game could fall into an endless cycle of repeated moves. To prevent this, the **Repetition Rule** ensures that no position can be repeated.  

## Preventing Infinite Loops  

In certain situations, such as the one shown below, a player can capture a stone, only for the opponent to recapture it on the next turn, creating a loop. This would result in an endless game. 

In Go, a **ko** refers to a situation where two players could alternately capture and recapture a single stone, repeatedly returning the board to the same position and could continue indefinitely. The **Repetition Rule** resolves this by prohibiting immediate recapture.

![day05_ko](/images/day05_ko.png)  

Instead, the player must play elsewhere first, giving their opponent the chance to protect their stone in the ko.  

However, this also means that Black may protect the captured stone while White is playing elsewhere. This introduces a strategic layer to ko situations.  

## Ko Threats

In a ko fight, players often make **ko threats**—moves elsewhere on the board that force the opponent to respond, allowing them to recapture the ko. These threats, also called **aji** in Japanese, can help to gain an advantage.  

![day05_kothreat](/images/day05_kothreat.png)

In this diagram, Black starts a ko by capturing a White stone with move 1. White then responds with move 2, threatening to capture a large group of Black stones.

Now the situation depends on Black's choice:

- If Black defends the threatened group by playing at A, White will recapture the stone in the ko. Black can then play elsewhere, allowing White to connect their stone and resolve the ko.
- If Black ignores the threat and finishes the ko by capturing stones with move B, White can play at A, killing the large Black group.

This sequence demonstrates the strategic balance in ko fights, where both players must weigh the value of the ko against other threats on the board. 

When the balance in a ko is tipped, it can lead to a **picnic ko**—a situation where winning the ko brings significant damage to the opponent, while losing it results in only a minor loss for you.
## Practice with Ko  

To continue honing your skills, revisit the **101weiqi** website introduced in the previous chapter : [101weiqi](www.101weiqi.com).

## Proverb of the Day  

> "A ko is won in preparation."

This proverb reminds us that the outcome of a ko fight often depends on the groundwork laid before it begins. Without threats, even a promising ko can quickly turn into a losing battle.

