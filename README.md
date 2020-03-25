# pycovid
Author(s): Luke Boegner

## Project Overview
Applying data analysis and machine learning to better understand various aspects
of COVID-19. Primary current objective is to better understand how US State
government actions have been affecting the spreading rate of the virus. Current
approach is to read text from Wikipedia to extract information for each state's
responses, build a machine-learning (ML) natural language processing (NLP) model
to interpret the severity of various actions, and then plot the actions against
the growth rate of the confirmed cases. Follow-on analysis can then be done to
determine if/when different levels of actions helped slow down the spread of
COVID-19.

## TODO:
* Continue manually labelling wikipedia data from each state's COVID-19 pages (
running label_wiki_data notebook and manually labelling sentences)
* Enhance NLP model once more data is generated above (running model_dev
notebook)
* Integrate NLP ML model with plotting of data (currently hardcoded in
covid_analysis notebook)
* Perform follow-on analysis of the results seen from the plotting
* Transition to using wikipedia's confirmed cases data instead of the JHU CSV
