# Stellar-Modelling

**A stellar model script used to calculate the interior structure of a star.**

Uses the main 4 stellar structure equations to calculate a solution of radius, luminosty, pressure and temperature of a star, from it's centre to its surface.

Depends on initial inputs (that must be within 20% of our Sun) which determines the star's properties (adiabatic or radiative temperature gradient) and iterates through guesses until a stable solution is found.

The model assumes a main sequence star with a combination of p-p and CNO energy generation.
