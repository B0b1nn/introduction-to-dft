# Introduction to DFT

Interactive lecture notes on density functional theory (DFT) for materials modelling. The notes follow the development of the theory from the many-body Schrödinger equation to the Kohn-Sham scheme, and then to practical calculations and applications.

**Live site:** https://B0b1nn.github.io/introduction-to-dft/

## Contents

| Page | Topics |
| --- | --- |
| `index.html` (Part 1) | First-principles modelling, the exponential wall, single-particle approximations (Hartree, Hartree-Fock), the Hohenberg-Kohn theorem, Kohn-Sham equations, LDA, the SCF cycle, practical calculations (k points, cutoff energy), catalyst screening, scope and limitations of DFT |
| `part2.html` (Part 2) | Forces and equilibrium structures, exchange-correlation functionals (LDA, GGA), plane waves and pseudopotentials, band structures and the band gap problem, a checklist for reliable calculations, glossary |

## Interactive elements

- **Exponential wall calculator:** how the storage needed for the many-body wavefunction grows with the number of particles, compared with the electron density.
- **SCF convergence model:** an illustrative model of how the mixing parameter affects convergence (not a real DFT calculation).
- **Hydrogen adsorption slider:** how the adsorption energy relates to catalytic activity.
- **Quasiparticle gap calculator:** the gap from total-energy differences (illustrative numbers).

## Sources

- F. Giustino, *Materials Modelling using Density Functional Theory: Properties and Predictions*, Oxford University Press, 2014.
- D. S. Sholl and J. A. Steckel, *Density Functional Theory: A Practical Introduction*, Wiley.
- Original papers cited in the notes: Hohenberg and Kohn (1964), Kohn and Sham (1965), Greeley et al. (2006).

These notes are a study summary and do not replace the books. Please consult the sources for complete derivations and for the original figures.

## Running locally

Each page is a single self-contained HTML file with no dependencies. Download the repository and open `index.html` in a web browser.

## Updating the site

Edit or upload the HTML files in the repository root. GitHub Pages (Settings, Pages, branch `main`, folder `/ (root)`) republishes the site automatically within a couple of minutes.
