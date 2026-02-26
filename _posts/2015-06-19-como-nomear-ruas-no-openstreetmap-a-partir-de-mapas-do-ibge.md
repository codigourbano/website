---
title: "Como nomear ruas no OpenStreetMap a partir de mapas do IBGE"
date: 2015-06-19
layout: post
categories: 
  - "mapas"
tags: 
  - "ibge"
  - "mapas"
  - "mapeamento"
  - "openstreetmap"
coverImage: "passo-3.png"
---

O iD, principal ferramenta de edição do [OpenStreetMap](http://www.openstreetmap.org), agora permite a exibição de uma camada de logradouros do IBGE. Com ela é possível saber nomes de ruas da maior parte das áreas urbanas do Brasil. Tal novidade existe graças a um trabalho da [comunidade do OpenStreetMap](http://wiki.openstreetmap.org/wiki/WikiProject_Brazil) de [transformação de arquivos .pdf publicados pelo IBGE para o censo de 2010](http://wiki.openstreetmap.org/wiki/IBGE_Tile_Layer).

Para usar a camada, [abra o editor iD](http://www.openstreetmap.org/edit?editor=id) na região em que quer mapear e clique em “Configurações da imagem de fundo":

![](/assets/images/passo-1.png)

Selecione a camada “IBGE Mapa de Setores Urbanos”:

![](/assets/images/passo-2.png)

Agora a camada base será parecida com esta:

![](/assets/images/passo-3.png)

Pronto, com este mapa é possível completar nomes de ruas em localidades pouco mapeadas. Confira algumas recomendações para evitar erros:

- Não desenhe geometrias baseando-se apenas nesta camada, pois ela não possui alinhamento correto na maioria dos locais;
- Use a tag 'source=IBGE' no elementos editados para informar que os dados vem do IBGE;
- Caso o mapa já contenha informações, verifique se estas vem de fontes melhores do que o IBGE.
