# Awesome R Packages

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

## Warning

- I did not include the subpackages of [{tidyverse}](https://www.tidyverse.org/packages/), [{tidymodels}](https://www.tidymodels.org/packages/) and [{devtools}](https://devtools.r-lib.org/#conscious-uncoupling) but I encourge to check them.
- The "**?**" in some package descriptions indicates that the packge was recently added to this list and I am not too sure about it.

## Packages

### Must absolutely have
- {tidyverse} ([site](https://www.tidyverse.org) / [GitHub](https://github.com/tidyverse)): The base of modern R. Check its [subpackages](https://www.tidyverse.org/packages/).

### Machine learning
- {tidymodels} ([site](https://www.tidymodels.org/) / [GitHub](https://github.com/tidymodels)): The base of modern R machine learning. Check its [subpackages](https://www.tidymodels.org/packages/).
- {dalex} ([site](https://modeloriented.github.io/DALEX/) / [GitHub](https://github.com/ModelOriented/DALEX)): Model interpretation.
- {tidytext} ([site](https://github.com/juliasilge/tidytext) / [GitHub](https://juliasilge.github.io/tidytext/)): Text analysis.

### Bayesian statistics
- {tidybayes} ([site](https://mjskay.github.io/tidybayes/) / [GitHub](https://github.com/mjskay/tidybayes/)): The base of modern R bayesian statistical analysis. Only analysis, the computation is made by Stan.
- {cmdstanr} ([site](https://mc-stan.org/cmdstanr/) / [GitHub](https://github.com/stan-dev/cmdstanr)): The base of modern R bayesian statistics. R interface to Stan.
- {brms} ([site](https://paul-buerkner.github.io/brms/) / [GitHub](https://github.com/paul-buerkner/brms)): Bayesian regression models.

### Tables
- {gt} ([site](https://gt.rstudio.com) / [GitHub](https://github.com/rstudio/gt)): The {ggplot2} of tables.

### Plots
- {ggplot2} ([site](https://ggplot2.tidyverse.org) / [GitHub](https://github.com/tidyverse/ggplot2)): The base of modern R plots.
- {patchwork} ([site](https://patchwork.data-imaginist.com) / [GitHub](https://github.com/thomasp85/patchwork)): Combine plots.
- {gganimate} ([site](https://gganimate.com) / [GitHub](https://github.com/thomasp85/gganimate)): Animations.

### Literate programming
- {rmarkdown} ([site](https://rmarkdown.rstudio.com) / [GitHub](https://github.com/rstudio/rmarkdown)): The base of modern R literate programming.
- {epoxy} (no site / [Github](https://github.com/gadenbuie/epoxy)): Add "glue rmarkdown chunks" that allow to easily produce text with code.
- {tinytex} ([site](https://yihui.org/tinytex/) / [GitHub](https://github.com/yihui/tinytex)): LaTeX.
- {bookdown} ([site](https://bookdown.org) / [GitHub](https://github.com/rstudio/bookdown)): Books.
- {thesisdown} ([site](https://ismayc.github.io/thesisdown/) / [GitHub](https://github.com/ismayc/thesisdown)): Thesis.
- {rticles} ([site](https://bookdown.org/yihui/rmarkdown/journals.html) / [GitHub](https://github.com/rstudio/rticles)): Articles.
- {distill} ([site](https://rstudio.github.io/distill/) / [GitHub](https://github.com/rstudio/distill)): Web articles.
- {xarigan} ([site](https://slides.yihui.org/xaringan/) / [GitHub](https://github.com/yihui/xaringan)): Web slides.
- {pagedown} ([site](https://pagedown.rbind.io) / [GitHub](https://github.com/rstudio/pagedown)): Paged reports, posters, CVs, cards, letters, etc.

### Dashboard
- {shiny} ([site](https://shiny.rstudio.com) / [GitHub](https://github.com/rstudio/shiny)): The base of modern R web applications.
- {shinydashboard} ([site](https://rstudio.github.io/shinydashboard/) / [GitHub](https://github.com/rstudio/shinydashboard)): Dashboards.
- {bs4Dash} ([site](https://rinterface.github.io/bs4Dash/) / [GitHub](https://github.com/RinteRface/bs4Dash)): {shinydashboard}, but with bootstrap 4 and AdminLTE 3. Great with {shinyWidgets}.
- {flexdashboard} ([site](https://rmarkdown.rstudio.com/flexdashboard/) / [GitHub](https://github.com/rstudio/flexdashboard)): Dashboards using RMarkdown. Great for static dashboards (just a single `.html` file) with {htmlwidgets} and {crosstalk}.
- {bslib} ([site](https://rstudio.github.io/bslib/) / [GitHub](https://github.com/rstudio/shiny)): Bootstrap themes.

### Web
- {httr2} ([site](https://httr2.r-lib.org/) / [GitHub](https://github.com/r-lib/httr2)): The future of {httr} **?**
- {plumber} ([site](https://www.rplumber.io) / [GitHub](https://github.com/rstudio/plumber)): Web APIs.

### DevOps
- {devtools} ([site](https://devtools.r-lib.org) / [GitHub](https://github.com/r-lib/devtools)): The base of modern R package/project development. Check its [subpackages](https://devtools.r-lib.org/#conscious-uncoupling).
- {pak} ([site](https://pak.r-lib.org/) / [GitHub](https://github.com/r-lib/pak)): Package installation. Basicaly, {remotes} on steroids.
- {rsconnect} ([site](https://rstudio.github.io/rsconnect/) / [GitHub](https://github.com/rstudio/rsconnect)): Deploy.

### Reproducibility
- {targets} ([site](https://docs.ropensci.org/targets/) / [GitHub](https://github.com/ropensci/targets)): Analysis workflows/pipelines.
- {renv} ([site](https://rstudio.github.io/renv) / [GitHub](https://github.com/rstudio/renv)): Dependency management.
- {here} ([site](https://here.r-lib.org) / [GitHub](https://github.com/r-lib/here)): Path relative to project folder.

### Others
- {fs} ([site](https://fs.r-lib.org) / [GitHub](https://github.com/r-lib/fs)): File system.
- {memmoise} ([site](https://memoise.r-lib.org) / [GitHub](https://github.com/r-lib/memoise)): Cache.
- {slider} ([site](https://davisvaughan.github.io/slider/) / [GitHub](https://github.com/DavisVaughan/slider)): Sliding window {purrr}.
- {clock} ([site](https://clock.r-lib.org/) / [GitHub](https://github.com/r-lib/clock)): The future of {lubridate} **?**
