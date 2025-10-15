# Robotics Project — R1 (Manual) & R2 (Autonomous)

**Project structure:**  
- R1: Manually controlled robot (teleop, simpler stack)  
- R2: Autonomous robot with SLAM, perception, planning, and ML components

This repository contains mechanical, electronics, firmware, navigation, AI/ML, simulation, integration (ROS), and test artifacts to build, simulate, and operate both robots.

## Quick start
1. Read `docs/` for architecture and assembly guides.
2. For R1: flash firmware in `electronics/firmware` and test with the `navigation` teleop nodes.
3. For R2: see `navigation/` and `ai/` for SLAM, perception models, and inference.
4. Use `scripts/setup/` to install dependencies.

## Contributing
- Follow the branch naming convention: `feature/<area>/<short-desc>` (e.g. `feature/navigation/rviz-views`)
- Tests in `tests/` must pass before merging.
- Update relevant `docs/` when changing behavior.

## Contacts
- Team Lead: TODO
- Maintainers: TODO
