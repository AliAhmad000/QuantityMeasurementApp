# UC14 – Temperature Category with Selective Arithmetic Support

**Date:** 2026-02-24 

## Overview  
Introduced **Temperature measurement** (Celsius, Fahrenheit) with selective operation support.

Unlike other categories, temperature supports equality and conversion but does not support standard arithmetic operations such as addition, subtraction, or division in meaningful contexts.

This required refactoring the `IMeasurable` interface to support optional arithmetic capabilities.

## What Was Added  
- `TemperatureUnit` enum (CELSIUS, FAHRENHEIT, KELVIN)  
- Non-linear conversion formulas  
- Refactored `IMeasurable` with default methods  
- `SupportsArithmetic` functional interface  
- Operation validation using `UnsupportedOperationException`  
- Arithmetic restriction enforcement in `Quantity<U>`  

## What I Learned  
- Interface Segregation Principle (ISP)  
- Capability-based design
- Backward-compatible interface evolution  

## Principles Followed  
- Interface Segregation Principle  
- Open-Closed Principle  
- Defensive Programming  
- Polymorphic behavior customization  
- Type Safety across categories  