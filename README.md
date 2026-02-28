# UC6 – Addition of Two Length Units

**Date:** 2026-02-23  

## Overview
Implemented arithmetic addition between length measurements.

## What Was Added
- `add()` method for same and cross-unit addition
- Base-unit normalization before addition
- Result returned in first operand’s unit
- Edge-case validations (zero, negative, large values)

## Principles Followed
- Immutability
- Reusability of conversion logic
- Mathematical correctness
- DRY compliance