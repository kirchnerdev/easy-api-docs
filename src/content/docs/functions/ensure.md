---
title: $ensure
description: finally statement as blocks.
---

finally statement as blocks.
:::danger
**$ensure** is only usable inside **$xtry**.
:::
## Parameters
| Name |               Description                | Enforced | Default Value |
|------|------------------------------------------|----------|---------------|
| Code | The code to execute after try execution. | Yes      | None          |
## Example
```eats
$ensure[code]
```