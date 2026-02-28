# UC13 – Centralized Arithmetic Logic (DRY Refactor)

**Date:** 2026-02-24  

## Overview  
Refactored arithmetic methods (`add`, `subtract`, `divide`) to eliminate duplication and enforce the **DRY principle**.

Introduced a centralized private helper method and `ArithmeticOperation` enum to manage operation dispatch cleanly.

## What Was Added  
- `ArithmeticOperation` enum (ADD, SUBTRACT, DIVIDE)  
- `performBaseArithmetic()` helper method  
- Centralized validation method  
- Removal of duplicated validation and conversion logic  

## Principles Followed  
- DRY (Don't Repeat Yourself)  
- SRP (Clear separation of responsibilities)  
- Encapsulation of internal logic  
- Backward Compatibility (All UC12 tests passed unchanged) 