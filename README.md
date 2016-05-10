# Synopsis
A series of R scripts that can be used to create structured zip file known as the 'Default Import Package' that can be imported by the [National Household Model](https://github.com/cse-bristol/national-household-model-standalone) as a housing stock. For more information on the content and structure of files within the 'Default Import Package' please see the Stock section within the [NHM documentation](https://github.com/cse-bristol/national-household-model-documentation/releases).

TODO - Some blurb about the source files

# Installation
The scripts for creating the stock files have been written in [R](https://cran.r-project.org/), which will need to be downloaded and installed.

To ensure the scripts run correctly and build consisten stock files we recommend you ensure you have the necessary R pacakges installed at the required versions, to make this easier we have created an R script which should install these dependencies for you (install-dependencies.R)(http://tbd). This can be run from within your R environment. 

# External Project Dependencies
We cannot distributre the source data files for the Housing Condition survey files the R scripts build the stock files, you will need to obtain these from the the following locations.

1. English Housing Condition Survey - TODO
2. Scottish Housing Condition Survey - TODO

# License
[Open Government License] (http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
