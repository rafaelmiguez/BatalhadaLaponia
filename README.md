# Batalhas de Lapônia

**C/C++ · console game · academic group project (2021)**

A two-player, turn-based board game developed as a first-semester group project. The repository preserves an early programming exercise involving game rules, console menus, player input, and file-based state.

## Gameplay

- Each player controls nine pieces: four with frontal attacks, four with diagonal attacks, and one special unit.
- Six special-unit classes are described in the original project documentation.
- Players have three actions per turn and win by eliminating the opposing pieces.
- The game includes a tutorial, player-name selection, manual or randomized piece placement, movement, and attacks.

## Explore the source

- [Original documentation and rules (Portuguese)](./BatalhaDaLaponia/Batalhas%20de%20Lap%C3%B4nia-%20README.txt)
- [Source directory](./BatalhaDaLaponia/)
- [MenuBL.cpp](./BatalhaDaLaponia/MenuBL.cpp) — console entry point containing `main`.
- The headers in the source directory contain additional game and interface routines.

## Running and compatibility

The source uses Windows console commands such as `cls` and `pause`. Start by opening the source directory in a Windows C/C++ development environment and reviewing the entry point and included headers. Keep the text files alongside the program: the menu reads and updates `verificacao.txt`.

The original toolchain and a reproducible build command are not documented. A fresh build has not been verified as part of this documentation update; compatibility adjustments may be needed on current systems.

## Team and context

The original documentation credits Gustavo Rodrigues Muti Pacheco, Fred Lopes Machado, Rafael Vieira Miguez, Felipe Leão da Silva Dias, and Antônio Mesquita. This repository represents collaborative coursework; it does not assign the entire implementation to any one contributor.

The original source and Portuguese documentation are preserved as a record of the project.
