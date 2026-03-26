# Flag Pole Linkage System

## Overview
Rotary-to-linear motion system using a stepper motor, gear train, and scissor linkage to drive vertical extension.

## What I Built
- Stepper motor control using Raspberry Pi + L298N
- Gear train driving a rack to translate rotation into linear motion
- Scissor linkage mechanism for vertical extension
- Limit switch for positional reset and repeatability

## Mechanism
A gear-driven rack moves linearly, driving one leg of a scissor linkage while the other leg remains fixed. This converts motor rotation into controlled vertical motion.

## Why It Matters
Demonstrates integration of mechanical linkage design with embedded motor control for precise linear actuation.

## Run
```bash
python3 scissor_linkage_actuation.py
