---
title: "Sensor livre pretende medir poluição do ar em regiões críticas"
date: 2015-07-17
layout: post
permalink: /sensor-feito-com-tecnologia-livre-pretende-medir-poluicao-do-ar-em-regioes-criticas/
categories:
  - "artigos-analises"
  - "sensores"
tags:
  - "associacao-ecologia-digital"
  - "dustduino-org"
  - "earth-journalismo-network"
  - "garoa-hacker-clube"
  - "largo-da-batata"
  - "mae-dagua"
  - "opendustmap"
  - "rede-infoamazonia"
---

**Por Ana Elisa Santana**, texto originalmente publicado no [Portal EBC](https://www.ebc.com.br/tecnologia/2015/07/sensor-feito-com-tecnologia-livre-pretende-medir-poluicao-do-ar-em-regioes)

Os softwares livres oferecem uma gama de possibilidades e têm sido usados em diversos projetos que facilitam a vida das pessoas. Uma iniciativa está criando uma rede de sensores que vão captar amostras de ar, analisar e informar a qualidade do que estamos respirando nas grandes ou pequenas cidades.

O protótipo do projeto, feito com Arduino, faz uma medição de partículas de combustível fóssil ou de queimadas e informa, em tempo real, as alterações ocorridas ao longo do dia. "Ele consegue detectar partículas de 2,5 e 10 micrômetros, e a leitura de partículas desse tamanho no ar consegue inferir em tempo real se existe queima próximo a uma floresta que represente perigo de devastação, por exemplo", explica Ricardo Guimarães, o Guima, desenvolvedor da Associação Ecologia Digital.

<figure class="post-figure-center">

<a href="/assets/images/sensor_de_qualidade_do_ar_dustduino.jpg">
  <img src="/assets/images/sensor_de_qualidade_do_ar_dustduino.jpg" width="713" height="475" alt="Sensor de qualidade do ar feito com Arduino. Foto: Ana Elisa Santana / Portal EBC — CC BY 3.0" loading="lazy" />
</a>

<figcaption>

Sensor de qualidade do ar feito com Arduino. Foto: Ana Elisa Santana / Portal EBC — Creative Commons CC BY 3.0.

</figcaption>

</figure>

**Mapa colaborativo**

Todas as informações são enviadas para a plataforma [OpenDustMap](https://web.archive.org/web/20151004080753/https://opendustmap.com/) (cópia de 2015 no Internet Archive; o domínio original saiu do ar), onde é possível clicar em cada um dos pontos e ver uma linha do tempo com as medições. A ideia é que o mapa colaborativo cresça, com a participação de pessoas comuns interessadas em medir a qualidade do ar em seus bairros. Para instalar, basta configurar o Wi-Fi e geo-referenciar a posição da sua casa.

O processo de instalação e configuração tem sido ensinado em hackerlabs (oficinas hackeres) realizados no Largo da Batata, em São Paulo, junto com o coletivo Garoa Hacker Clube. É no Largo da Batata, também, que está instalado o primeiro dos protótipos de medição da qualidade do ar. Em uma banca de revista na Avenida Faria Lima, ligada ao sensor, foi instalada uma fita de led que informa os índices de qualidade do ar às pessoas na região.

O sensor é um projeto colaborativo feito com o [sensor DustDuino](https://github.com/MattSchroyer/DustDuino) (documentação histórica no [Public Lab, Internet Archive](https://web.archive.org/web/20150331235310/http://publiclab.org/wiki/dustduino)), que está implementando o software, e a [Earth Journalism Network](https://earthjournalism.net/), que financiou a prototipagem e o desenvolvimento, e a Associação Ecologia Digital, que já tem algumas iniciativas como o Código Urbano.

<div class="embed-youtube">
<iframe src="https://www.youtube.com/embed/02KkpSU-MJg" title="Vídeo: sensor de qualidade do ar (Dustduino / reportagem)" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen loading="lazy"></iframe>
</div>

A primeira etapa do projeto tem dois protótipos já em funcionamento, no Largo da Batata e no Minhocão, em São Paulo, e mais 35 prontos para instalação. O critério utilizado para escolher os locais será a criticidade dos pontos, como avenidas que têm intensa movimentação de veículos.

O custo atual de um equipamento desses é de aproximadamente 100 dólares, incluídos o módulo de qualidade particulado, o Arduino e o Wi-Fi. "É um valor bom se considerar que é um instrumento científico de alta precisão", considera Guima. Ele afirma ainda que o valor tende a diminuir, uma vez que o equipamento deve passar a ser prototipado em larga escala.

Por ser feito em plataforma aberta, as pessoas podem adicionar mais componentes como sensores diferentes para captar CO₂, temperatura, umidade. Assim, ele pode passar a enviar mais dados para a plataforma, de acordo com as necessidades de cada ponto.

**Qualidade da água na Amazônia**

Também está sendo desenvolvido pela Rede Infoamazônia um projeto em que será monitorada a qualidade da água consumida por famílias de 25 comunidades ribeirinhas em Santarém, no Pará. O sensor batizado de Mãe D'água deve ajudar a população da região, que sofre com epidemias relacionadas à falta de estrutura e de saneamento básico na água.

De acordo com Guima, atualmente há análise da água em Santarém apenas duas vezes por ano e, a partir dessas leituras, é atestada a qualidade da água para milhares de pessoas. Esta frequência, segundo ele, é questionável. "A medição pode ser feita em um momento em que a qualidade pode estar muito boa ou muito ruim, e esse resultado acaba valendo por um semestre todo", avalia.

Com o sensor Mãe D'água, também feito com tecnologia livre, a leitura será feita de hora em hora. "Um sensor com tecnologia livre possibilita que um engenheiro que entende de eletrônica acesse o projeto e replique, faça melhorias, ajuste a ferramenta de acordo com a necessidade da região", celebra Guima.

Assim como o sensor de poluição do ar, o Mãe d'água enviará os dados coletados para visualização online, este na plataforma de monitoramento da Infoamazônia. Os moradores da região, por sua vez, vão poder também se cadastrar pra receber as informações por SMS.

**Leia também:** [Primeiro sensor independente para monitorar poluição é instalado em SP]({% post_url 2015-03-26-primeiro-sensor-independente-para-monitorar-poluicao-e-instalado-em-sp %})
