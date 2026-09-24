# AirEXPRESS Fleet Tracker

A lightweight, browser-based 3D asset inspection and tracking interface powered by Google's `<model-viewer>`. Built for mobile-first and desktop visualization of ground support equipment (GSE), featuring interactive hotspots, dynamic specification flyouts, and native WebXR Augmented Reality support.

---

## Features

- **3D Asset Rendering:** Native WebGL rendering utilizing `<model-viewer>` v4.0.0.
- **Augmented Reality (AR):** Native AR quick-launch supporting WebXR, Scene Viewer (Android), and Quick Look (iOS).
- **Interactive Hotspots:** Clickable 3D surface annotations mapped to specific asset coordinates with automatic camera refocusing.
- **Dynamic Asset Switching:** Dropdown selector swapping models, associated metadata, and spatial hotspot nodes on demand.
- **Hardware Specifications Drawer:** Overlay panel displaying telemetry, operational crew assignments, and functional specs.
- **Glassmorphic Industrial UI:** Compact, responsive controls designed with CSS backdrop filters and hardware-acceleration.

---

## Directory Structure

Organize the repository as follows:

```text
yunexpress-fleet-tracker/
├── index.html
├── models/
│   ├── tld_121_aircraft_loader.glb
│   └── gpu_aiport_ground_power_unit.glb
└── README.md
