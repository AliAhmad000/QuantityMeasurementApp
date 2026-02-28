# UC12 – Subtraction and Division Operations

**Date:** 2026-02-24  

## Overview  
Extended the `Quantity<U>` class to support **subtraction** and **division**, completing arithmetic capabilities for all supported categories (Length, Weight, Volume).

Subtraction returns a new immutable `Quantity<U>`, while division returns a dimensionless scalar ratio.

## What Was Added  
- `subtract()` method (implicit and explicit target unit)  
- `divide()` method returning `double`  
- Division-by-zero validation  
- Cross-category arithmetic prevention   

## Principles Followed  
- Immutability  
- Defensive Programming 