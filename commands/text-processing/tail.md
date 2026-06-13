# tail Command

## What is tail?

The `tail` command is used to display the last few lines of a file.

## Syntax

```bash
tail filename
```

## Example

```bash
tail notes.txt
```

Displays the last 10 lines of `notes.txt`.

## Display Last 5 Lines

```bash
tail -n 5 notes.txt
```

Shows only the last 5 lines of the file.

## Monitor File Changes in Real Time

```bash
tail -f app.log
```

Continuously displays new lines added to the file.

## Real World Example

```bash
tail /var/log/syslog
```

Displays the most recent system log entries.

## Sample Output

```bash
Jun 13 10:30:15 systemd[1]: Started nginx.service.
Jun 13 10:31:02 sshd[1234]: Accepted password for bishal
```

## Common Options

| Option | Description               |
| ------ | ------------------------- |
| -n 5   | Show last 5 lines         |
| -n 20  | Show last 20 lines        |
| -f     | Monitor file in real time |

## Note

Press `Ctrl + C` to stop `tail -f`.
