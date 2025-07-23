---
title: $bufferResize
description: Resizes the length of a buffer.
---

Resizes the length of a buffer.
## Parameters
|  Name  |         Description         | Enforced | Default Value |
|--------|-----------------------------|----------|---------------|
| Name   | The name of the buffer.     | Yes      | None          |
| Length | The new buffer byte length. | Yes      | None          |
## Example
```eats
$bufferResize[name;length]
```