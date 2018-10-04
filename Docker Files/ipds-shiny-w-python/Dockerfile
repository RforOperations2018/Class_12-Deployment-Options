FROM ipds/shiny-base

MAINTAINER Geoffrey Arnold "geoffrey.arnold@pittsburghpa.gov"

# sytem libaries for python & xml
RUN apt-get update \
    && apt-get upgrade -y \
    && apt-get install -y \
    

RUN pip install mechanize

# install dependencies of most Python dependent apps
RUN R -e "install.packages(c('shinythemes', 'httr', 'jsonlite', 'R4CouchDB', 'DT', 'RCurl', 'readxl', 'plotly', 'DT', 'shinydashboard'), repos='https://cloud.r-project.org/')"