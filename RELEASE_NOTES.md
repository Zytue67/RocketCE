# RocketCE v1.0.1 — Lower, controllable jumps

- A quick tap of 2nd now produces a low jump suitable for hitting a ground ball, rather than jumping straight over it.
- Hold 2nd for up to 0.2 seconds for extra height.
- Reduced the neutral double-jump impulse to match the first jump. Directional flips, boost and gravity retain their existing tuning.

Replace **ROCKETCE.8xp** on your calculator. Existing artwork AppVars and runtime libraries are unchanged. For multiplayer, update both calculators so the host uses the new physics.

This is an arcade approximation of Rocket League's tap/hold behavior, not an exact physics reproduction. Native build and host regression results are documented in VALIDATION.md; calculator feel and FPS need physical testing.
