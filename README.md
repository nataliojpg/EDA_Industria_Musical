# EDA_Industria_Musical
## Descripción
Este proyecto es un análisis exploratorio de datos (EDA) sobre la industria musical, considerando tendencias en artistas clásicos y contemporáneos, buscando
desmentir sesgos y creencias que tengamos sobre este sector.
Para algunos datos ausentes, se sacaron datos de la web usando Selenium (web scraping)

## Hipótesis
1) Los artistas clásicos son en mayoría originarios del Reino Unido, y los artistas contemporáneos son en mayoría originarios de Estados Unidos
   1.2) Los artistas clásicos británicos tienen promedio más ventas que los clásicos estadounidenses.
   1.3) Los artistas clásicos fueron en mayoría fundados antes del año 2000
   
2) Los géneros más populares eran y son el rock y el pop
   
3) Mientras más bailable sea una canción, menos acústica será.
   3.2)Mientras más energía tenga una canción, más valencia tendrá.
   
## Contenido
- data/: contiene los dataframes utilizados en este análisis
- memoria/: contiene los Jupyter Notebooks donde se hizo el análisis y se sacaron las gráficas, además de un Notebook específicamente para el web scraping
- EDA_presentación : pdf de la presentación en clase

## Herramientas
- Python
- Pandas
- Seaborn
- Matplotlib.Pyplot
- Selenium
