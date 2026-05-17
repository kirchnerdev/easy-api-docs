---
title: $createSymlink
description: Creates a symbolic link to the source path.
---

Creates a symbolic link to the source path.
## Parameters
|    Name     |                    Description                     | Enforced | Default Value |
|-------------|----------------------------------------------------|----------|---------------|
| Source Path | The path of the file to create a symbolic link to. | Yes      | None          |
| Link Path   | The path of the file to link.                      | Yes      | None          |
## Example
```eats
$createSymlink[sourcePath;linkPath]
```