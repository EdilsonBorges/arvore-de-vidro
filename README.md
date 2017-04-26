# Árvore de Vidro 

### Resumo e História do Projeto 

Tudo começou quando estava pensando em desenvolver um sistema de irrigação automático. O projeto iria usar tanques de água, tubos de PVC, válvula solenóide, e um ESP8266. 

Depois, novas ideias foram surgindo e pensei em um sistema de aquecimento com garrafas de vidro, pra criar um efeito estufa, e depois usar essa água para outra coisa (a ideia inicial seria "purificar" água de reuso de chuva). Daí vieram várias ideias diferentes, tais como utilizar água de chuva, utilizar garrafas de cerveja, e até gerar eletricidade no futuro, baseando no conceito por trás o Motor de Hero, também conhecido como [Aeolipile](https://www.youtube.com/watch?v=WLeOBITkknk).

Pra não ficar na teoria, decidi comprar os materiais e começar a fazer alguma coisa. Nesse projeto, tudo será documentado, desde como as ideias foram surgindo (como vocês podem ver pelos dois parágrafos acima), até a forma de como conectar os materiais, como conseguir, aonde comprar, os preços que achei no mercado e até os parâmetros técnicos de projeto. Tudo feito em cima da licença WTFPL, então, "faça o que quiser" com as informações que achar aqui. 

### Materiais empregados - versão 0.1 - Conseguir fazer a água das garrafas chegar no ponto de uso, pela ação da gravidade.

O objetivo inicial é conseguir fazer o projeto com materiais fáceis e baratos de encontrar no mercado, tais como tubos de PVC e garrafas de vidro. 

* Foram escolhidas _garrafas de cerveja long neck 330~355 mL_, porque são fáceis de encontrar, porque a maioria tem uma camada colorida escura (verde escuro, marrom), facilitando a criação de efeito estufa, porque são relativamente fáceis de encaixar nos tubos e conexões de PVC, porque são resistentes, e porque são pequenas (em média, 3 garrafas conseguem armazenar 1 Litro de água) e assim o peso ficará distribuído em toda a estrutura (considerando aceleração da gravidade de aproximadamente 10m/s² e densidade da água de 1 kg/m³, cada garrafa cheia pesará apenas ~3,3 N, se a mesma ficar totalmente na vertical (em cima do telhado pode diminuir ainda mais) ---> **CALCULAR ESSES PARÂMETROS, e a pressão (F/A) no telhado, para 45º de inclinação**

* Foram escolhidas *conexões de PVC de 3/4" rosqueáveis*, cor branca (para água-fria). Apesar do material PPR ser mais indicado para tubulações de água quente, foi preferido usar PVC por causa do custo baixo. Futuramente, em uma real necessidade (temperatura alta demais) novos materiais serão considerados. Foi escolhida a medida 3/4" pois é a mais fácil de conectar em uma garrafa long neck de cerveja comum. 

* A arquitetura escolhida para construir o sistema foi de nipeis, Ts e plugues de PVC 3/4", todos rosqueáveis. Foram desconsiderados o uso de tubos de PVC pela dificuldade de cortar os tubos (geralmente eles vem em barras de 3 metros), de rosqueá-los, dificultando demais a expansão e modularização do sistema. 

* A concepção/arquitetura para o sistema foi pensada levando em consideração o ambiente de um bar de rock de Goiânia. Assim, o sistema deveria permitir que qualquer pessoa, munida apenas de uma garrafa de cerveja vazia e limpa (poderia limpá-la com a própria água quente do sistema), e um isqueiro, poderia adicionar um nó a mais na árvore de vidro, expandindo-a. Daí nasceu todo o conceito de expansão colaborativa e modularidade do sistema. 

### Construção do sistema

As fotos abaixo ilustram o passo a passo da construção do sistema.

![1 - Garrafa de vidro](/Imagens/1-garrafa-de-vidro.jpg)

Ao utilizar garrafas de vidro temos ao menos 3 vantagens:

1. Baixíssimo custo (pessoas jogam garrafas de cerveja fora todo dia, ainda mais em bares, festas, etc). 
2. Fácil de gerar efeito estufa no interior
3. Sistema modular, em que basta acrescentar uma garrafa, um T e um plugue de PVC para expandir.

![2 - Isqueiro](/Imagens/2-isqueiro.jpg)

O isqueiro é um item que muitas pessoas possuem em bares. Como o projeto foi pensado tendo em mente um bar de rock, uma pessoa poderia adicionar sua garrafa de cerveja recém esvaziada ao sistema, no intervalo de um cigarro e outro, usando seu isqueiro.

![3 - Fita Veda Rosca](/Imagens/3-fita-veda-rosca.jpg)

A fita veda rosca é um item barato e muito útil. Com ela garante-se que a garrafa e as demais junções não irão vazar água, temperatura ou pressão.

![4 - Materiais](/Imagens/4-materiais.jpg)

Acima está a lista de todos os materiais com suas descrições.

![5 - Luva de redução - Frente](/Imagens/5-luva-de-reducao-lateral.jpg)

A luva de redução é usada para reduzir o diâmetro dos Ts de PVC de 3/4" para o diâmetro da válvula solenóide, que é de 1/2". 

![6 - Luva de redução - Cima](/Imagens/6-luva-de-reducao-frente.jpg)

Vista superior da luva de redução.

![7 - T aquecido com garrafa quente](/Imagens/7-T-aquecido.jpg)

![8 - válvula solenóide 12V](/Imagens/8-valvula-solenoide.jpg)

![9 - Esquema versão 0.1](/Imagens/9-esquema-versao-0.1.jpg)

![10 - Primeiro plugue conectado - Vista de lado](/Imagens/10-primeiro-plugue-lareral.jpg)

![11 - Primeiro plugue com veda rosca](/Imagens/11-primeiro-plugue-frente.jpg)

![12 - Teste com água - Plugue horizontal](/Imagens/12-teste-com-agua-horizontal.jpg)

![13 - Teste com água - Plugue vertical](/Imagens/13-teste-com-agua-vertical.jpg)

![14 - Alicate para apertar primeiro nípel](/Imagens/14-alicate-para-nipel.jpg)

![15 - Esquema esqueleto - Vista de perspectiva](/Imagens/15-estrutura-em-perspectiva.jpg)

![16 - Teste com água](/Imagens/16-teste-com-agua-estrutura.jpg)

![17 - Esquentando a boca da garrafa](/Imagens/17-esquentando-garrafa.jpg)

![18 - Garrafa conectada](/Imagens/18-garrafa-conectada.jpg)

![19 - Versão 0.1 com rosca](/Imagens/19-esquema-garrafa-pronta.jpg)

![20 - Versão 0.1 - Pronta](/Imagens/20-versao-0.1-finalizada.jpg)

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
Total |  |                 |  | R$ 85,30 

* Capacidade de garrafas no momento: 2 
* Capacidade volumétrica: 660 ~ 710 mL
* Custo de expansão (R$/cada garrafa extra): R$ 7,00 (1 nípel + 1 plugue + 1 T)

### Princípio físico:

De acordo com esse link da seção de Física do site StackExchange, [Heat trapped inside car on sunny day](https://physics.stackexchange.com/questions/14185/heat-in-the-car-during-sunny-day), a maior parte da energia do sol está no espectro visível de radiação. Apenas uma pequena parte se encontra na faixa não visível (IR e UV). A energia absorvida é radiada de volta na forma de onda Infravermelha (calor), mas o vidro funciona como um escudo opaco para esse comprimento de onda, fazendo com que o calor se mantenha no interior do veículo/recipiente. A mesma explicação pro "Efeito Estufa".

Dessa forma, a hipótese é que a água no interior da garrafa de vidro vai aquecer (podendo ser usados colimadores espelhados, para aumentar a eficiência) com os raios solares, que por serem a maioria no espectro visível, irão passar o vidro e aquecer a água. O vidro funcionará como um escudo para os raios infravermelhos que queiram sair, mantendo o líquido aquecido. 

Perguntas: 

1. Diante disso, é melhor que a garrafa seja transparente, assim mais raios de sol entrariam (o comprimento de onda da cor verde não seria refletida?)
2. Uma garrafa colorida, ou até mesmo escura, impediria os raios infravermelhos de saírem? Ou, por bloquearem a entrada de raios do sol naquela faixa de cor, demoraria mais para aquecer a mistura? 

- [ ] Fazer testes usando sensores de temperatura conectados diretamente nas garrafas, submetidos a uma mesma incidência (garrafas próximas umas das outras) e monitorar de forma online. Plotar aqui os resultados em forma de gráfico.

De acordo com esse outro link da seção de Física do site StackExchange, [Increase of temperature by sunlight](https://physics.stackexchange.com/questions/68611/how-much-does-sunlight-affect-inside-temperature), a quantidade de energia que entra em um recipiente/sala, é proporcional à área de suas aberturas/janelas, bem como do ângulo de incidência, características do vidro, etc. Dessa forma, os colimadores reflexivos serão bons para aproveitar uma área de incidência maior que o tamanho da garrafa, porém, não podem ser caros demais, como isso aqui: [Ivanpah Solar Power Facility](https://en.wikipedia.org/wiki/Ivanpah_Solar_Power_Facility). Terá que ser um material fácil e leve, e que encaixe por baixo da matriz de garrafas/canos (árvore ou trepadeira de vidro). Pode até ser uma chapa de apoio, e assim facilitar a instalação em telhados, paredes, muros, etc. 

O link ainda diz que a maior parte do aquecimento de ambientes se dá pela incidência solar em superfícies sólidas. Para esse projeto estamos usando um fluido (água), então é preciso ver se funcionaria da mesma forma. 

- [ ] Fazer testes de medição em temperatura em garrafas vazia e com água, e verificar a diferença. Medir em tempo real durante um dia e postar aqui em forma de gráficos os resultados.

### Futuro

- [ ] Descobrir até quantos graus celsius pode chegar a temperatura da água na garrafa (radiação solar de Goiânia de 700 a 1000 W/m²)
- [ ] Comprar TIP120 e fonte 12V para implementar controlador da válvula
- [ ] Achar distribuidores com preço acessível para sensor de temperatura (DS18B20) e de vazão de água (1/2")
- [ ] Desenvolver software que regule pressão e temperatura da água/vapor no interior das garrafas
- [ ] Detalhar passo a passo, items 7 a 20.
- [ ] Adicionar novos modelos de nós (folhas de vidro), com sustentação, com subida (milho de vidro)
- [ ] Projetar sistema que possibilite instalação com caixa d'água e telhado

