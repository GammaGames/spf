---
layout: post
title: On Sprites
sidebar: Sprites?
description: Some general information and pros/cons of the system.
---

## What is a Sprite?

Let's start with a definition from the [documentation](https://sdk.play.date/2.0.3/Inside%20Playdate.html#C-graphics.sprite):

> Sprites are graphic objects that can be used to represent moving entities in your games, like the player, or the enemies that chase after your player.

They abstract the drawing and updating of game objects away so you can focus on the programming of your game, and provide helper functions to make your dev life easier. For most games, sprites are the way to go.

### Pros

The sprite system has a few perks that make it a good choice for most games:
* Their `:update` method is called automatically
* They handle optimizing drawing only when the sprite changes
* You can set their Z-index to layer sprites at runtime
* The SDK provides management functions like `performOnAllSprites()` and `removeAll()`
* Sprites have a basic collision system built-in
* Sprites have helper functions to make working with tilemap objects easier

### Cons

The system doesn't come without its downsides, though:
* There is performance overhead
* f
