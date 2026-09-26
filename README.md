# Waves

Amin Gh.'s personal site — portfolio, code, and interactive physics visualizations.

**Live:** https://imzadeqasemzade.github.io/Waves/

## Site map

- `/` — portfolio: robotics builds (SpiderBot, Grabbie, PetPal), code projects,
  skills, background
- `/moving-charge/` — interactive visualization: fields of a moving charge

## Visualizations

### 01 — Fields of a moving charge

Drag a point charge around and watch its E-field lines lag behind it — the far
field still points at where the charge *was*, because the news travels at `c`.
Flip on **Oscillate** and watch kinks peel off the field lines as transverse EM
waves. That peeling is exactly what a radio antenna does.

The field lines are the instantaneous electric field computed from the
**Liénard–Wiechert fields** (the exact relativistic field of an arbitrarily moving
charge), with the retarded time solved numerically at every grid point. The lag,
the forward compression of a fast charge, and the radiation kinks all fall out of
Maxwell's equations — nothing is faked.

## Roadmap

- [x] Moving charge — Liénard–Wiechert field lines, drag + oscillate modes
- [ ] Wire antenna — driven dipole, Poynting vector, live far-field radiation pattern
- [ ] Wave propagation — reflection, interference, standing waves
