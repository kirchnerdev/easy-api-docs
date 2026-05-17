---
title: $renameFile
description: Renames a file from the source path to the destination path.
---

Renames a file from the source path to the destination path.
## Parameters
|    Name     |           Description           | Enforced | Default Value |
|-------------|---------------------------------|----------|---------------|
| Source Path | The path of the file to rename. | Yes      | None          |
| New Name    | The new name of the file.       | Yes      | None          |
## Example
```eats
$renameFile[sourcePath;newName]
```