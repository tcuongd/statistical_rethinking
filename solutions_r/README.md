### Solutions to Practice exercises in R and `cmdstanr`

#### Installation

Ensure you have the following installed:

* RStudio
* `R` >= 4.0

For the smoothest package dependency experience this project uses `renv`. You can install `renv` to `R` using `install.packages("renv")`.

Once `renv` is installed, open `solutions_r.Rproj` and run:

```
renv::restore()
```

Follow the prompts to install the dependencies.

After that you should be able to open and run the `.Rmd` files for each chapter with no issues. They can be knitted to `.nb.html` files using the Knit functionality in RStudio.