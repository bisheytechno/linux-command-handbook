# kill Command

## What is kill?

The `kill` command is used to terminate a running process using its Process ID (PID).

## Syntax

```bash
kill PID
```

## Example

```bash
kill 1234
```

Terminates the process with PID `1234`.

## Force Kill a Process

```bash
kill -9 1234
```

Forcefully terminates the process if it does not stop normally.

## Find Process ID

```bash
ps aux | grep chrome
```

Displays the PID of running Chrome processes.

## Real World Example

```bash
ps aux | grep node
kill 5678
```

Stops the Node.js application running with PID `5678`.

## Common Signals

| Signal | Description                    |
| ------ | ------------------------------ |
| -15    | Graceful termination (default) |
| -9     | Force kill process             |
| -1     | Restart process (SIGHUP)       |

## Note

Be careful when using `kill -9` because the process is terminated immediately without cleanup.
