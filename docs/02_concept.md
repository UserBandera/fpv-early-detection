# 2. Concept (public overview)

The module combines several sensors:

| Component | Role |
|---|---|
| Short-range radar | Detects moving objects, measures distance and speed |
| Wide-angle camera | Images for recognition |
| Embedded AI computer | Classifies objects (drone / not a drone) |
| Data logger | Records sensor data for development and training |

Principles:
- **Sector-based coverage** — the area around the robot is divided into sectors; the first prototype covers one sector.
- **Sensor fusion** — radar and camera complement each other (weather, dust, darkness).
- **Low cost & scalability** — standard components wherever possible.
- **Open interface** — the module outputs an alert and a target track to the robot's protective systems.

Detailed architecture, algorithms and calculations are confidential.

© 2026 Ivan Lozynskyi. All rights reserved.
