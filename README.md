[![Join the #daf-d3 channel](https://img.shields.io/badge/Slack%20channel-%23daf--d3-blue.svg)](https://developersitalia.slack.com/messages/C8TGKHFQV)
[![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)

# Introduction
This repo contains a [d3.js](https://d3js.org/) infographic that visualizes [MIUR](http://www.miur.gov.it/)'s data (link [here](http://dati.ustat.miur.it/dataset/07d1c63f-9b1a-47f0-9648-66663e59c3f6/resource/9bebad94-3c0b-469e-8e50-b474d52aeb27/download/file02_2015-16_provenienze.csv)) on the number, hometown ("comune di residenza"), and sex of enrolled students and newly enrolled students in Italian Universities ("Atenei") in the Academic Year 2015/2016. It shows the inbound, outbound, and stationary flow of students per region, area of study, and sex.

## Data folder
Data contained in the data folder have been extracted with the following command:

    wget -O file02_2015-16_provenienze.csv http://dati.ustat.miur.it/dataset/07d1c63f-9b1a-47f0-9648-66663e59c3f6/resource/9bebad94-3c0b-469e-8e50-b474d52aeb27/download/file02_2015-16_provenienze.csv

# Running the application
    npm install
    npm start

# Licence

Copyright (c) 2017-2018, the respective contributors, as shown by the AUTHORS file.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.


# Note
This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). It uses React + D3js ES6.
