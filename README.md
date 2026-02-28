# UC11 – Volume Category Integration

**Date:** 2026-02-24  

## Overview  
Introduced a third measurement category — **Volume** — to validate the scalability of the generic `Quantity<U>` architecture implemented in UC10.

Only a new `VolumeUnit` enum was required. No changes were made to `Quantity<U>`, proving the architecture is truly extensible.

## What Was Added  
- `VolumeUnit` enum (LITRE, MILLILITRE, GALLON)  
- Base unit: LITRE  
- Equality, conversion, and addition support via generic logic  
- Comprehensive unit tests for volume operations 

## Principles Followed  
- OCP (Open for extension, closed for modification)  
- DRY (Logic reused from generic implementation)  
- Type-Safe Generics  
- Separation of Concerns  