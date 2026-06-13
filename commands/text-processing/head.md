# head Command

## What is head?

The `head` command is used to display the first few lines of a file.

## Syntax

```bash
head filename
```

## Example

```bash
head notes.txt
```

Displays the first 10 lines of `notes.txt`.

## Display First 5 Lines

```bash
head -n 5 notes.txt
```

Shows only the first 5 lines.

## Real World Example

```bash
head /etc/passwd
```

Displays the first few entries from the system user database.

## Sample Output

```bash
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
```

## Common Options

| Option | Description         |
| ------ | ------------------- |
| -n 5   | Show first 5 lines  |
| -n 20  | Show first 20 lines |
