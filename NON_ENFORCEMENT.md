# Non-Enforcement Declaration

ARCHICUSTOS is an **archival primitive**, not an enforcement mechanism.

## What ARCHICUSTOS does

- Archives input data
- Outputs deterministic archive hash
- Returns exit code indicating success/failure of archiving

## What ARCHICUSTOS does NOT do

- Validate content correctness
- Enforce retention rules
- Verify archive integrity over time
- Make trust decisions
- Block or allow actions

## Enforcement responsibility

Enforcement is the responsibility of:
- The calling system (CICULLIS, MK10-PRO, etc.)
- The policy layer above ARCHICUSTOS
- Human decision-makers

## Liability

ARCHICUSTOS output indicates "this was archived" — nothing more.
Archiving does not imply correctness, completeness, or validity.
