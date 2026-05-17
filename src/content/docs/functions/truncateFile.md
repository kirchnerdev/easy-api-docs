---
title: $truncateFile
description: Truncates a file to the specified size.
---

Truncates a file to the specified size.
## Parameters
|   Name    |            Description            | Enforced | Default Value |
|-----------|-----------------------------------|----------|---------------|
| File Path | The path of the file to truncate. | Yes      | None          |
| Size      | The size of the file in bytes.    | Yes      | None          |
## Example
```eats
$truncateFile[filePath;size]
```