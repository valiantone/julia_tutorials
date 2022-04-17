# julia_tutorials
Learning Julia interactively in notebooks, via tutorials available on [julialang.org](https://julialang.org/learning/)


## Setup
We recommend using a Jupyter notebook instance for following through with tutorials. To get started with the same:
1. Download the latest stable release for your OS from [https://julialang.org/](https://julialang.org/)
2. Once installed, launch the Julia REPL and enter `]` to go in to the package manager sub-module.
3. To install IJulia, type the pakage manager command `add IJulia`

#### Launching a Notebook server with IJulia Kernel
From the Julia REPL, launch the Jupyter notebok server with eth following command:
> using IJulia
> notebook()