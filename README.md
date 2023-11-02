# intro-qgis
Curso ISA Open Campus [Introdução a QGIS](https://www.isa-opencampus.pt/introducaoQGIS)

* Curso de formação (sem avaliação e sem atribuição de ECTS).
* O formando receberá um Certificado de Curso de Formação.
* É exigida a presença em, pelo menos, 85% do tempo de contacto.

## Ligações para o curso

* [Caderno de apoio](https://isa-ulisboa.github.io/sig/Caderno-aulas-praticas-qgis3_SIG.pdf)
* [Canal Youtube](https://www.youtube.com/@qgis3emportugues)
* [Página oficial Fenix de acesso restrito](https://fenix.isa.ulisboa.pt/courses/cfiqgis-846413499991002). As gravações das sessões estão apenas acessíveis aos formando inscritos no curso e estão no separador *gravacoes_sessoes*
* [Link Zoom para as sessões](https://videoconf-colibri.zoom.us/j/97385541766)
* [Inquérito aos formandos após sessão 5](https://forms.gle/NsX4uj1AcVmAk88G9)
* [Inquérito sobre preferências de tópicos na última semana](respostas_inquerito_ultima_semana.pdf)

## Sessão 1 (2 outubro 2023): início até secção 1.4.8 do caderno de apoio

1. Instalação QGIS
2. Definição da pasta de trabalho e do projeto QGIS
3. Primeiros exemplos, até secção 1.4.8 <<Criar legendas “quantitativas” para um cdg vetorial.>>

Dados para a sessão:
* Dados vetoriais (concelhos de Portugal Continental, linhas de água) e tabela simples:
  - [Download zip file: Conc2016, linhasAgua, VACc](https://github.com/isa-ulisboa/sig/raw/main/IntroQGIS.zip)
* Descarregar o modelo digital de elevações para Portugal Continental (25 m)
  - [Link: SRTM-DEM EPSG:3763, GSD=25m](https://www.fc.up.pt/pessoas/jagoncal/dems/); ou
  - [Link: ALOS-AW3D30 EPSG:3763, GSD=25m](https://www.fc.up.pt/pessoas/jagoncal/dems/), com algumas falhas.

## Sessão 2 (4 de outubro de 2023). Secções 1.5.1 e 1.5.2 do caderno de apoio

* Seleção de features por atributos e por localização (Secção 1.5), exempos com dados conc2016 e linhasAgua:
  - Seleção por atributos: selecção de features usando expressões (1.5.1)
  - Seleção por localização: selecção de features usando relações espaciais (1.5.2)

## Sessão 3 (9 de outubro de 2023). Secções 1.4.9-1.4.12, 1.6, 1.7

* Adicionar conjunto de dados geográficos do tipo matricial (raster) ao projecto
* Tabelas simples (txt, csv,...) e cruzamento de tabelas; Criar novos atributos
* Layout manager para construção de cartas
* Sugestão de exercício: produção de vinho branco por concelho, dados Pordata

## Sessão 4 (11 de outubro de 2023). Secções 2.1 e 2.2

* Acesso interactivo a imagens de muito boa resolução e outros dados “web”.
* Alguns links para conexões XYZ:
  - Google satellite:  https://mt1.google.com/vt/lyrs=y&x={x}&y={y}&z={z}  (permite escolher nível de zoom: máximo=23)
  - Bing: https://t0.tiles.virtualearth.net/tiles/a{q}.jpeg?g=685&mkt=en-us&n=z
  - ESRI imagery: https://services.arcgisonline.com/arcgis/rest/services/World_Imagery/MapServer/tile/{z}/{y}/{x}
  - Stamen Toner: https://stamen-tiles.a.ssl.fastly.net/toner/{z}/{x}/{y}.png
  - Stamen Watercolor: https://stamen-tiles.a.ssl.fastly.net/watercolor/{z}/{x}/{y}.jpg
  - OpenStreetMap: https://tile.openstreetmap.org/{z}/{x}/{y}.png
* Plugin para acesso a Basemaps:
  - Instalar Plugin QuickMapServices. Sugestão: depois de instalar o plugin, abrir no menu "Web" e escolher "Settings" e "More services" para instalar o "Contributed pack" de basemaps.
* Exercício de edição para objectos vetoriais do tipo “linha”: criar novo conjunto de dados geográficos, digitalização, "snapping", "vertex tool".


## Sessão 5 (16 de outubro de 2023). Secções 2.3 e 2.4

* Leitura de dados GNSS em QGIS: animação em QGIS usando o atributo temporal do ficheiro gpx criado pela aplicação móvel (e.g. A-GPS Tracker ou Gaia GPS)
* Criação e edição de dados geográficos do tipo polígono; "advanced digitizing toolbar"

## Sessão 6 (18 de outubro de 2023). Secções 3.1, 3.2, 3.3.1

* Discussão do problema de agregação e visualização dos dados ICNF sobre localizações de ninhos de vespa asiática
* Propriedade "digitizing" para controle de features inválidas e erros topológicos na criação de dados geográficos: ver [video](https://www.youtube.com/watch?v=0cgA8yj5Wyg)
* Análise espacial para dados vetoriais: descarregar os dados para o exercício dos repositórios seguintes:
  - Tabelas simples [Download zip file: ProtRV e ProdS](https://github.com/isa-ulisboa/sig/raw/main/analise_espacial_cascais/tabelas_simples_cascais.zip)
  - [Link: Carta dos Solos](https://snisolos.dgadr.gov.pt/downloads) no site da DGADR
  - Rede estradas (roads), linhas de água (waterways), etc [Dados OpenStreetMap para Portugal](https://download.geofabrik.de/europe/portugal.html)
  - CAOP: Carta Administrativa Oficial de Portugal no [Link: Registo Nacional de dados geográficos/SNIG](https://snig.dgterritorio.gov.pt/rndg/srv/por/catalog.search#/home)
  - COS: Carta de Uso e Ocupação do Solo no [Link: Registo Nacional de dados geográficos/SNIG](https://snig.dgterritorio.gov.pt/rndg/srv/por/catalog.search#/home)
* Caso não seja possível obter os dados geográficos nos links acima, pode usar unicamente as tabelas simples e os 5 conjuntos de dados geográficos que pode obter nos links abaixo:
  - Tabelas simples [Download zip file: ProtRV e ProdS](https://github.com/isa-ulisboa/sig/raw/main/analise_espacial_cascais/tabelas_simples_cascais.zip)
  - [Download zip file: LAgua, RedeViaria, CartaSolos, UsoSolos, LimConc](https://github.com/isa-ulisboa/sig/raw/main/analise_espacial_cascais/dados_geog_input_cascais.zip) já pré-processados.
* Resolução de problemas de validade de features com "fix geometries"

## Sessão 7 (23 de outubro de 2023). Secções 3.2, 3.3, 3.4, 2.4.5, 2.4.6

* [Diagrama de operações](diagrama_cascais-COS-OSM-2023.jpg) para o problema de análise espacial: zonagem no concelho de  Cascais
* Criação de uma tabela simples (e.g. notepad, Excel, ...) e importação em QGIS; Cálculo do rendimento total a partir da certa de ocupação do solo da Tapada da Ajuda (Secções 2.4.5 e 2.4.6)
  
## Sessão 8 (25 de outubro de 2023). Secções 1.6.5 e 4.5

* Criar mapa da produção de vinho branco por concelho, dados Pordata (Secção 1.6.5). Acesso aos dados: [dados Pordata ao nível do município](https://www.pordata.pt/Municipios/Produ%c3%a7%c3%a3o+de+vinho+por+cor-975).
* Análise com dados raster: determinar perdas de eucalipto no concelho de manteigas entre 2018 e 2022 usando a COSc (raster) para a ocupação do solo e a CAOP (vetorial) para delimitar o concelho [diagrama de operações](diagrama_cosc_eucalipto_manteigas.pdf). Este exercício é semelhante ao exercício 4.5 do Caderno de Apoio.
* Inquérito: [alguns tópicos possíveis para a última semana do curso](https://forms.gle/Hs93LczkagzShHPa9)

## Sessão 9 (30 de outubro de 2023). Secção 7

* Conclusão do exercício sobre dados raster da sessão anterior;
* Imagens multiespectrais (7 bandas) Landsat-8 OLI para a zona do Alqueva:
  - [Download zip file: Imagem de 15 de maio 2014](https://github.com/isa-ulisboa/sig/blob/578f05a9bb761e99d6e487763994afd93fed68da/LC82030332014151.zip)
  - [Download zip file: Imagem de 1 de junho 2014](https://github.com/isa-ulisboa/sig/blob/578f05a9bb761e99d6e487763994afd93fed68da/LC82030332014167.zip)

Nota: acesso a imagens de satélite:
* Para descarregar imagens de satélite Sentinel, disponíveis desde 2016, aconselha-se fazer a instalação de SNAP <<ESA Sentinel Applications Platform, or [SNAP](https://step.esa.int/main/toolboxes/snap/), is a free and open toolbox for processing data products from numerous satellite missions such as the EU’s Copernicus Sentinel-1, Sentinel-2 and Sentinel-3, as well as ESA’s SMOS mission, and ‘Third Party Missions’.>>
* Uma alternativa para imagens Sentinel é o [browser](https://dataspace.copernicus.eu/browser/). Exige registo em Copernicus.
* O site [EarthData](https://www.earthdata.nasa.gov/) da NASA permite aceder e descarregar muitos tipos de imagens de satélite, incluindo Landsat

## Sessão 10 (2 de novembro de 2023). Secção 6.4

* Análise do relevo:
  - Montejunto: [Download zip file: Curvas de nível, pontos cotados, linhas de água, linhas de festo, EPSG:3763](https://github.com/isa-ulisboa/sig/blob/main/representacao_terreno_montejunto_3763.zip)
  - Descarregar o modelo digital de elevações para Portugal Continental (25 m) [Link: SRTM-DEM EPSG:3763, GSD=25m](https://www.fc.up.pt/pessoas/jagoncal/dems/)
  - [Diagrama de operações para o problema](diagrama_montejunto_sessao_10.pdf)
