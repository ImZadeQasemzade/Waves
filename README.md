# Waves

Interactive visualizations of electromagnetic fields and waves — built to *see*
the physics, not just read about it.

## 01 — Fields of a moving charge

**Live:** https://ImZadeQasemzade.github.io/Waves/

Drag a point charge around and watch its E-field lines lag behind it — the far
field still points at where the charge *was*, because the news travels at `c`.
Flip on **Oscillate** and watch kinks peel off the field lines as transverse EM
waves. That peeling is exactly what a radio antenna does.

The field lines are the instantaneous electric field computed from the
**Liénard–Wiechert fields** (the exact relativistic field of an arbitrarily moving
charge), with the retarded time solved numerically at every grid point. The lag,
the forward compression of a fast charge, and the radiation kinks all fall out of
Maxwell's equations — nothing is faked.

Try the **light speed** slider: slowing `c` down lets you watch the "news" of the
charge's motion propagate outward as an expanding boundary.

## Roadmap

- [x] Moving charge — Liénard–Wiechert field lines, drag + oscillate modes
- [ ] Wire antenna — driven dipole, Poynting vector, live far-field radiation pattern
- [ ] Wave propagation — reflection, interference, standing waves
