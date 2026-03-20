---
title: "Baixe informações de locais isentos de rodízio pela SABESP em formato aberto"
date: 2015-10-16
layout: post
permalink: /baixe-em-formato-aberto-informacoes-de-locais-isentos-de-rodizio-pela-sabesp/
categories: 
  - "bases-publicas"
tags: 
  - "dados-abertos"
  - "formatos"
  - "raspagem-de-dados"
  - "scraping"
---

Após [reportagem](https://ultimosegundo.ig.com.br/brasil/seca/2015-10-15/sabesp-divulga-lista-de-locais-que-estao-livres-de-rodizio-em-sao-paulo.html) do iG, a SABESP informou quais são os locais isentos de rodízio e que contam com abastecimento prioritário em caso de falta d'água. O formato de publicação escolhido foi o [PDF](https://en.wikipedia.org/wiki/Portable_Document_Format), que é usado para garantir que um documento seja visualizado da mesma maneira em diferentes plataformas, mas, apesar de bastante útil para a distribuição de documentos, não é adequado a dados estruturados.

Um conjunto de dados só pode ser considerado aberto, segundo [diferentes](https://br.okfn.org/dados-abertos/) [definições](https://dados.gov.br/dados-abertos/), se estiver em um formato legível por máquina, pois assim poderá ser importado a bancos de dados ou aberto em programas de edição. Quando um dado é publicado exclusivamente em PDF, a única possibilidade de extração de dados é via _raspagem de dados_. Traduzido do termo inglês _[data scraping](https://en.wikipedia.org/wiki/Data_scraping)_, é a técnica de extração de dados a partir de documentos legíveis a humanos. Uma excelente ferramenta de extração de arquivos PDF é o [Tabula](https://tabula.technology), que tem [código aberto](https://github.com/tabulapdf/tabula).

Após importar um PDF ao programa, é possível marcar as áreas onde estão posicionadas as tabelas que serão processadas, como na imagem:

<figure>

<a href="/assets/images/Captura-de-tela-2015-10-16-15.29.14.png">
  <img src="/assets/images/Captura-de-tela-2015-10-16-15.29.14-1024x637.png" alt="Seleção de tabelas no Tabula" />
</a>

<figcaption>

Seleção de tabelas no Tabula

</figcaption>

</figure>

O Tabula não pode extrair automaticamente dados de todas as páginas do arquivo distribuído pela SABESP, então o processo de raspagem foi repetido para cada uma delas. O programa exporta em [formato CSV](https://tools.ietf.org/html/rfc4180), adequado a dados estruturados e legível por praticamente todos software de edição e linguagens de programação.

Links para os dados:

- [equipamentos-essenciais.csv](https://github.com/codigourbano/equipamentos-essenciais/raw/master/equipamentos-essenciais-sp.csv)
- [visualização em formato tabela](https://github.com/codigourbano/equipamentos-essenciais/blob/master/equipamentos-essenciais-sp.csv)
- [repositório do Github](https://github.com/codigourbano/equipamentos-essenciais)
