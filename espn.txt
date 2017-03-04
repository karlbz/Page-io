## an R app to connect to ESPN 

library(shiny)

ui <- pageWithSidebar(
  headerPanel("Welcome!"),
  sidebarPanel(),
  mainPanel( HTML('<iframe width="1000" height="1000" src="http://www.espn.com" frameborder="0" allowfullscreen></iframe>')
  )
)

shinyServer(function(input, output) { })
