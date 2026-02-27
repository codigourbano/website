---
title: "Raspador de dados facilita acesso para consultas ao CEP"
date: 2015-05-11
layout: post
categories: 
  - "liberteocep"
  - "bases-publicas"
tags: 
  - "liberteocep"
  - "cep-scraper"
  - "ceps"
  - "consulta-cep"
  - "correios"
  - "json"
  - "lai"
  - "qual-o-cep"
  - "raspador"
---

**Por Daniel Santini, Vitor George e Miguel Peixe**

[![liberte](/assets/images/liberte.png)](/assets/images/liberte.png)Em março, ao explicar [por que o CEP deve ser tratado como informação pública](/2015/03/12/por-que-o-cep-deve-ser-tratado-como-informacao-publica/), o Código Urbano apresentou um panorama de diferentes pedidos de abertura de dados feitos a partir da [Lei de Acesso à Informação.](/2015/02/04/como-usar-a-lei-de-acesso-a-informacao/) Apesar de posicionamentos favoráveis por parte da Controladoria-Geral da União, as solicitações não avançaram e, os Correios decidiram seguir fornecendo ao público em geral apenas acesso limitado a base de dados pública. A consulta de CEPs hoje só pode ser feita por meio de um [sistema bastante simples](http://www.buscacep.correios.com.br/), que não permite baixar dados e onde é possível fazer somente uma busca por vez.

A base completa segue fechada, mas a gente preparou um raspador, que pode ajudar desenvolvedores que precisam fazer consultas de endereço no sistema dos Correios a partir de números de CEPs. Trata-se do CEP Scraper, um robozinho simpático, que raspa as informações do [BuscaCEP](http://www.buscacep.correios.com.br/) e as devolve em formato JSON, algo que pode ser especialmente útil para os que usam javascript que queiram raspar dados atualizados do CEP. Disponibilizamos este raspador em dois repositórios diferentes:

[https://www.npmjs.com/package/cep-scraper](https://www.npmjs.com/package/cep-scraper)

[https://github.com/codigourbano/cep-scraper](https://github.com/codigourbano/cep-scraper)

_Não custa lembrar que o uso comercial de tais informações não é permitido. A [Lei Postal](http://www.planalto.gov.br/ccivil_03/leis/L6538.htm) prevê apenas liberdade para a divulgação sem fins comerciais, conforme o artigo 15: § 3º - É facultada a edição de lista de endereçamento postal sem finalidade comercial e de distribuição gratuita, conforme disposto em regulamento._

Por fim, vale lembrar também que o CEP é apenas um código numérico vinculado a um endereço físico (que pode ser uma rua, um bairro ou uma área) e não envolve o nome de moradores ou algo assim, sendo que sua divulgação não implica em violação de privacidade. E que no mundo todo existem ações para libertar as bases de CEPs que ainda se encontram fechadas, iniciativas que ganham força justamente pelo caráter público de tais dados.

#LiberteoCEP
