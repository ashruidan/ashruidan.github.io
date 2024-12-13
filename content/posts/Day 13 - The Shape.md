+++
date = '2024-12-13T17:13:39+01:00'
draft = false
title = 'Day 13 - The Shape'
+++

## **Introduction**

In Go, shapes refer to the arrangement of stones on the board. A good shape efficiently connects stones, maximizes liberties, and prepares for future moves. A bad shape, on the other hand, is inefficient, easy to cut, or lacks flexibility.
## **Good Shapes**  

### **1. The Bamboo Joint**

![day13_bamboo](/images/day13_bamboo.png)

The bamboo joint consists of two diagonal connections. It is uncuttable with enough liberties and provides a strong connection between stones.

### **2. The Tiger’s Mouth**

![day13_tigermouth](/images/day13_tigermouth.png)

The tiger's mouth forms when three stones protect a central point, mostly an important cutting point.

### **3. Table Shape**

![day13_tableshape](/images/day13_tableshape.png)

A four-stone formation with a central point that ensures connection and liberties.  

### **4. Dog Face**

![day13_dogface](/images/day13_dogface.png)

A three-stone formation with a central point that serves as a foundation for creating other shapes, such as the table shape.

## **Bad Shapes**  

Bad shapes waste stones or create weaknesses that can be exploited. Here are some to avoid:  

### **1. Empty Triangle**  

![day13_emptytriangle](/images/day13_emptytriangle.png)

An inefficient shape that uses three stones to connect two points, wasting a move when we compare with a kosumi. The empty triangle got 7 liberties for three stones and the string of three stones got 8 liberties and gaining 1 liberty from a two stones string, making it an inefficient and slow third move. 
Not to be confused with the full triangle, where we connect one side of a kosumi while being attacked in the opposite side (upper-right shape). 

## **More about shapes**

A good youtube video to see about more shapes : [Dsaun Shape Lecture](https://www.youtube.com/watch?v=JKBh8FGK9bU)

## **Proverb of the Day**  

> "A Ponnuki in the center is worth thirty points"  

![day13_ponnuki](/images/day13_ponnuki.png)

This proverb highlights the immense value of an efficient and well-placed shape like the ponnuki. Formed when a stone is captured, leaving four stones surrounding the empty point, the ponnuki is strong, efficient, and radiates influence in all directions.
