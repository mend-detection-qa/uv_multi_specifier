# Test Case: UV Multi-Specifier with Exclusion

## Package Manager
UV

## Python Version Detection
- **Source**: pyproject.toml
- **Expected Version**: >=3.10,!=3.11.*
- **Format**: Multi-specifier with exclusion pattern

## Test Purpose
Test UV with complex constraints that exclude specific versions (3.10.x and 3.12.x OK, but NOT 3.11.x).
