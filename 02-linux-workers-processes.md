# Workers (Processes)

A process is a worker currently performing a task inside the building.

Examples:

SSH worker

Docker worker

Nginx worker

Every active task is being performed by a worker.

## View Workers

Command:

ps aux

Meaning:

ps = Process Status

a = All Users

u = User Information

x = Background Workers

## Example

ps aux | head

Shows the first few workers currently active.

## Find Specific Worker

ps aux | grep ssh

Shows SSH-related workers.

## Building Analogy

Worker = Process

No worker = No work being performed.

## Key Takeaway

Processes are active workers performing tasks inside Linux.
