# tee Command

## What is tee?

The `tee` command writes output to both the terminal and a file.

## Syntax

```bash
command | tee file.txt
```

## Example

```bash
ls | tee output.txt
```

## Append Output

```bash
ls | tee -a output.txt
```

## Real World Example

```bash
df -h | tee disk-report.txt
```
