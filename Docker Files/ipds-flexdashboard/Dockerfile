FROM ipds/shiny-base

MAINTAINER Geoffrey Arnold "geoffrey.arnold@pittsburghpa.gov"

# install dependencies of FlexDashboard app
RUN R -e "install.packages(c(,'plotly', 'R4CouchDB'), repos='https://cloud.r-project.org/')"