# Whimsical Carnival Spin Wheel

---

## Overview

This is a full-scale interactive front-end demonstration built to showcase deterministic motion logic, SVG rendering, and Canvas-based particle simulation without external libraries.

The experience simulates a carnival-style spin wheel that always resolves positively by design. While playful in concept, the implementation focuses on precision animation control, mathematical rendering, and synchronized UI state management.

---

## Live Demo

https://hastonking.github.io/Spin-Wheel-Demo/

---

## Concept

The wheel animates toward a calculated final rotation rather than a purely random stop.

Key principles behind the interaction:

- Deterministic spin targeting  
- Accurate wedge index calculation  
- Guaranteed alignment between landing position and displayed result  
- Structured animation sequencing  
- Clean reset state handling  

The visual result is always programmatically synchronized with the exact wedge selected.

---

## Technical Highlights

### Motion & State Control

- Deterministic spin logic (no uncontrolled drift)  
- Explicit rotation targeting  
- Controlled easing curves  
- Animation lifecycle management  
- Spin/reset isolation  

### SVG Rendering

- Dynamic wedge generation using polar-to-Cartesian math  
- Accurate arc path construction  
- Multi-line text fitting within angled segments  
- Adaptive font scaling to prevent clipping  
- Label rotation alignment  

### Canvas Particle System

- Confetti simulation via `requestAnimationFrame`  
- Gravity and friction modeling  
- Surface collision detection  
- Persistent particle accumulation until reset  

### UI & Responsiveness

- Result synchronization with final wedge  
- Responsive layout scaling  
- Desktop and mobile optimization  
- Layout containment and alignment safeguards  

### Architecture

- Vanilla HTML / CSS / JavaScript  
- No heavy frameworks  
- Separation of rendering, animation, and state logic  
- Readable, structured implementation  

---

## Folder Structure

