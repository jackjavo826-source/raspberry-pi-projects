# Raspberry Pi Projects

Personal experiments with single-board computers, Linux, and peripheral integration.

**Status: documentation stage.** This repository organizes the work and its validation requirements. Source packages, wiring diagrams, and hardware test results have not yet been published.

## Platforms and project areas

| Platform | Focus | What a reproducible project should include |
| --- | --- | --- |
| Raspberry Pi 5 | Linux setup and system integration | OS image/version, power requirements, dependencies, and configuration |
| Raspberry Pi Zero 2 W | Compact embedded Linux experiments | Board revision, peripheral interface, connection diagram, and startup behavior |
| Cross-platform | Troubleshooting and recovery | Minimal reproduction, sanitized logs, diagnosis, and recovery procedure |

## Bring-up documentation

Each experiment should record the exact board and peripheral models, software versions, interface settings, and expected behavior. Capture the smallest working configuration before adding services or automation.

Any camera project should specify the compatible connector and cable, capture software, and a non-sensitive test image. Any remote-access example should use placeholders and exclude real hostnames, addresses, keys, and credentials.

## Planned checks

- Cold boot with the documented power supply and peripherals
- Dependency installation on a clean image
- Peripheral detection and a minimal functional example
- Recovery from a disconnected peripheral or failed service
- Shutdown and restart behavior

## Current evidence

No checks above are recorded as passed. Hardware measurements and compatibility statements must be tied to the actual configuration and source revision used.

See the [portfolio documentation standards](https://github.com/jackjavo826-source/jackjavo826-source/blob/main/PORTFOLIO_STANDARDS.md).
