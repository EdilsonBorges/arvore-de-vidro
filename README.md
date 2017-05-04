# Árvore de Vidro 

### Resumo e História do Projeto 

Tudo começou quando estava pensando em desenvolver um sistema de irrigação automático. O projeto iria usar tanques de água, tubos de PVC, [válvula solenóide](https://pt.wikipedia.org/wiki/V%C3%A1lvula_de_controle_direcional_(hidr%C3%A1ulica_e_pneum%C3%A1tica), e um [ESP8266](https://en.wikipedia.org/wiki/ESP8266). 

Depois, novas ideias foram surgindo e pensei em um sistema de aquecimento com garrafas de vidro, pra criar um efeito estufa, e depois usar essa água para outra coisa (a ideia inicial seria "purificar" água de reuso de chuva). Daí vieram várias ideias diferentes, tais como utilizar água de chuva, utilizar garrafas de cerveja, e até gerar eletricidade no futuro, baseando no conceito por trás o Motor de Hero, também conhecido como [Aeolipile](https://www.youtube.com/watch?v=9K_r8BUXoMw).

Pra não ficar na teoria, decidi comprar os materiais e começar a fazer alguma coisa. Nesse projeto, tudo será documentado, desde como as ideias foram surgindo (como vocês podem ver pelos dois parágrafos acima), até a forma de como conectar os materiais, como conseguir, onde comprar, os preços que achei no mercado e até os parâmetros técnicos de projeto. Tudo feito em cima da licença [WTFPL](http://www.wtfpl.net/), então, "faça o que quiser" com as informações que achar aqui. 

### Versão 0.1 - Objetivo: Conseguir fazer a água das garrafas chegar no ponto de uso, pela ação da gravidade.

A ideia aqui é fazer o projeto com materiais fáceis e baratos de encontrar no mercado, tais como tubos de PVC e garrafas de vidro. 

* Foram escolhidas _garrafas de cerveja long neck 330~355 mL_, pelos seguintes motivos: 

- são fáceis de encontrar;
- a maioria tem uma camada colorida escura (verde escuro, marrom), facilitando a criação de efeito estufa;
- são relativamente fáceis de encaixar nos tubos e conexões de PVC;
- são resistentes;
- são pequenas (em média, 3 garrafas conseguem armazenar 1 Litro de água) e assim o peso ficará distribuído em toda a estrutura (considerando aceleração da gravidade de aproximadamente 10m/s² e densidade da água de 1 kg/m³, cada garrafa cheia pesará apenas ~3,3 N, se a mesma ficar totalmente na vertical (em cima do telhado pode diminuir ainda mais) ---> **CALCULAR ESSES PARÂMETROS, e a pressão (F/A) no telhado, para 45º de inclinação**

* Foram escolhidas *conexões de PVC de 3/4" rosqueáveis*, cor branca (para água-fria). Apesar do material PPR ser mais indicado para tubulações de água quente, foi preferido usar PVC por causa do custo baixo. Futuramente, em uma real necessidade (temperatura alta demais) novos materiais serão considerados. Foi escolhida a medida 3/4" pois é a mais fácil de conectar em uma garrafa long neck de cerveja comum. 

* A arquitetura escolhida para construir o sistema foi de [nipeis](http://www.ecivilnet.com/dicionario/o-que-e-nipel.html), Ts e plugues de PVC 3/4", todos rosqueáveis. Foram desconsiderados o uso de tubos de PVC pela dificuldade de cortá-los (geralmente eles vem em barras de 3 metros) e de rosqueá-los, dificultando demais a expansão e modularização do sistema. 

* A concepção/arquitetura para o sistema foi pensada levando em consideração o ambiente de um bar de rock de Goiânia. Assim, o sistema deveria permitir que qualquer pessoa, munida apenas de uma garrafa de cerveja vazia e limpa (poderia limpá-la com a própria água quente do sistema), e um isqueiro, poderia adicionar um nó a mais na árvore de vidro, expandindo-a. Daí nasceu todo o conceito de expansão colaborativa e modularidade do sistema. 

### Construção do sistema

As fotos abaixo ilustram o passo a passo da construção do sistema.

![1 - Garrafa de vidro](/Imagens/1-garrafa-de-vidro.jpg)

1 - Ao utilizar garrafas de vidro temos ao menos 3 vantagens:

1. Baixíssimo custo (pessoas jogam garrafas de cerveja fora todo dia, ainda mais em bares, festas, etc). 
2. Fácil de gerar efeito estufa no interior
3. Sistema modular, em que basta acrescentar uma garrafa, um T e um plugue de PVC para expandir.

![2 - Isqueiro](/Imagens/2-isqueiro.jpg)

2 - O isqueiro é um item que muitas pessoas possuem em bares. Como o projeto foi pensado tendo em mente um bar de rock, uma pessoa poderia adicionar sua garrafa de cerveja recém esvaziada ao sistema, no intervalo de um cigarro e outro, usando seu isqueiro.

![3 - Fita Veda Rosca](/Imagens/3-fita-veda-rosca.jpg)

3 - A fita veda rosca é um item barato e muito útil. Com ela garante-se que a garrafa e as demais junções não irão vazar água, temperatura ou pressão.

![4 - Materiais](/Imagens/4-materiais.jpg)

4 - Acima está a lista de todos os materiais com suas descrições.

![5 - Luva de redução - Frente](/Imagens/5-luva-de-reducao-lateral.jpg)

5 - A luva de redução é usada para reduzir o diâmetro dos Ts de PVC de 3/4" para o diâmetro da válvula solenóide, que é de 1/2". 

![6 - Luva de redução - Cima](/Imagens/6-luva-de-reducao-frente.jpg)

6 - Vista superior da luva de redução.

![7 - T aquecido com garrafa quente](/Imagens/7-T-aquecido.jpg)

7 - Essa figura mostra como ficou o T após ser aquecida a garrafa de vidro com isqueiro e rosqueada nele, quando ainda estava quente.

![8 - válvula solenóide 12V](/Imagens/8-valvula-solenoide.jpg)

8 - A válvula solenóide é um dispositivo que permite a passagem de água ou outro fluido a partir de um comando elétrico ou eletrônico. Existem diversos tipos diferentes de válvula. Essa da imagem utiliza tensão de 12 V, podendo ser alimentada por bateria de carro, e, por ser baixa, não oferece risco às pessoas. Outra razão para a escolha da tensão foi a facilidade de controle, bastando utilizar um transistor darlington, como o TIP122. 

![9 - Esquema versão 0.1](/Imagens/9-esquema-versao-0.1.jpg)

9 - Esquema inicial, mostrando como ficará após encaixar as peças.

![10 - Primeiro plugue conectado - Vista de lado](/Imagens/10-primeiro-plugue-lareral.jpg)

10 - Imagem do primeiro plugue rosqueado, à esquerda.

![11 - Primeiro plugue com veda rosca](/Imagens/11-primeiro-plugue-frente.jpg)

11 - Vista frontal do primeiro pluge rosqueado com fita veda rosca. A quantidade de fita usada foi para dar de duas a 3 voltas na rosca, no sentido oposto ao que a peça seria rosqueada. (Se horária, então deve-se colocar fita veda rosca no sentido anti-horário).

![12 - Teste com água - Plugue horizontal](/Imagens/12-teste-com-agua-horizontal.jpg)

12 - As conexões foram testadas com água. Apesar de ser feito com pressão atmosférica, é um teste razoável para esse primeiro momento.

![13 - Teste com água - Plugue vertical](/Imagens/13-teste-com-agua-vertical.jpg)

13 - Teste com água na vertical, caindo sobre o plugue recém rosqueado.

![14 - Alicate para apertar primeiro nípel](/Imagens/14-alicate-para-nipel.jpg)

14 - O primeiro nípel foi apertado usando alicate, os outros foram conectados usando somente a mão. Como a ideia é que qualquer pessoa pudesse apertar, provavelmente qualquer pessoa não teria um alicate à disposição, e por isso a ideia da construção poder ser feita usando apenas as mãos.

![15 - Esquema esqueleto - Vista de perspectiva](/Imagens/15-estrutura-em-perspectiva.jpg)

15 - Figura mostrando as três conexões acopladas. Duas para as garrafas e uma para a válvula solenóide.

![16 - Teste com água](/Imagens/16-teste-com-agua-estrutura.jpg)

16 - O arranjo acima também foi testado com água.

![17 - Esquentando a boca da garrafa](/Imagens/17-esquentando-garrafa.jpg)

17 - A garrafa foi esquentada com um isqueiro, e depois rosqueada na conexão superior do T. Foram gastos muitos minutos aquecendo e rosqueando a garrafa. O motivo é que a rosca da garrafa de cerveja é totalmente diferente da rosca do T de PVC, e assim, a alta temperatura derrete o T, "forjando" uma conexão compatível para a garrafa de cerveja. O procedimento adotado foi o de aquecer por uns 10 segundos e depois rosquear no T. Retirar e repetir o procedimento, até que a forma da rosca da garrafa passasse para a conexão T de PVC. após assumir a forma, a garrafa foi aquecida novamente, foi passado duas voltas de fita veda rosca na garrafa pré-aquecida e essa foi acoplada na conexão de PVC, torcendo-a até encaixar e ficar firme. A conexão aqui deve ficar bem feita, pois uma vez conectado e passado água, fica extremamente difícil tirar (não devendo nunca ser torcida a garrafa com força, para não quebrá-la na mão). Só foi possível tirar quando eu aqueci o pescoço da garrafa com o isqueiro e fui torcendo devagar.

![18 - Garrafa conectada](/Imagens/18-garrafa-conectada.jpg)

18 - Após o procedimento acima, a garrafa ficou assim.

![19 - Versão 0.1 com rosca](/Imagens/19-esquema-garrafa-pronta.jpg)

19 - Esquema finalizado, faltando somente a válvula solenóide.

![20 - Versão 0.1 - Pronta](/Imagens/20-versao-0.1-finalizada.jpg)

20 - Versão 0.1 Finalizada, com todas as conexões com veda rosca, e válvula solenóide conectada.

### Custos com materiais:

ID | Quantidade |Descrição | Preço unitário | Preço total
--|-----|----------|--------------------|-------|
1 | 3 | T PVC água fria 3/4" rosqueável | R$ 4,00 | R$ 12,00
2 | 2 | Nipel PVC água fria 3/4" | R$ 1,50 | R$ 3,00
3 | 3 | Plugue PVC água fria - 3/4" | R$ 1,50 | R$ 4,50
4 | 1 | Luva de redução 3/4" para 1/2" | R$ 1,00 | R$ 1,00
5 | 1 | Fita veda rosca 10 metros | R$ 3,00 | R$ 3,00
6 | 1 | Isqueiro pequeno | R$ 3,00 | R$ 3,00 
7 | 1 | Válvula solenóide 12 V 40 cm coluna d'água 1/2" | R$ 33,90 | R$ 33,90
8 | 1 | NodeMCU versão 0.9 | R$ 24,90 | R$ 24,90
9 | 1 | Transistor Darlington TIP122 | R$ 0,90
10| 1 | Placa perfurada para montagem 10cmx5cm | R$ 3,00
11| 1 | Regulador de tensão L7805 | R$ 0,90
12| 1 | Diodo 1N5406 3A | R$ 0,30
13| 1 | Borne azul 2 parafusos | R$ 2,00
14| 1 | Borne azul 3 parafusos | R$ 3,25
15| 1 | Sensor de temperatura DS18B20 | R$ 17,50
16| 1 | Fonte chaveada 220/12V 2A | R$ 22,50
17| 1 | Acelerômetro MPU-6050 | R$ 36,00
Total |  |                 |  | R$ 171,60 

* Capacidade de garrafas no momento: 2 
* Capacidade volumétrica: 660 ~ 710 mL
* Custo de expansão (R$/cada garrafa extra): R$ 7,00 (1 nípel + 1 plugue + 1 T)

### Princípio físico:

De acordo com esse link da seção de Física do site StackExchange, [Heat trapped inside car on sunny day](https://physics.stackexchange.com/questions/14185/heat-in-the-car-during-sunny-day), a maior parte da energia do sol está no espectro visível de radiação. Apenas uma pequena parte se encontra na faixa não visível (IR e UV). A energia absorvida é radiada de volta na forma de onda Infravermelha (calor), mas o vidro funciona como um escudo opaco para esse comprimento de onda, fazendo com que o calor se mantenha no interior do veículo/recipiente. A mesma explicação pro "Efeito Estufa".

Dessa forma, a hipótese é que a água no interior da garrafa de vidro vai aquecer (podendo ser usados colimadores espelhados, para aumentar a eficiência) com os raios solares, que por serem a maioria no espectro visível, irão passar o vidro e aquecer a água. O vidro funcionará como um escudo para os raios infravermelhos que queiram sair, mantendo o líquido aquecido. Um jeito simples de fazer colimadores com espelho de aço inoxidável: [DIY Parabolic Through Mirror](https://www.youtube.com/watch?v=St-0HWKAY4k).

Perguntas: 

1. Diante disso, é melhor que a garrafa seja transparente, assim mais raios de sol entrariam (o comprimento de onda da cor verde não seria refletida?)
2. Uma garrafa colorida, ou até mesmo escura, impediria os raios infravermelhos de saírem? Ou, por bloquearem a entrada de raios do sol naquela faixa de cor, demoraria mais para aquecer a mistura? 

- [ ] Fazer testes usando sensores de temperatura conectados diretamente nas garrafas, submetidos a uma mesma incidência (garrafas próximas umas das outras) e monitorar de forma online. Plotar aqui os resultados em forma de gráfico.

De acordo com esse outro link da seção de Física do site StackExchange, [Increase of temperature by sunlight](https://physics.stackexchange.com/questions/68611/how-much-does-sunlight-affect-inside-temperature), a quantidade de energia que entra em um recipiente/sala, é proporcional à área de suas aberturas/janelas, bem como do ângulo de incidência, características do vidro, etc. Dessa forma, os colimadores reflexivos serão bons para aproveitar uma área de incidência maior que o tamanho da garrafa, porém, não podem ser caros demais, como isso aqui: [Ivanpah Solar Power Facility](https://en.wikipedia.org/wiki/Ivanpah_Solar_Power_Facility). Terá que ser um material fácil e leve, e que encaixe por baixo da matriz de garrafas/canos (árvore ou trepadeira de vidro). Pode até ser uma chapa de apoio, e assim facilitar a instalação em telhados, paredes, muros, etc. 

O link ainda diz que a maior parte do aquecimento de ambientes se dá pela incidência solar em superfícies sólidas. Para esse projeto estamos usando um fluido (água), então é preciso ver se funcionaria da mesma forma. 

- [ ] Fazer testes de medição em temperatura em garrafas vazia e com água, e verificar a diferença. Medir em tempo real durante um dia e postar aqui em forma de gráficos os resultados.

### Futuro

- [ ] Descobrir até quantos graus celsius pode chegar a temperatura da água na garrafa 
(Considerando radiação solar de Goiânia de até [5,7kW/m²](http://www.portalsolar.com.br/blog-solar/energia-solar-nas-cidades/energia-solar-em-goiania--go.html))
- [X] Comprar TIP120 e fonte 12V para implementar controlador da válvula
- [X] Achar distribuidores com preço acessível para sensor de temperatura (DS18B20) e de vazão de água (1/2")
- [ ] Desenvolver software que regule pressão e temperatura da água/vapor no interior das garrafas
- [X] Detalhar passo a passo, items 7 a 20.
- [ ] Adicionar novos modelos de nós (folhas de vidro), com sustentação, com subida (milho de vidro)
- [ ] Projetar sistema que possibilite instalação com caixa d'água e telhado


### Novas pesquisas

Pesquisei mais a fundo sobre aquecimento de água, geração de energia com fontes térmicas e termodinâmica em geral e descobri o que já estava descoberto a muito tempo: [Frank Shuman](https://www.youtube.com/watch?v=wHVxw_jNstg) já fez isso em 1912, no Egito, usando uma tecnologia que hoje é conhecida como CSP - [Concentrated Solar Power](https://en.wikipedia.org/wiki/Concentrated_solar_power).

Dessa forma, é possível aquecer uma área pequena com raios solares, utilizando diversos métodos e materiais diferentes, tais como refletores espelhados, lentes, tubos de cobre, tubos pintados de tinta preta, etc. As possibilidades são vastas!

Percebi que um dos maiores gargalos para conseguir aproveitar a luz do Sol com muita eficiente, através de [lentes de Fresnel](https://www.youtube.com/watch?v=drE54ctrHBY), por exemplo, é conseguir seguir o movimento do sol durante todo o dia. Ainda assim isso não é novidade, já que existem diversas formas de fazer isso. Eu escolhi fazer utilizando motores de passo, acelerômetro e 4 LDRs. Seguem as fotos do que eu rabisquei nos últimos dias. Ainda vou organizar todas as informações. 

![21 - Rascunho 1](/Imagens/21-rascunho1.jpg)

![22 - Rascunho 2](/Imagens/22-rascunho2.jpg)

![23 - Rascunho 3](/Imagens/23-rascunho3.jpg)

![24 - Rascunho 4](/Imagens/24-rascunho4.jpg)


### Futuro

- [ ] Fazer primeiro o seguidor de sol com os motores de passo
- [ ] Buscar parcerias para construir o sistema de gerador de vapor e turbina a vapor




