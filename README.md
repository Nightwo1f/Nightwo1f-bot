# Nightwo1f-bot

Personal research bot inspired by Mindee Bot for TibiaME / OTME / JTME. For personal and educational use only; no redistribution intended.

## Overview

- **Route-based automation (waypoints)**: Movement and actions driven by user-defined waypoint routes; waypoints are numbered and support reverse traversal.
- **Script engine**: Compatible with Mindee-style Python scripts; scripts act as a contract over the engine.
- **Multi-account headless sessions**: Multiple accounts handled via parallel sessions, no graphical client required for automation.
- **Minimal UI**: Only for route recording and monitoring; no full game UI.

## Technical notes

- TibiaME protocol is binary TCP; login yields a dynamic world server model (no IP/port hardcoded for world servers).
- Core game logic resides in native libraries (.so / native jars); this project implements a client and engine layer on top of protocol reverse engineering.

## License

MIT. See [LICENSE](LICENSE).

