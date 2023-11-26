# Modelo de Segregação de Schelling

O Modelo de Segregação de Schelling, também conhecido como modelo de segregação de Schelling ou modelo de segregação de Schelling, é um modelo computacional que explora como as preferências individuais podem levar ao surgimento de comunidades ou bairros segregados. Foi desenvolvido pelo economista Thomas C. Schelling em 1971.

O modelo é baseado na ideia de que até mesmo preferências individuais leves por vizinhos de características semelhantes podem levar a um alto grau de segregação em nível macro. Ele fornece insights sobre como a segregação social pode surgir sem intenção explícita ou discriminação institucional.



Componentes do Modelo:

Aqui está uma explicação simplificada de como o modelo funciona:

1. Grade: O modelo representa uma grade ou um ambiente espacial no qual os agentes ou indivíduos são colocados. Cada célula da grade pode estar vazia ou ocupada por um agente.
2. Agentes: Os agentes no modelo representam indivíduos com determinadas características. Por exemplo, no modelo original, Schelling usou dois tipos de agentes: vermelhos e azuis, representando diferentes grupos raciais ou étnicos. Cada agente tem uma preferência pela proporção de vizinhos que deseja que sejam do mesmo tipo.
3. Vizinhança: Uma vizinhança é definida como o conjunto de células ao redor de um agente. O tamanho da vizinhança pode variar, mas geralmente inclui os vizinhos imediatos do agente.
4. Decisão de movimento: Em cada passo de tempo, um agente verifica sua vizinhança atual e compara a proporção de vizinhos que são do mesmo tipo que ele com sua preferência. Se a proporção ficar abaixo da preferência do agente, ele se considera insatisfeito e procura um novo local.
5. Movimento: Se um agente estiver insatisfeito, ele seleciona aleatoriamente uma célula vazia na grade e se move para aquele local. O agente deixa sua célula anterior vaga.
6. Iteração: A decisão de movimento e o processo de movimentação continuam para cada agente no modelo até que uma determinada condição de parada seja alcançada. Isso pode ser um número fixo de iterações ou até que um estado estável seja alcançado, onde nenhum agente está insatisfeito.
