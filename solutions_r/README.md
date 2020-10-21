## Solutions to Practice exercises in R and `cmdstanr`

### Installation

Ensure you have the following installed:

* RStudio
* `R` >= 4.0

For package dependency management this project uses `renv`. Open `solutions_r.Rproj` to start. `renv` should start installing automatically if it's not installed already. If this is not the case, manually run `install.packages("renv")`.

Then run

```
renv::restore()
```

Follow the prompts to install the dependencies.

After that you should be able to open and run the `.Rmd` files for each chapter. They can be knitted to `.nb.html` files using the Knit functionality in RStudio.
