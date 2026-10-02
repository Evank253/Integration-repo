# Integration Testing Protocol

Integration is not considered successful merely because two systems communicate.

## Test layers

1. Contract validation
2. Input/output validation
3. Failure-path testing
4. Boundary testing
5. Reproducibility testing
6. Provenance verification
7. Capability composition testing
8. Resource and latency characterization
9. Authorization-boundary testing
10. Regression testing

## Evidence rule

Every result must identify:

- test identifier
- versions/commits
- inputs
- environment
- expected behavior
- observed behavior
- artifacts
- logs/results
- reproducibility status

## Qualification

If evidence is absent or insufficient, record NOT_MEASURED or EVIDENCE_INSUFFICIENT rather than assuming success.
