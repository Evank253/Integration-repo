# Integration Repository

This repository contains mechanisms that allow capabilities from independent systems to interoperate and compose without merging those systems.

## Purpose

Build the connective mechanisms, interfaces, adapters, contracts, and controlled execution paths required to turn existing capabilities into new cross-system capabilities.

## Model

System A → Capability A → Bridge → Capability B → System B

A bridge connects capabilities; it does not erase system boundaries.

## Design requirements

- explicit interfaces
- capability-level routing
- provenance preservation
- bounded execution
- failure isolation
- compatibility checks
- evidence capture
- reproducible tests
- no implicit authority escalation

See:
- CAPABILITY_BRIDGE_SPEC.md
- INTERFACE_CONTRACT.md
- BRIDGE_REGISTRY.yaml
- TESTING_PROTOCOL.md
