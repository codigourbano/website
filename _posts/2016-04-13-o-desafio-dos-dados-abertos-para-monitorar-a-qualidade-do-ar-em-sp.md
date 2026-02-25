---
title: "O desafio dos dados abertos para monitorar a qualidade do ar em SP"
date: 2016-04-13
categories: 
  - "mapas"
  - "sensores"
tags: 
  - "dados"
  - "dados-abertos"
  - "dustduino"
  - "hardware-livre"
  - "jornalismo-de-dados"
  - "mapas-abertos"
  - "poluicao"
  - "qualidade-do-ar"
  - "sao-paulo"
  - "sensores"
coverImage: "IMG_3007-e1460127192753.jpg"
---

A poluição do ar é um dos problemas de saúde mais graves dos nossos tempos. Embora invisíveis, pequenas partículas de poeira - 2,5 micrômetros de diâmetro - são consideradas a quarta maior causa de morte em todo o mundo. A Organização Mundial da Saúde estima que doenças respiratórias são responsáveis por 2,9 milhões de mortes por ano.

No entanto, apesar da gravidade do problema, conseguir informações precisas e localizadas sobre a qualidade do ar é difícil, se não impossível. Mesmo quando fornecidos por governos ou pesquisadores, os dados tendem a representar grandes ambientes, em vez de locais específicos. Na cidade São Paulo, como mostram informações da plataforma [OpenAQ](https://openaq.org/#/sources), existem 19 estações de monitoramento e apenas 9 delas realizam as medições do material particulado 2.5 (PM 2.5).

Com isso em mente, o Código Urbano trabalhou nos últimos 18 meses com a rede [Earth Journalism Network (EJN)](http://earthjournalism.net/) para experimentar o uso de sensores de baixo custo para identificar problemas de poluição do ar em São Paulo. A EJN, projeto da [ONG Internews](https://www.internews.org/) tem trabalhado ao longo dos últimos três anos para envolver pesquisadores e líderes de tecnologia social em lugares como Ulan Bator (Mongólia ), Jacarta (Indonésia) e São Paulo. Em parceria com o engenheiro Matthew Schroyer, a EJN desenvolveu o DustDuino, um sensor de partículas que utiliza um [microprocessador Arduino](https://pt.wikipedia.org/wiki/Arduino) adaptado para enviar dados de qualidade do ar em tempo real para a internet.

O vídeo abaixo conta mais sobre o conceito do projeto e a implementação em São Paulo.

https://vimeo.com/154353030

Em abril de 2014, com o apoio do [Feedback Labs](http://feedbacklabs.org/), o Código Urbano se juntou ao "Make Sense", um consórcio para testar a hipótese de que sensores de baixo custo poderiam ser usados para melhorar a capacidade de resposta à poluição do ar. Um conjunto diversificado de parceiros - incluindo [Frontline SMS](http://frontlinesms.com/), [SimLab](http://simlab.org/), a [Iniciativa Ground Truth](http://groundtruth.in/) e [Development Seed](https://developmentseed.org/) - foram mobilizados para contribuir para a criação de uma rede de sensores piloto em SP.

Nos 18 meses seguintes, os parceiros projetaram e fabricaram um protótipo do DustDuino e desenvolveram o site [OpenDustMap.com](http://opendustmap.com/#search) para exibir leituras dos dispositivos. Além disso, [um manual para o uso do sensor](http://geojournalism.org/tracks/environmental-sensors/) foi escrito.

<figure>

![Poster sobre os efeitos da poluição do ar sobre a saúde e o funcionamento do DustDuino. Por Luiza Peixe/Código Urbano](/assets/images/poster_a3v2-212x300.png)

<figcaption>

Poster sobre os efeitos da poluição do ar sobre a saúde e o funcionamento do DustDuino. Por Luiza Peixe/Código Urbano

</figcaption>

</figure>

Ao implantar o DustDuino em São Paulo, a equipe foi capaz de testar a qualidade dos dados produzidos e também a distribuição de dados através de mensagens SMS e mapas interativos na web. Houve um enorme interesse entre os jornalistas, programadores, ONGs, funcionários municipais e outras partes interessadas. Ao todo, conseguimos distribuir 12 sensores ao redor da cidade e conectá-los em tempo real com nosso mapa interativo.

As lições aprendidas durante o projeto agora estão documentadas em um relatório de autoria de Erica Hagen da iniciativa Ground Truth. Este documento de aprendizagem foi criado através de entrevistas com cada um dos parceiros do consórcio e descreve detalhadamente as nossas estratégias para lidar com problemas comuns a projetos de internet das coisas, tais como o envolvimento do usuário, opções de conectividade, processos de fabricação e os atuais desafios na coleta de dados relevantes.

Além da obtenção de dados confiáveis, um dos objetivos-chave na criação e implantação de sensores foi gerar uma comunidade de usuários que pode tornar a rede eficaz. Por isso com apoio do [Garoa Hacker Clube](https://garoa.net.br/wiki/P%C3%A1gina_principal) organizamos encontros e workshops para distribuir sensores e treinar pessoas em como usá-los.

Apesar do grande interesse por parte do público, os desafios de lidar com essa nova tecnologia não puderam ser superados durante o projeto-piloto. O objetivo final é proporcionar uma utilização fácil e barata dos sensores para permitir a cientistas-cidadãos e comunicadores informar com precisão os problemas da poluição do ar. Mas não chegamos lá ainda. Usar os DustDuinos ainda requer um certo nível de habilidades de programação.

"O projeto fez alguns progressos na criação de um protótipo de sensor confiável de qualidade do ar; sobre como organizar a produção em massa, solucionar problemas de software e hardware; realizar a integração com a API do Frontline SMS e uma integração do back-end com a exibição de dados no front-end do OpenDustMap.com", Hagen conclui no relatório.

"O projeto também tem feito progressos em direção à obtenção de dados estruturados confiáveis ​​e precisos a partir dos sensores e produziu uma extensa documentação que irá permitir uma maior experimentação. No final, entretanto, o consórcio ainda não foi capaz de testar com sucesso o potencial da tecnologia de sensores para o monitoramento por pessoas e comunidades mais afetadas pela degradação ambiental."

**[Leia o relatório completo (em inglês)](https://earthjournalism.net/program-updates/learning-by-doing-dustduino-in-sao-paulo).**

Em 2016, o Código Urbano segue sua parceria com a Earth Journalism Network para aumentar a quantidade dos sensores DustDuinos instalados em São Paulo, bem como melhorar a precisão e qualidade dos dados sobre poluição do ar coletados.  
**  
Leia também**  
[Primeiro sensor independente para monitorar poluição é instalado em SP](https://www.codigourbano.org/primeiro-sensor-independente-para-monitorar-poluicao-e-instalado-em-sp/)
