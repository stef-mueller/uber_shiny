![uber logo](http://mediad.publicbroadcasting.net/p/sdpb/files/styles/medium/public/201607/uber.jpg)
# Shiny App to Explore Uber Data (ubeRideR)

This project is an RShiny Web Application that I developed for the RStudio Shiny Contest. The application itself explores my Uber Data. This data was requested from UBER and you can request your data from Uber on the following [link](https://help.uber.com/riders/article/download-your-data?nodeId=2c86900d-8408-4bac-b92a-956d793acd11).

The shinyapp is viewable on [https://vivekkatial.shinyapps.io/uber_shiny/](https://vivekkatial.shinyapps.io/uber_shiny/)

## Technical Information

This web application is written using the [R Shiny](https://shiny.rstudio.com/) web framework/R package. It demonstrates the of `HTMLTemplates` to render beautiful looking applications using R Shiny.

The theme used in this app is [Glint](https://colorlib.com/wp/product/glint/). 

The development time, including concept design, API research, data preparation, cleaning and application development took less than 20 hours.

## Shiny app

 The app was developed with best Shiny practices in mind, e.g. the use of Shiny modules. In total about 1,100 lines of code were written for this app in less than 80 hours. This time included app ideation and all required research of data sources, data preparation and its operationalisation, app development, design and how to best present the information.

## Application Deployment

The app is deployed through RStudio's webservice [shinyapps.io](https://shinyapps.io/). Additionally, the app is published on [RStudio Cloud](https://rstudio.cloud/project/258634) which provides a complete development environment of the project.

You will also need your own Google API Token and Uber Credentials to collect the data required.

## Upcoming Features

- Ability for users to add their own data
- A more functional dashboard with interesting stats
- Visualisations
