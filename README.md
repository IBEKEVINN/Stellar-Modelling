# Stellar-Modelling

**A stellar model script used to calculate the interior structure of a star.**

Uses the main 4 stellar structure equations to calculate radius, luminosty, pressure and temperature from the centre of a star to its surface.

The model assumes a star with a combination of p-p and CNO energy generation. Depends on initial inputs (that must be within 20% of our Sun) which determines the star's properties (adiabatic or radiative temperature gradient) and iterates through guesses until a stable solution is found.
