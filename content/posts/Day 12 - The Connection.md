+++
date = '2024-12-12T18:20:37+01:00'
draft = false
title = 'Day 12 - The Connection'
+++
## Introduction

In Go, the concepts of **connection** and **cutting** lie at the heart of the game. Connecting your stones strengthens your groups, ensuring they survive and work together. Cutting, on the other hand, aims to divide your opponent’s groups, making them weaker and creating opportunities to attack.

## **Connections**

Connecting stones allows you to build strong groups and secure their survival. A well-connected group is harder to attack, provides stability, and can exert more influence on the board.

### **1. Solid Connection**

A **solid connection** ensures absolute strength between stones, such as connecting two stones with a tobi when there’s no cutting point.

![day12_solidconnect](/images/day12_solidconnect.png)

Playing the triangle mark, will make the two stones of a tobi connect solidly.

### **2. Hanging Connection**

A **hanging connection** has multiple point of connection to link the stones. It’s slightly less solid than a direct connection.

![day12_hangingconnect](/images/day12_hangingconnect.png)

A kosumi can be reinforced if attacked by opponent in one of the triangle mark by playing in the other triangle mark.

### **3. Loose Connection**

A **loose connection** seems connected because no opponent stone is played between them. While it provides speed and influence, it’s vulnerable to cutting unless reinforced.

![day12_looseconnect](/images/day12_looseconnect.png)

Here, a three-space jump offers more mobility but requires additional moves to make the connection less loose or you would be exchanging something to be able to stay connected.

## **Cuts**

Cutting is a powerful way to weaken your opponent by dividing their groups. A well-placed cut forces your opponent to defend multiple weak groups, creating opportunities to attack and profit.

### **Principles of Cutting**

1. **Make the Cutting Stone Live**: A cutting stone is only effective if it survives. Ensure your cutting move threatens both sides, making it hard for your opponent to handle.
2. **Exploit Weakness**: Identify points where your opponent’s groups are loosely connected or vulnerable.

### **1. Solid Cut**

A **solid cut** cleanly separates your opponent’s stones. This creates two disconnected groups and forces your opponent to respond.

![day12_solidcut](/images/day12_solidcut.png)

Here, Black tobi got cut by White and now Black has to take into account the lives of the two groups but White is only with one group and can choose which side to attack.

### **2. Cross-Cut**

A **cross-cut** places your stone between two opponent stones, dividing both your opponent’s group and your own. This often leads to a complex fight where the state of the board becomes important.

![day12_crosscut](/images/day12_crosscut.png)

## Proverb of the Day

> **"Capture the cutting stones."**

This proverb emphasizes the importance of eliminating your opponent’s cutting stones. Cutting stones are dangerous because they divide your groups and threaten your stability. If you can capture them, you remove the threat and strengthen your position.
