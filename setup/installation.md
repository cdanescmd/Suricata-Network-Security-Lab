# Suricata Installation

## Environment
- Ubuntu Linux (VM)
- Isolated virtual lab network
- Limited system resources to simulate real-world constraints

## Tool Selection
Suricata was selected as the intrusion detection system due to its open-source availability, active community support, and widespread use in enterprise security monitoring environments.

## Installation Approach
Suricata was installed using the system package manager to ensure compatibility with the operating system and simplify updates. Default service management was used to integrate Suricata with system startup processes.

## Validation
Post-installation checks were performed to confirm:
- Suricata binary availability
- Service registration with systemd
- Network interface visibility
