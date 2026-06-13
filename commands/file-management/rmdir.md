# rmdir Command

## What is rmdir?

The `rmdir` command is used to remove empty directories.

## Syntax

```bash
rmdir directory_name
```

## Example

```bash
rmdir testfolder
```

Removes the empty directory named `testfolder`.

## Remove Multiple Empty Directories

```bash
rmdir folder1 folder2 folder3
```

## Real World Example

```bash
mkdir demo
rmdir demo
```

Creates a directory named `demo` and then removes it.

## Note

`rmdir` only works on empty directories.

If the directory contains files, use:

```bash
rm -r directory_name
```
