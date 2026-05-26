# Security Guards (Firewall)

The firewall controls who may enter the building.

Linux commonly uses:

UFW

Meaning:

Uncomplicated Firewall

## Check Security Guard Status

sudo ufw status

## Enable Security Guard

sudo ufw enable

## Disable Security Guard

sudo ufw disable

## Allow Visitors

sudo ufw allow 22

## Block Visitors

sudo ufw deny 22

## Important Discovery

The security guard does not create doors.

Departments create doors.

The security guard only allows or blocks visitors.

## Building Analogy

Firewall = Security Guard

Port = Door

Service = Department

## Key Takeaway

Firewall controls access.

It does not create services or open ports.
