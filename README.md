# UC5 – Explicit Unit-to-Unit Conversion

**Date:** 2026-02-23  

## Overview
Introduced explicit conversion API for length units.

## What Was Added
- `convert(value, sourceUnit, targetUnit)` method
- Validation for NaN, Infinity, null units
- Precision handling with epsilon
- Overloaded demonstration methods

## Principles Followed
- API Design Best Practices
- Immutability
- Encapsulation
- Defensive Programming