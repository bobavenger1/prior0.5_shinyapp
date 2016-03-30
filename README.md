# prior0.5_shinyapp
An R Shiny that allows the user to estimate the prior probability that one should use in a scenario tree in order for that prior to be uninformative given the sample size and design prevalence used. Values calculated assume that one is using a simple scenario tree in which there is one herd of n animals during one time period and the only branch probability is the sensitivity of the test.

Run in R by copy-pasting the following code into the R console:

  install.packages("shiny", dependencies = TRUE)
  
  shiny::runGitHub("matthewbranan/prior0.5_shinyapp")
