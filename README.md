Descrição do Projeto:
Este projeto implementa a simulação do crescimento logístico da população, um modelo comum em biologia e ecologia para descrever o crescimento de uma população que atinge um limite (capacidade de suporte) devido à competição por recursos. O código explora como diferentes parâmetros influenciam o crescimento populacional ao longo do tempo.

Funcionalidades:
Modelo de Crescimento Logístico:

A função logistic_growth implementa a fórmula do crescimento logístico, que descreve o crescimento de uma população 
𝑃
(
𝑡
)
P(t) com o tempo 
𝑡
t, dada uma capacidade de suporte 
𝐾
K, uma taxa de crescimento 
𝑟
r, e uma população inicial 
𝑃
0
P 
0
​
 .
Parâmetros Importantes:

P0: População inicial.
K: Capacidade de suporte (limite máximo que o ambiente suporta).
r: Taxa de crescimento populacional.
t: Tempo (gerado como um vetor de 0 até o valor máximo definido).
Visualizações:

O código gera três gráficos diferentes que mostram como o crescimento da população é afetado por:
Diferentes capacidades de suporte (
𝐾
K).
Diferentes taxas de crescimento (
𝑟
r).
Diferentes populações iniciais (
𝑃
0
P 
0
​
 ).

 Tecnologias Utilizadas:
NumPy: Para cálculos matemáticos e geração de dados de tempo.
Matplotlib: Para criar gráficos que visualizam o crescimento da população ao longo do tempo.
Seaborn: Para estilizar os gráficos e melhorar a legibilidade.
Como o Código Funciona:
Modelo de Crescimento Logístico:

A fórmula do crescimento logístico é usada para calcular a população ao longo do tempo:
𝑃
(
𝑡
)
=
𝐾
1
+
(
𝐾
−
𝑃
0
𝑃
0
)
𝑒
−
𝑟
𝑡
P(t)= 
1+( 
P 
0
​
 
K−P 
0
​
 
​
 )e 
−rt
 
K
​
 
A função logistic_growth aceita os parâmetros 
𝑃
0
P 
0
​
  (população inicial), 
𝐾
K (capacidade de suporte), 
𝑟
r (taxa de crescimento), e 
𝑡
t (tempo), e retorna os valores de população para cada instante de tempo.
Gráficos:

O primeiro gráfico mostra o impacto de diferentes capacidades de suporte 
𝐾
K no crescimento da população, mantendo a taxa de crescimento 
𝑟
r constante.
O segundo gráfico mostra o impacto de diferentes taxas de crescimento 
𝑟
r, com uma capacidade de suporte 
𝐾
K fixa.
O terceiro gráfico mostra o efeito de diferentes populações iniciais 
𝑃
0
P 
0
​
 , mantendo 
𝐾
K e 
𝑟
r constantes.

Resultados:
Capacidade de Suporte (
𝐾
K):

À medida que 
𝐾
K aumenta, a população atinge um valor maior, mas o comportamento de crescimento inicial permanece o mesmo.
Taxa de Crescimento (
𝑟
r):

Quanto maior a taxa de crescimento, mais rápido a população atinge a capacidade de suporte.
População Inicial (
𝑃
0
P 
0
​
 ):

Diferentes valores de 
𝑃
0
P 
0
​
  afetam o tempo necessário para a população atingir 
𝐾
K, mas todas as populações convergem para o mesmo valor de 
𝐾
K com o tempo.
Visualizações:
Três gráficos são gerados, cada um explorando uma variável do modelo logístico:
Crescimento com Diferentes Capacidades de Suporte:
Explora o impacto de 
𝐾
K no crescimento da população.
Crescimento com Diferentes Taxas de Crescimento:
Explora como variações em 
𝑟
r afetam a rapidez com que a população cresce.
Crescimento com Diferentes Populações Iniciais:
Mostra como o valor inicial da população influencia o crescimento até atingir 
𝐾
K.
Exemplo de Gráficos:
Os gráficos mostram curvas de crescimento logístico com diferentes parâmetros:

Gráfico 1: Crescimento Populacional com Diferentes Capacidades de Suporte 
𝐾
K.
Gráfico 2: Crescimento Populacional com Diferentes Taxas de Crescimento 
𝑟
r.
Gráfico 3: Crescimento Populacional com Diferentes Populações Iniciais 
𝑃
0
P 
0
​
 .
