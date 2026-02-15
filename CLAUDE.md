# CLAUDE.md

This file provides guidance for AI assistants working with this repository.

## Project Overview

**footballstuff** is an early-stage exploration project for football/soccer data analysis, written primarily in R. The project is documented in Spanish and aims to perform analyses such as sentiment analysis on social networks related to football.

The repository is minimal — it contains a single R script and a README.

## Repository Structure

```
footballstuff/
├── README.md          # Project description (Spanish)
├── firstRcode.R       # Sample R script with random data generation
└── CLAUDE.md          # This file
```

## Language & Runtime

- **Primary language:** R
- **No formal dependency management** — no `DESCRIPTION` file, no `renv.lock`, no `packrat`
- **No specific R version requirement** is declared
- To run the R script: `Rscript firstRcode.R`

## Build, Test, and Lint

- **No build system** is configured
- **No test framework** is set up
- **No linter or formatter** is configured
- **No CI/CD pipeline** exists

## Code Conventions

- **File naming:** camelCase (e.g., `firstRcode.R`)
- **Comments and documentation:** Written in Spanish
- **R style:** Uses `=` for assignment (not `<-`); uses base R functions (`rnorm`, `data.frame`)
- **Architecture:** Flat structure, no subdirectories — exploratory/prototype phase

## Git Workflow

- **Primary branch:** `master`
- **Commit messages:** Short, informal English messages
- **No branch protection or PR requirements** are enforced

## Development Notes

- This project is in the ideation/proof-of-concept phase
- The only implemented code generates random normal distributions and combines them into a data frame
- Planned work includes sentiment analysis on social networks (not yet implemented)
