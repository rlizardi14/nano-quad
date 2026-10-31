# Nano Quad — DIY 1S Brushed Quadcopter

A ~115 mm quadcopter built from first principles on a ~$100 budget:
custom ESP32-C3 flight controller, MOSFET motor drivers, ESP-NOW link,
3D-printed PETG frame, and model-based attitude control.

## Approach
Predict, then measure: every subsystem is modeled before it is built,
and every model is checked against experiment (thrust stand, bifilar
pendulum, 1-DOF test rig).

## Status
| # | Milestone | Status |
|---|-----------|--------|
| 0 | Requirements & power budget | In progress |
| 1 | Sensing (IMU + attitude estimation) | Parts ordered |
| 2 | Link & telemetry | — |
| 3 | Motor drive & characterization | — |
| 4 | Frame v1 | — |
| 5 | Model & control design | — |
| 6 | Bench integration | — |
| 7 | 1-DOF rig tuning | — |
| 8 | Guarded flight | — |

## Repository layout
See the README in each folder.

## Engineering log
[docs/log/](docs/log/)