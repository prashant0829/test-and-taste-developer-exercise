*Alternative Solution*:
We Can precompute the average gravity for moons when creating ⁠ MoonDto ⁠ objects and store it directly in ⁠ PlanetDto ⁠. Use this precomputed value in the ⁠ Planet ⁠ class.

*Benefit*:
This will reduce computational overhead in the ⁠ Planet ⁠ class, making it simpler and faster since gravity calculations are done only once.

*Drawback*:
This will increase complexity and potential redundancy in data handling, as any change in moon data requires recalculating and updating the precomputed values in ⁠ PlanetDto ⁠.
