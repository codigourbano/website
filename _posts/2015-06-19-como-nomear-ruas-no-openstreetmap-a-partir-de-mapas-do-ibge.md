---
title: "Como nomear ruas no OpenStreetMap a partir de mapas do IBGE"
date: 2015-06-19
layout: post
permalink: /como-nomear-ruas-no-openstreetmap-a-partir-de-mapas-do-ibge/
categories: 
  - "mapas"
tags: 
  - "ibge"
  - "mapas"
  - "mapeamento"
  - "openstreetmap"
coverImage: "passo-3.png"
---

O iD, principal ferramenta de edição do [OpenStreetMap](https://www.openstreetmap.org), agora permite a exibição de uma camada de logradouros do IBGE. Com ela é possível saber nomes de ruas da maior parte das áreas urbanas do Brasil. Tal novidade existe graças a um trabalho da [comunidade do OpenStreetMap](https://wiki.openstreetmap.org/wiki/WikiProject_Brazil) de [transformação de arquivos .pdf publicados pelo IBGE para o censo de 2010](https://wiki.openstreetmap.org/wiki/IBGE_Tile_Layer).

Para usar a camada, [abra o editor iD](https://www.openstreetmap.org/edit?editor=id) na região em que quer mapear e clique em “Configurações da imagem de fundo":

<figure class="post-figure-center">
<img src="/assets/images/passo-1.png" width="640" height="445" alt="Captura do editor iD: menu de configurações da imagem de fundo" loading="lazy" />
<figcaption>No iD, abra as configurações da imagem de fundo.</figcaption>
</figure>

Selecione a camada “IBGE Mapa de Setores Urbanos”:

<figure class="post-figure-center">
<img src="/assets/images/passo-2.png" width="640" height="447" alt="Captura do iD: lista de camadas com IBGE Mapa de Setores Urbanos selecionado" loading="lazy" />
<figcaption>Selecione a camada do IBGE na lista.</figcaption>
</figure>

Agora a camada base será parecida com esta:

<figure class="post-figure-center">
<img src="/assets/images/passo-3.png" width="640" height="439" alt="Captura do mapa no iD com sobreposição dos setores urbanos do IBGE" loading="lazy" />
<figcaption>Visualização dos setores urbanos como referência para nomes de vias.</figcaption>
</figure>

Pronto, com este mapa é possível completar nomes de ruas em localidades pouco mapeadas. Confira algumas recomendações para evitar erros:

- Não desenhe geometrias baseando-se apenas nesta camada, pois ela não possui alinhamento correto na maioria dos locais;
- Use a tag <code>source=IBGE</code> nos elementos editados para informar que os dados vêm do IBGE;
- Caso o mapa já contenha informações, verifique se estas vem de fontes melhores do que o IBGE.
