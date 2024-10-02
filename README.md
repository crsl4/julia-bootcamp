# Welcome to the Julia bootcamp

This repository contains the material for the "Julia bootcamp" at the Stat. Dept., UW-Madison, Fall, 2024 semester

  - The goal for the bootcamp is to highlight the main features that make Julia an attractive option for data science programmers
  - The workshop is intended for statistics/data science students with experience in R and/or Python who are interested in learning the attractive features of Julia for Data Science. No knowledge of Julia is required.
  - Workshop materials in the github repository [julia-bootcamp](https://github.com/crsl4/julia-bootcamp)

## Learning objectives for this bootcamp

At the end of the bootcamp, participants will be able to:

  - Identify the main features that make Julia an attractive language for Data Science
  - Set up a Julia environment to run their data analysis
  - Efficiently handle datasets (even across different languages) through Tables.jl and Arrow.jl
  - Communicate across languages (Julia, R, Python)

## Schedule

| Date | Topic |
| -----| ------|
| Sept 26 | Introduction to Julia |
| Oct 3 | [Generalized Linear Mixed Models in Julia](https://github.com/crsl4/julia-bootcamp/blob/main/2-glm-implementation.qmd) |
| Oct 10 |  |
| Oct 17 |  |
| Oct 24 |  |


 
## In preparation for the bootcamp

Review the first part (Writing) of [Modern Julia Workflows](https://modernjuliaworkflows.github.io), abbreviated `MoJuWo`, which provides a general introduction to setting up a Julia development environment.

  - That first part of MoJuWo mentions the [VS Code](https://code.visualstudio.com) editor; we suggest using [Positron](https://github.com/posit-dev/positron) instead.  It is the same editor but customized by [Posit PBC](https://posit.co) for data scientists.  Install Positron or VS Code.
  - Install Julia using `juliaup`, as described in section 2 of `MoJuWo - Writing`
  - We will use [Quarto](https://quarto.org), also from [Posit PBC](https://posit.co), for preparing slides and documents. Install quarto.
  - Install the [Julia extension](https://code.visualstudio.com/docs/languages/julia) in VS Code or Positron. The [Quarto extension](https://quarto.org/docs/tools/vscode.html) is pre-installed in Positron.
  - Git clone the bootcamp repository: `git clone https://github.com/crsl4/julia-bootcamp.git`
  - Your cloned repository contains a file `Project.toml`, which is described in section 7 of `MoJuWo - Writing`.  Use "package mode" in the REPL to activate and update the environment.
