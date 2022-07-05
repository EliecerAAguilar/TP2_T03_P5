# Topicos Especiales 2
## Tarea #03

<div id="badges">
    <a href="https://www.linkedin.com/in/eliecer-aguilar-507/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="https://twitter.com/elieceraguilar3">
      <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
    </a>
    <a href="https://colab.research.google.com/github/eliecer507/TP2_tarea03_p02/blob/main/main.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
    </a>
</div>


<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>


<div>
GeoJSON es	 un	 formato	 estándar	 abierto	 diseñado	 para	 representar	
características	 geográficas	 simples,	 junto	 con	 sus	 atributos	 no	 espaciales.	
Está	basado	en	el	formato	JSON.
Las	características	incluyen	puntos	(por	lo	tanto,	direcciones	y	ubicaciones),	
cadenas	de	líneas	(por	lo	tanto,	calles,	carreteras	y	límites),	polígonos	(países,	
provincias,	 extensiones	 de	 tierra)	 y	 colecciones	 de	 varios	 partes	 de	 estos	
tipos.	
Las	 características	 de	 GeoJSON	 no	 necesitan	 representar	 entidades	 del	
mundo	 físico	 únicamente;	 Las	 aplicaciones	 móviles	 de	 navegación,	 por	
ejemplo,	pueden	describir	su	cobertura	de	servicio	usando	GeoJSON
El	formato	GeoJSON	se	diferencia	de	otros	estándares	GIS	en	que	fue	escrito	
y	mantenido	no	por	una	organización	de	estándares	formal,	sino	por	un	
grupo	de	trabajo	de	desarrolladores	de	Internet.
</div>


## Problema	5.	GeoJSON/Shapefiles desde	Geopandas.


El	California	Open	Data	Portal	(<a href="https://data.ca.gov/en/" target="_blank">https://data.ca.gov/en/ </a>)	es	un	interesante	repositorio	de	datos	gubernamentales	y	
colectados	 por	 los	 usuarios	 particulares,	 sobre	 datos	 como	 Recursos	 naturales,	 Agua	 (recurso	 que	 es	 escaso en	
California,	COVID-19,	Salud	y	Servicios	Humanos,	Economía	y	demografía,	Gobierno	y	Transporte).
Si	usted	Navega	hasta	los	datasets	(<a href="https://data.ca.gov/en/dataset" target="_blank">https://data.ca.gov/en/dataset </a>),	se	dará	cuenta	que	tienen	una	colección de	datos	
en	formato	GeoJSON.


Lo	mismo	puede	hacer	(en	menor	escala)	dentro	del	sitio	del	Ministerio	de	Ambiente	de	Panamá	en	la	sección	de	
geoservicios	(<a href="https://www.sinia.gob.pa/index.php/en/extensions/datos-abiertos-y-geoservicios" target="_blank">https://www.sinia.gob.pa/index.php/en/extensions/datos-abiertos-y-geoservicios </a>)  


En	este	problema	debe:


1. Ubicar	1 dataset de	cada	portal	(es	decir	1	de	California	y	otro	de	Panamá)	que	sea	de	su	interés,	bájelos	y	
léalos	usando	Geopandas


2. Describa	las	columnas	de	cada	uno	de	los dataset   


3. Visualice	ambos geodataframes  


4. Haga	algunas	búsquedas	(filtrando	usando	indexación	booleana vectorizada)	basado	en	la	información	de	las	
columnas	de	los	archivos.   


5. Contextualice	en	un	mapa	de	California,	para	ello	puede	usar	como	“base”	un	mapa	de	OpenStreetMaps.  


6. Muestre	el	mapa	contextualizado	resultante  
