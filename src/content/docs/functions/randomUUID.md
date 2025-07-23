---
title: $randomUUID
description: Generates a random [RFC 4122](https://www.rfc-editor.org/rfc/rfc4122.txt) version 4 UUID. The UUID is generated using acryptographic pseudorandom number generator.
---

Generates a random [RFC 4122](https://www.rfc-editor.org/rfc/rfc4122.txt) version 4 UUID. The UUID is generated using acryptographic pseudorandom number generator.
## Parameters
|         Name          |             Description             | Enforced | Default Value |
|-----------------------|-------------------------------------|----------|---------------|
| Disable Entropy Cache | By default, to improve performance. | No       | false         |
## Example
```eats
$randomUUID[disableEntropyCache?]
```