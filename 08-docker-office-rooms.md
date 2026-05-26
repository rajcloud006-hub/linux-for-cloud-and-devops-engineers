# Docker Office Rooms

Docker allows applications to run inside temporary office rooms within the building.

Each room contains everything the worker needs.

## What is Docker?

Docker is a platform used to create and run containers.

## What is a Container?

A container is a temporary office room.

Everything required is already inside:

- tools
- software
- libraries
- configuration

## What is an Image?

An image is the architect's blueprint.

Docker uses the blueprint to build a room.

## First Container

sudo docker run hello-world

Docker:

1. Found blueprint
2. Built room
3. Started worker
4. Worker completed task
5. Room stopped

## Interactive Container

sudo docker run -it ubuntu:20.04 bash

Creates a temporary office room and places you inside.

## Important Discovery

Inside container:

docker command not found

Why?

Docker exists in the building.

Not inside the room.

## Building Analogy

Linux Server = Building

Container = Temporary Office Room

Image = Architect's Blueprint

Application = Worker

Docker = Building Manager

## Key Takeaway

Containers are isolated rooms used to run applications consistently everywhere.
