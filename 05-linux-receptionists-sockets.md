# Receptionists (Sockets)

A socket is a receptionist sitting at a door.

The receptionist waits for visitors and directs them to the correct department.

## Real Example

During SSH practice:

sudo systemctl stop ssh

SSH department stopped.

However:

ss -tulnp | grep :22

Still showed Door 22 open.

Why?

Because ssh.socket was still active.

The receptionist was still sitting at Door 22.

## Remove Receptionist

sudo systemctl stop ssh.socket

Door closed immediately.

## Building Analogy

Socket = Receptionist

Port = Door

Service = Department

## Key Takeaway

An open door does not always mean the department is running.

Sometimes a receptionist is still waiting at the door.
