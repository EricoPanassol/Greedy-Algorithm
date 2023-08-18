# Greedy Algorithm

## Discplina: Projeto e Otimização de Algoritmos

Estudo das principais técnicas para o projeto e análise de algoritmos: programação dinâmica,
algoritmos gulosos, divisão e conquista, backtracking, branch and bound e algoritmos genéticos.
Estudos de caso no desenvolvimento de algoritmos Introdução ao Teorema Mestre.

### <ins>Objetivos do trabalho:</ins>

- Este trabalho consiste no desenho, análise e implementação de algoritmos greedy.

- O trabalho pode ser realizado grupos de até 4 alunos.

- O trabalho deve ser implementado em Java.

### <ins>Problema 1</ins>

Você e um grupo de amigos deseja realizar um rally pelo deserto de Dakkar. Os regulamentos da corrida 
determinam que os times podem viajar apenas durante o dia. Após analisar o mapa seus colegas
identificaram um grande conjunto de bons pontos de para passar a noite. Durante várias sessões de
brainstorming eles (sim, você estava estudando para as provas P1 e não participou) definiram o seguinte 
algoritmo para determinar se vocês conseguem chegar no próximo ponto de parada antes do anoitecer. 

Algoritmo: Cada vez que vocês chegarem a um potencial ponto de parada, vocês determinam se conseguem 
chegar no próximo ponto de parada antes do anoitecer. Se vocês conseguirem, vocês continuam dirigindo, 
caso não consigam, vocês param e acampam no ponto atual.

Eles afirmam que o algoritmo acima os levará a linha de chegada com o menor número de paradas. Você 
concorda?

Para tornar a questão mais precisa vamos assumir as seguintes premissas:
- Modelaremos a trilha do rally como um longo segmento de linha de comprimento _L_.

- Vocês conseguem viajar no máximo _d_ quilômetros por dia antes de anoitecer.
- Assumiremos que os pontos de parada estão localizados a distâncias _X1_, _X2_, …, _Xn_ do ponto de 
partida.

- Assumiremos também que os seus amigos sempre estão corretos quando estimam se conseguem ou 
não chegar ao próximo ponto de parada antes do anoitecer.

- Vamos considerar um conjunto de pontos de parada como válidos se a distância entre cada par 
adjacente é no máximo _d_, e o primeiro ponto de parada está a no máximo uma distância _d_ do início 
e o último ponto de parada está a uma distância no máximo � do final da corrida. Portanto, um 
conjunto de pontos de parada é valido se vocês conseguirem acampar nestes pontos e ainda 
completar toda a trilha.

- Assumimos que o conjunto _n_ com todos os pontos de parada é valido

Com base nas informações acima, podemos afirmar que o algoritmo proposto é ótimo, no sentido de que 
encontra o menor conjunto de pontos de parada válidos que completa o rally?

Estruture a resposta no formato de um relatório com as seguintes sessões:
1. O Problema;
2. O Algoritmo;
3. Análise do Algoritmo;
4. Implementação e Tempo de Execução;
