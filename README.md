# 3D Car Racing

A 3D car racing game built with Python (Flask) and Three.js.

## Features

- 4 curved circuit tracks (Circuit, Wobbly, Oval, Chicane)
- 2 car models: BMW M4 and Lamborghini Aventador
- 3D rendering with shadows, fog, and dynamic lighting
- Lap-based racing (3 laps)
- Traffic cars to avoid
- Nitro boost
- Keyboard controls

## Controls

| Key | Action |
|-----|--------|
| ↑ / W | Accelerate |
| ↓ / S | Brake |
| ← / A | Steer left |
| → / D | Steer right |
| Space | Nitro boost |

## Run

```bash
python3 -m venv venv
venv/bin/pip install flask
venv/bin/python server.py
```

Open http://localhost:6001
