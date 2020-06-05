# Covid19-Curve-and-Soccer
## Description
Exploratory analysis of the coronavirus epidemiologic curve in Brazil, especially in Rio de Janeiro, and comparison with European countries. Analysis of the return of soccer.

## Data
The official data were used. The global data used were from the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE), and download by data.world platform. And the Brazilian data, with details of the cities was from the country's health ministry. The analysis was done with data until 06/30/2020.

- https://data.world/covid-19-data-resource-hub/covid-19-case-counts (World) 
- https://covid.saude.gov.br/ (Brazil)


## Libs
This work was done with Pandas and Plotly basically. The other libs needed to replicate the notebook are only to exporting the images. I recommend replacing fig.show ('svg', ...) with fig.show (), so that you can interact with the graph. And Chart Studio is for export to a Plotly account, this can also be removed.

- pandas==1.0.1
- plotly=4.8.1
- \*plotly-orca==1.3.1
- \*chart-studio==1.0.1

\* They are not important. Just to export the graphics.

## Post
Details of the analysis in this post on Medium:

https://medium.com/@miltongamaneto/compara%C3%A7%C3%A3o-entre-as-curvas-epidemiol%C3%B3gica-e-a-retomada-do-futebol-a57003194cb5
