# Interface Contract

## Minimum contract

Every cross-system capability interface should define:

### Identity
- provider system
- capability identifier
- version
- interface version

### Input
- accepted data
- schema
- validation rules
- size and resource limits

### Output
- output schema
- status
- provenance references
- evidence references

### Execution
- permitted operations
- timeout
- retry behavior
- failure handling
- isolation requirements

### Governance
- authorization required
- delegated scope
- prohibited operations
- human escalation conditions

## Compatibility rule

An interface is not considered compatible merely because two systems can exchange data. Compatibility must be demonstrated through tests.
