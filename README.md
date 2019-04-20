# Data Visualization with Maps Shiny Workshop

This repository contains the following:

- intro announcement slides
- workshop slides
- code we wrote during the workshop

If you would like to learn more about Shiny, please take a look at RStudio's [free tutorial on Shiny here](https://shiny.rstudio.com/tutorial/), as well as a great webinar [here](https://www.rstudio.com/resources/webinars/introduction-to-shiny/).

## Pre-installation

We assume you have RStudio installed on your computer. If you don't have it installed, please go to [this link](https://www.rstudio.com/) to install it on your computer.

We ask that you install the following packages before the event:

- **`sf`: to work with spatial data (this can be a pain to install, if you are running into issues with installing the "units" package, please arrive early so we can get you set up)**
- `shiny`: to make a Shiny app
- `leaflet`: to make interactive maps
- `spData`: spatial data package that contains the data we'll be working with
- `dplyr`: for some data wrangling examples

You can do this by pasting the following command into the R console and hitting enter:

```
install.packages(c("sf", "shiny", "leaflet", "spData", "dplyr"))
```

## If local installation isn't working...

If installation is not working for you on your local device, please create an account at [RStudio Cloud](https://rstudio.cloud/) and install the packages in a new project there.

Optional: you can also register for a free account at [shinyapps.io](https://www.shinyapps.io) ahead of time.

More information and sign up for this workshop on our [Meetup.com event](https://www.meetup.com/rladies-chicago/events/260316086/).
