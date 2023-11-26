---
description: Matthew O. Jackson, Stanford University
---

# Teoria dos Jogos

Ao enquadrar a análise, algumas questões tornam-se importantes. Primeiro, quem são os jogadores? Podem ser pessoas, empresas, organizações, governos, etnias grupos, e assim por diante. Em segundo lugar, quais ações estão disponíveis para eles? Todas as ações que os jogadores podem levar que possam afetar os pagamentos de qualquer jogador devem ser listados. Em terceiro lugar, qual é o momento das interações? As ações são tomadas simultaneamente ou sequencialmente? São interações repetido? A ordem de jogo também é importante.&#x20;

Mover-se atrás de outro jogador pode dar ao jogador i uma vantagem de saber o que o outro jogador fez; também pode colocar o jogador i em um desvantagem em termos de tempo perdido ou capacidade de realizar alguma ação.

Que informações fazem diferentes jogadores têm quando realizam ações? Quarto, quais são os retornos para os vários jogadores como resultado da interação? Determinar os retornos envolve estimar os custos e benefícios de cada conjunto potencial de escolhas por todos os jogadores. Em muitas situações pode ser mais fácil estimar os pagamentos para alguns jogadores (como você) do que para outros, e pode não estar claro se outros jogadores também estão pensando estrategicamente. Esta consideração sugere que o cuidado atenção deve ser dada a uma análise de sensibilidade. Depois de enquadrar a situação, podemos olhar da perspectiva de diferentes jogadores para analisar quais ações são ideais para eles. Existem vários critérios que podemos usar.

## Definição Formal da teoria dos Jogos

Comecemos com uma representação padrão de um jogo, que é conhecido como jogo de forma normal, ou jogo de forma estratégica:

• O conjunto de jogadores é N = {1, . . . , n}.&#x20;

• O jogador i tem um conjunto de ações, ai , disponíveis. Estes são geralmente referidos como estratégias puras. 3 Este conjunto pode ser finito ou infinito.

• Seja a = a1 × · · · × an o conjunto de todos os perfis de estratégias ou ações puras, com um elemento genérico denotado por a = (a1, . . . , an).

Existem muitos jogos que podem ter diferentes descrições que os motivam, mas têm uma forma normal semelhante em termos dos aspectos estratégicos do jogo. Outro exemplo do O mesmo jogo que o dilema dos prisioneiros é conhecido como duopólio de Cournot.&#x20;

A história é do seguinte modo. Duas empresas produzem bens idênticos. Cada um deles tem dois níveis de produção, alta ou baixo. Se produzirem em alta produção, terão muitos produtos para vender, enquanto em baixa produção, eles têm menos para vender. Se eles cooperarem, eles concordam em cada um produzir em baixa produção. Nesse caso, o produto é raro e tem um preço muito alto no mercado, e cada um deles obtém um lucro de 4. Se cada um produzir em alta produção (ou defeito), então eles vão baixar o preço e, mesmo que vendam mais mercadorias, o preço cai o suficiente para reduzir seus lucros totais para 2 cada. Se um desertar e o outro cooperar, então o preço está em uma faixa intermediária. A empresa com maior produção vende mais bens e obtém um lucro maior de 6, enquanto a empresa com produção menor apenas cobre seus custos e ganha um lucro de 0



## Estrategias dominantes

```
As estratégias dominantes são poderosas tanto do ponto de vista analítico quanto do jogador.
perspectiva. Um indivíduo não precisa fazer nenhuma previsão sobre o que os outros jogadores
pode fazer, e ainda tem uma melhor estratégia bem definida.

No dilema dos prisioneiros, é fácil verificar que cada jogador tem uma posição estritamente dominante.
estratégia para desertar - isto é, confessar à polícia e concordar em testemunhar. Então, se usarmos dominante
estratégias para prever o jogo, então a única previsão é que cada jogador irá desertar, e
ambos os jogadores se saem pior do que nas estratégias alternativas em que nenhum deles falha. Um basico
A lição do dilema dos prisioneiros é que os incentivos individuais e o bem-estar geral não precisam
coincidir. Os dois jogadores acabam indo para a cadeia por 2 anos, mesmo sabendo que teriam
ido para a prisão por apenas 1 ano se nenhum deles tivesse desertado. 

O problema é que eles não podem confiar
uns aos outros para cooperar: não importa o que o outro jogador faça, é melhor um jogador desertar.
Observe que esta análise pressupõe que todas as informações relevantes de pagamento estão incluídas no
função de pagamento. Se, por exemplo, um jogador teme represálias por confessar e testemunhar, então
que devem ser incluídos nos pagamentos e podem alterar os incentivos do jogo. Se o
jogador se preocupa com quantos anos o outro jogador passa na prisão, então isso pode ser escrito
também na função payoff.
Quando existem estratégias dominantes, elas tornam a análise da teoria dos jogos relativamente fácil.
No entanto, tais estratégias nem sempre existem, e então podemos nos voltar para as noções de equilíbrio.
```

## Equilibrio de Nash

Um equilíbrio de Nash de estratégia pura é um perfil de estratégias tal que a estratégia de cada jogador é a melhor resposta (resulta no maior retorno disponível) contra as estratégias de equilíbrio dos outros jogadores.
