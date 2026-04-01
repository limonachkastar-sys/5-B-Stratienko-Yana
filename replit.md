# Hello World Python Project

## Overview
A minimal Python "Hello World" demonstration script.

## Project Structure
```
hello-world/
  hello-world.py   # Simple Python script that prints "Hello World"
.replit            # Replit configuration (python-3.12, nix stable-25_05)
```

## Tech Stack
- **Language**: Python 3.12
- **Runtime**: Nix (stable-25_05)

## Running
The workflow "Start application" runs:
```
python hello-world/hello-world.py
```
Output: `Hello World`

## Notes
- No web server, frontend, or external dependencies — this is a pure console script.
- Fixed a syntax error in the original import: `print['Hello World']` → `print("Hello World")`
