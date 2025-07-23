---
title: $imageAccentColor
description: Returns the accent color of a loaded image.
---

Returns the accent color of a loaded image.
:::danger
**$imageAccentColor** is only usable inside **$createCanvas**.
:::
## Parameters
|   Name   |                  Description                  | Enforced | Default Value |
|----------|-----------------------------------------------|----------|---------------|
| Image ID | Cached image ID to get the accent color from. | Yes      | None          |
## Example
```eats
$imageAccentColor[imageId]
```