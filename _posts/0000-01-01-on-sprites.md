---
layout: post
title: On Sprites
sidebar: Sprites?
description: Some general information and pros/cons of the system.
---

## What is a Sprite?

From the [documentation](https://sdk.play.date/2.0.3/Inside%20Playdate.html#C-graphics.sprite):

> Sprites are graphic objects that can be used to represent moving entities in your games, like the player, or the enemies that chase after your player.

<!-- > The best way to understand the sprite system, in my opinion, is to imagine how YOU would write a system that redraws only what's needed, and lets you treat graphics as atomic objects with properties. Instead of drawing as soon as you have something to draw, you might want to put all such draws into a table. Then, at draw time, you'd go through the table and see which of the objects in it have actually changed since the last draw. Once you have that table, you could also do neat things like, re-order the objects in it, so something draws on top (without moving its draw call in the code). And this is how the sprite system works—you create sprite objects, set their properties, and put them in a table. Then at draw time, that table gets iterated through, and things that qualify to be redrawn get redrawn.

https://discord.com/channels/675983554655551509/821661913393004565/1158542149315465237 -->

### Pros

### Cons
