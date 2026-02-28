# UC10 – Generic Quantity<U> with IMeasurable

**Date:** 2026-02-23  

## Overview
Refactored entire system into a single generic `Quantity<U>` class.

## What Was Added
- `IMeasurable` interface
- Generic `Quantity<U extends IMeasurable>` class
- Refactored LengthUnit and WeightUnit to implement interface
- Simplified QuantityMeasurementApp

## What I Learned
- Generic Programming in Java
- Interface-driven architecture
- Type erasure considerations
- Open-Closed Principle in action

## Principles Followed
- DRY (Logic implemented once)
- SRP
- OCP (Open for extension, closed for modification)
- Polymorphism and Delegation