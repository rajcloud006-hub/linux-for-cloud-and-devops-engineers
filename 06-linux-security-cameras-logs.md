# Security Cameras (Logs)

Logs record events happening throughout the building.

Think of them as security camera recordings.

## View Recordings

journalctl

## View SSH Recordings

journalctl -u ssh

## View Recent Events

journalctl -u ssh | tail -n 5

## Follow Live Events

journalctl -u ssh -f

## Why Logs Matter

When something fails:

Do not guess.

Check the recordings.

## Building Analogy

Logs = Security Cameras

journalctl = Security Camera Viewer

## Key Takeaway

Logs provide evidence.

Always verify before making assumptions.
