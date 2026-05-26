# Doors (Ports)

A port is a numbered door in the building.

Visitors use doors to enter.

Common doors:

22 = SSH

80 = Website

443 = Secure Website

## View Open Doors

ss -tulnp

## Check SSH Door

ss -tulnp | grep :22

Output:

0.0.0.0:22

Meaning:

Door 22 is open and accepting visitors.

## Building Analogy

Port = Door

Visitors enter through doors.

## Key Takeaway

Ports provide entry points into services.
