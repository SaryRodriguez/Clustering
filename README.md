# Cluster Random Points

1. Project Instructions

Write a shiny application with associated supporting documentation. The documentation should be thought of as whatever a user will need to get started using your application.
Deploy the application on Rstudio's shiny server
Share the application link by pasting it into the provided text box
Share your server.R and ui.R code on github
The application must include the following:

Some form of input (widget: textbox, radio button, checkbox, ...)
Some operation on the ui input in sever.R
Some reactive output displayed as a result of server calculations
You must also include enough documentation so that a novice user could use your application.
The documentation should be at the Shiny website itself. Do not post to an external link.

The Shiny application in question is entirely up to you. However, if you're having trouble coming up with ideas, you could start from the simple prediction algorithm done in class and build a new algorithm on one of the R datasets packages. Please make the package simple for the end user, so that they don't need a lot of your prerequisite knowledge to evaluate your application. You should emphasize a simple project given the short time frame.

2. This Shiny application

This Shiny application ('Clustering') creates a Dynamic clustering through adding random points in a dashboard. 

It listens for the clicks in the dashbords. Counts the pooint on button clicks and generate a plot of the clustered points. 

3. how to visualize this Shiny application

Download the server.R and ui.R files and place them in a directory named 'Clustering'. Open an R session and set the working directory to the folder that contains the directory 'Clustering'. Then run the following commands:

library(shiny)
runApp('Clustering')
