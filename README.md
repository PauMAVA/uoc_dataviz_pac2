# uoc_dataviz_pac2
Aquest projecte està creat com a part de la PAC2 de l'assignatura de Visualització de Dades a la UOC.

## Navegació

|Tècnica|Títol|
|---|---|
| [Bubble Packing](https://paumava.github.io/uoc_dataviz_pac2/results/bubblepacking.html) | Sòl Urbà Consolidat en Hectàrees en el 2023 |
| [Choropleth Map](https://paumava.github.io/uoc_dataviz_pac2/results/choropleth.html) | PIB per càpita per província de l'estat Espanyol en el 2021 |
| [Ridgeline Plot](https://paumava.github.io/uoc_dataviz_pac2/results/ridgeplot.html) | Estat dels embassaments d'aigua a Catalunya durant el 2023 |

## Requeriments
Per executar aquest projecte, es poden seguir les següents instruccions.

```
python -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
jupyter lab
```

## Tècniques Utilitzades

### Bubble Packing
El Bubble Packing és una tècnica de visualització de dades que mostra la jerarquia d'elements amb cercles empaquetats que representen diferents valors. Aquesta tècnica és útil per a visualitzar agrupacions i relacions de dades.

S'ha realitzat un anàlisi del Sòl Urbà Consolidat en Hectàrees en el 2023.

- [Dades del mapa urbanístic de Catalunya](https://analisi.transparenciacatalunya.cat/Urbanisme-infraestructures/Dades-del-mapa-urban-stic-de-Catalunya/epsm-zskb/about_data)
- [Exemple de visualització amb R](https://r-graph-gallery.com/circle-packing.html)
- [Documentació de Circle Packing en Python](https://python-graph-gallery.com/circular-packing-1-level-hierarchy/)

### Choropleth Map
El Choropleth Map és un mapa on les àrees geogràfiques estan ombrejades o acolorides en funció del valor d'una variable. Aquest tipus de mapa és especialment efectiu per mostrar variacions geogràfiques en una regió o país.

S'ha realitzat un anàlisi del PIB per càpita per província de l'estat Espanyol en el 2021.

- [INE – Estadístiques oficials d'Espanya](https://ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736167628&idp=1254735576581&menu=resultados)
- [GeoJSON amb les províncies d'Espanya](https://github.com/codeforgermany/click_that_hood/blob/main/public/data/spain-provinces.geojson)
- [Documentació de Choropleth Map](https://datavizcatalogue.com/methods/choropleth.html)
- [Guia de Choropleth Map amb Plotly](https://plotly.com/python/choropleth-maps/)

### Ridgeline Plot
El Ridgeline Plot és una representació gràfica que mostra distribucions de dades en diverses categories amb corbes que es superposen. Aquesta tècnica és ideal per observar variacions i tendències en dades temporals o categòriques.

S'ha realitzat un anàlisi de l'estat dels embassaments d'aigua a Catalunya durant el 2023.

- [Dades d'aigua als embassaments de Catalunya](https://analisi.transparenciacatalunya.cat/Medi-Ambient/Quantitat-d-aigua-als-embassaments-de-les-Conques-/gn9e-3qhr/about_data)
- [Explicació de Ridgeline Plot](https://www.data-to-viz.com/graph/ridgeline.html)
- [Llibreria per a fer Ridgeplot en Python](https://github.com/tpvasconcelos/ridgeplot)
### Altres
Per crear la pàgina de documentació del projecte amb GitHub Pages:

- [GitHub Pages – Crear una pàgina de projecte](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
