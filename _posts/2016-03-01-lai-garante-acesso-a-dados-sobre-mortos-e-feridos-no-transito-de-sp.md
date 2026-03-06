---
title: "LAI garante acesso a dados sobre mortos e feridos no trânsito de SP"
date: 2016-03-01
layout: post
permalink: /lai-garante-acesso-a-dados-sobre-mortos-e-feridos-no-transito-de-sp/
categories: 
  - "bases-publicas"
tags: 
  - "acesso-a-informacao"
  - "acidentes-de-transito"
  - "acidentes-em-sp"
  - "dados-abertos"
  - "lai"
  - "mortes-no-transito"
coverImage: "ocorrencias-sp.png"
---

Um pedido de informações à Prefeitura de São Paulo com base na [Lei de Acesso à Informação](http://www.acessoainformacao.gov.br/assuntos/conheca-seu-direito/a-lei-de-acesso-a-informacao) ([nº 12.527/2011](http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/lei/l12527.htm "Lei de Acesso à Informação")) garantiu pela primeira vez o acesso legível por máquina a dados sobre mortos e feridos no trânsito do município de São Paulo. Após oito meses e duas negativas seguidas de recursos, a Comissão Municipal de Acesso a Informação [deferiu pedido](http://transparencia.prefeitura.sp.gov.br/acesso-a-informacao/Documents/CMAI/8aATA_CMAI_18_11_15.pdf) em terceira instância e, assim, garantiu a disponibilização de informações sobre as ocorrências que embasaram a formulação do [Relatório Anual de Acidentes Fatais 2014.](http://www.cetsp.com.br/media/395294/relatorioanualacidentesfatais2014.pdf)

O documento original foi divulgado pela Companhia de Engenharia de Tráfego em abril de 2015 em formato PDF, com apresentação de tabelas, números e mapas, mas sem a possibilidade de consulta aos dados que possibilitaram criar tais visualizações. No resultado do pedido, as informações estão organizadas em sete arquivos diferentes reunidos em um arquivo compacto .zip para [download](http://transparencia.prefeitura.sp.gov.br/acesso-a-informacao/Documents/CMAI/bases_de_dados/Acidentes_Fatais_2014.zip). Não é simples entender o que foi disponibilizado.

O arquivo "_Protocolo PR 12024.accdb_" está no formato proprietário [Microsoft Access 2007](https://pt.wikipedia.org/wiki/Microsoft_Access). Ele contém informações sobre ocorrências, veículos e vítimas. Para facilitar a consulta, convertemos essas bases em [formato CSV](https://pt.wikipedia.org/wiki/Comma-separated_values) (campos separados por vírgula) que podem ser abertos no [LibreOffice](https://help.libreoffice.org/Calc/Importing_and_Exporting_CSV_Files/pt-BR) ou no [Excel](https://support.office.com/pt-br/article/Importar-ou-exportar-arquivos-de-texto-txt-ou-csv-e8ab9ff3-be8d-43f1-9d52-b5e8a008ba5c#bmimport_data_from_a_text_file_by_openi), disponibilizamos em nosso [repositório](https://github.com/codigourbano/ocorrencias-fatais-sp) no Github. A partir destes dados geramos tabelas com detalhes sobre as [ocorrências](https://github.com/codigourbano/ocorrencias-transito-pmsp#ocorrencias-2014csv), [vítimas](https://github.com/codigourbano/ocorrencias-transito-pmsp#ocorrencias-fatais-vitimas-2014csv) e [veículos envolvidos](https://github.com/codigourbano/ocorrencias-transito-pmsp#ocorrencias-fatais-veiculos-2014csv). Os significados de cada coluna nas tabelas são descritos no [dicionário de dados](https://github.com/codigourbano/ocorrencias-transito-pmsp#dicion%C3%A1rio-de-dados).

<figure>

[![mapa-ocorrencias](/assets/images/mapa-ocorrencias-286x300-1.png)](/assets/images/mapa-ocorrencias-286x300-1.png)

<figcaption>

_Todas ocorrências de trânsito de SP em 2014_

</figcaption>

</figure>

**O mapa de ocorrências**  
Na resposta ao pedido, a CET-SP também disponibilizou dados em formato [Mapinfo](https://en.wikipedia.org/wiki/MapInfo_Professional), outra plataforma proprietária. Fizemos a conversão com a excelente  biblioteca [ogr2ogr](http://www.gdal.org/ogr2ogr.html) e disponibilizamos em formato shapefile no repositório. Estes dados trazem o georeferenciamento das ocorrências, como ilustra o mapa ao lado.

O cruzamento da localização das colisões e atropelamentos com dados de outras fontes pode ser feito no [QGIS](http://qgis.org), seguindo os passos [deste tutorial](http://geojournalism.org/2014/10/mixing-shapefiles-and-comma-separated-files-in-qgis/). Também no QGIS é possível ver os dados sobre um mapa de ruas do [OpenStreetMap](http://openstreetmap.org) instalando o [plugin OpenLayers](https://plugins.qgis.org/plugins/openlayers_plugin/).  O [manual de instruções](http://docs.qgis.org/2.8/pt_BR/docs/user_manual/plugins/plugins.html) explica como instalar complementos.

O material está disponível em [domínio público](https://github.com/codigourbano/ocorrencias-transito-pmsp#licen%C3%A7a) e sua divulgação tem como objetivo  garantir mais subsídios técnicos no debate de políticas públicas por especialistas, jornalistas, pesquisadores ou qualquer cidadão com acesso à Internet e conhecimento básico de ferramentas de dados abertos.

A imagem abaixo aponta os locais de ocorrências fatais e permite observar que, em 2014, os pontos mais críticos foram as avenidas, em especial as vias marginais dos rios Pinheiros e Tietê. A situação é especialmente delicada no Cebolão, complexo de viadutos em que essas duas vias expressas se encontram.

![](/assets/images/mortes.png)

Abrir dados, neste sentido, é também convidar a população a participar das decisões sobre questões que não são só técnicas, mas também políticas. A redução de velocidade adotada em muitas das avenidas em questão é um exemplo. A decisão gerou polêmica e questionamentos sobre a real necessidade de se desacelerar a cidade. Com o mapa aberto e uma visuação fica fácil identificar a gravidade da situação e onde são os pontos mais críticos.

Esta base de dados é a primeira a ser disponibilizada na [página](http://transparencia.prefeitura.sp.gov.br/acesso-a-informacao/Paginas/CMAI-Comiss%C3%A3o-Municipal-de-Acesso-%C3%A0-Informa%C3%A7%C3%A3o.aspx) da Comissão Municipal de Acesso à Informação, no portal Transparência da Prefeitura Municipal de São Paulo. O precedente abre caminho para que os relatórios de outros anos (2015 e anos anteriores) sejam disponibilizados em formato legível por máquina, possibilitando a criação de mais visualizações especificas.

_Leia também: [Como usar a Lei de Acesso à Informação]({% post_url 2015-02-04-como-usar-a-lei-de-acesso-a-informacao %})_

_\* Evitamos usar "acidentes" de trânsito neste texto, apesar de o termo aparecer inclusive no nome do relatório sobre colisões e atropelamentos em São Paulo. Conforme [explica Daniel Guth](http://abicicletanacidade.blogfolha.uol.com.br/2016/02/15/carros-vs-nao-carros/?cmpid=comptw), diretor de participação da [Ciclocidade:](http://www.ciclocidade.org.br/)_ 

_"atropelamentos ou colisões só podem ser considerados 'acidentes de trânsito' depois da perícia e do processo transitado em julgado. Antes disto devem ser tratados pelo que são, objetivamente: colisões ou atropelamentos. (...) O esvaziamento até a ausência de culpa e o processo de aceitação dos crimes de trânsito como meros acidentes, acontecimentos casuais e fortuitos, levou-nos a uma preocupante apatia que blinda nossa capacidade de indignação com o fato de termos, no Brasil, mais de 50 mil mortos no trânsito todos os anos, segundo dados do DPVAT."_
