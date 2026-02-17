# 300x250 Interactive Banner Variant

## Overview

This is a 300x250 interactive display banner built as a compact variant of the Whimsical Carnival Spin Wheel project.

The objective was to demonstrate:

- Deterministic animation control in a constrained ad format
- SVG + Canvas integration inside fixed IAB dimensions
- Clean result synchronization between animation state and UI display
- Lightweight implementation suitable for display ad environments

## Concept

Title: **Odds That I Get The Job**

The banner uses a playful probabilistic theme.  
Each spin lands on exaggerated favorable odds (e.g., 100:1, 250:1, 1000:1) to convey confidence in a light, optimistic tone.

All outcomes resolve positively by design.

## Technical Highlights

- Fixed 300x250 layout (IAB standard)
- Responsive internal scaling
- Controlled rotation targeting (no random drift)
- Result box synchronized with final wedge
- Confetti simulation using Canvas particle system
- Persistent accumulation behavior until reset
- Clean mobile rendering
- No heavy frameworks

## Folder Structure

