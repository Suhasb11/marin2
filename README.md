# marin2

This app is developed for tracking the ship. this is similar to marin1 only added leaflet.extras library

1. convert the csv file to feather format to increase the speed
2. files used 
app.R - main file containing ui and server
mapserver - shiny module for server components
uimodule - all ui components of shimy module

library(gaugeR)
library(shiny)
#library(shinyDashboardThemes)
library(shinyjs)
library(shinythemes)
library(shiny.semantic)
library(semantic.dashboard)

library(dplyr)
library(leaflet)
library(leaflet.extras)
library(geosphere)
library(plotly)
library(testthat)
library(feather)
