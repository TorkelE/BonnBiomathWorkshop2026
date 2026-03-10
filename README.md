# Bonn Conference on Mathematical Life Sciences 2026- Catalyst and Julia W
This is a workshop on how to use the Julia programming language generally to create, simulate, and analyse models in mathematical systems biology. The primary package considered is Catalyst.jl, although other packages (either how they combine with Catalyst, or when run separately) are also considered. More information of the workshop can be found here: https://www.bcml.uni-bonn.de/events/2nd-bonn-conference-on-mathematical-life-sciences/catalyst-workshop

## Preparations and Setup

#### To set up Julia and download required packages (ideally do this before the workshop)

- Generally, VSCode is the recommended IDE for all Julia programming. See how to install it and its Julia extension here: https://code.visualstudio.com/docs/languages/julia.
- Download this repository and place somewhere on your computer (or clone using `git clone https://github.com/TorkelE/BonnBiomathWorkshop2026.git`).
- Open this repository in VSCode.
- Start a Julia terminal (e.g. through the [VSCode Command Palette](https://code.visualstudio.com/api/ux-guidelines/command-palette) followed by "Julia: Start REPL").
- Run `]activate .` in your Julia terminal (`]` will open [*Pkg mode*](https://docs.julialang.org/en/v1/stdlib/REPL/#Pkg-mode), from where you enter "activate .").
- Still in Pkg mode, run `instantiate`. This will download all Julia packages that are used in this workshop.

#### To run the workshop
The workshop consists of a set of notebook. To run the workshop, go through each notbook in order. When starting a notebook for the first time, you have to desigante a kernel. Here select the "Julia release channel kernel".

