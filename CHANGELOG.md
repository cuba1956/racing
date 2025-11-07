# Changelog

## Unreleased

- **Racecraft**: Drivers now coast once they reach the apex speed and must scrub excess pace via an overshoot penalty before re-accelerating, producing more believable corner exits.
- **Telemetry**: The pedal graph draws a turquoise baseline whenever the car is coasting, making apex management easy to spot in replays or live runs.
- **Tyres**: Rebalanced the wear constant and compound multipliers so stint lengths better match real expectations (softs ≈7 laps, mediums ≈12, hards ≈17 by default) and tweaked overall degradation response.
- **Lookahead**: Reduced the minimum anticipation interval to 10 ms and expanded the slider range (down to 0.25× base) so the player can sample ultra-fast reaction settings.
