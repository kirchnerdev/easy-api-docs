---
title: $stringReplace
description: Returns whether the given text starts with the provided word.
---

Returns whether the given text starts with the provided word.
## Parameters
|   Name   |               Description                | Enforced | Default Value |
|----------|------------------------------------------|----------|---------------|
| Text     | The text to work with.                   | Yes      | None          |
| Match    | The word to be matched.                  | Yes      | None          |
| Replacer | The word to replace the match with.      | No       |               |
| Strict   | Whether strictly replace all ocurrences. | No       | true          |
## Example
```eats
$stringReplace[text;match;replacer?;strict?]
```
## Function Aliases
- $replace
- $replaceText