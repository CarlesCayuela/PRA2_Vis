# PRA2 | VISUALITZACIÓ DE DADES

## Descripció:

Aquesta visualització mostra dades sobre el sanejament de les aigües residuals urbanes a nivell mundial. Es basa principlament en dades de l'organització mundial de la salut.
I pretén respondre a les següents preguntes:

- Quin percentatge de la població mundial té accés a sistemes de sanejament bàsic?
- Com es distribueixen a nivell mundial?
- Com ha evolucionat en el temps l'accés de la població al sanejament i quina relació existeix amb la riquesa del país?

## Conjunts de dades:

S'han utilitzat 3 conjunts de dades.

- [dades_who.xlsx](https://washdata.org/data/downloads#WLD): Fitxer principal amb les dades sobre sanejament al món.
- [GDP_world.xlsx](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?end=2020&start=2020): Dades sobre el PIB de cada país.
- [world-administrative-boundaries.shp](https://public.opendatasoft.com/explore/dataset/world-administrative-boundaries/export/): Fitxer shp amb el límits dels països.

## Eines utilitzades

La visulització s'haprogramat amb R, utilitzant RStudio i RMarkdown, per donar-li el format de *dashboard* s'ha utilitzat la llibreria *flexdashboard*.

* [RStudio](https://posit.co/download/rstudio-desktop/)
* [RMarkdown](https://rmarkdown.rstudio.com/)
* [Flexdashboard](https://pkgs.rstudio.com/flexdashboard/)

Tanmateix, s'han utilitzat altres llibreries que es poden consulta al codi font del fitxer *.Rmd*. Destaca l'ús de la llibreria [crosstalk](https://rstudio.github.io/crosstalk/) que permet millorar la interactivitat de les visualitzacions creades amb R. i de le llibreries [plotly](https://plotly.com/r/) i [leaflet](https://rstudio.github.io/leaflet/) per crear gràfics i mapes interactius.

## Execució
Per executar la visualització des del codi cal obrir el fitxer:
    
    PRA2-CarlesCayuela.Rmd
 
 Les dades estan a la carpeta /data/

## Crèdits
La versió de la llibreria `crosstalk` utilitzada ha estat la desenvolupada per @dmurdoch (https://github.com/dmurdoch/crosstalk) que l'ha millorat per fer-la més compatible amb la llibreria `leaflet`

## Llicència
GNU General Public License v3.0
