Hey Gökce

Here is my version of Balls and their admires, where the code is filled in and including a flowchart. I could sadly not get the compiler to show the window of the balls, so i do not have a video.

## Balls and Their Admirers:
----------------------------

A simple Raylib simulation of colorful balls moving around a window — each ball randomly follows another ball, creating dynamic motion and interaction.

## Overview:
------------

Each ball has:

- A 2D position (posx, posy)

- A velocity (velx, vely)

- A radius

- A color

- A pointer to another ball it follows

- On every frame, each ball updates its velocity to move toward its “leader,” updates its position (with screen wrapping), and is drawn on the window.

## Features:
------------

- 100 colorful balls moving on screen

- Each ball follows another random ball (not itself)

- Continuous motion with screen wrapping

- Random initial position, velocity, color, and radius
