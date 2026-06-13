# cut Command

## What is cut?

The `cut` command is used to extract specific columns or fields from text files.

## Syntax

```bash
cut [options] file
```

## Example

```bash
cut -d ',' -f1 users.csv
```

Extracts the first column from a CSV file.

## Extract Multiple Fields

```bash
cut -d ',' -f1,3 users.csv
```

Extracts the first and third columns.

## Extract Characters

```bash
cut -c1-5 file.txt
```

Displays the first five characters of each line.

## Real World Example

```bash
cut -d ':' -f1 /etc/passwd
```

Displays only usernames from the `/etc/passwd` file.

## Sample Output

```bash
root
daemon
bishal
```
