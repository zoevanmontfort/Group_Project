# Group_Project

players_url <- "https://raw.githubusercontent.com/Norah-supercoder/dsci-100-project-individual/refs/heads/main/players.csv"
sessions_url <- "https://raw.githubusercontent.com/Norah-supercoder/dsci-100-project-individual/refs/heads/main/sessions.csv"
library(repr)
library(tidyverse)
library(tidymodels)
options(repr.matrix.max.rows = 10)
source("cleanup.R")
set.seed(2000)
players <- read_csv(players_url)
head(players)
players 
