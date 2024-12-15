1. Considere a base que você ajustou na lição passada. Carregue-a. Caso ainda haja alguma pendência, ajuste - lembre-se de que o scikitlearn não recebe variáveis em formato string, somente numéricas, e não aceita 'missings'.

Separe 70% da base para treinamento e 30% para validação. Cada uma dessas partes terá dois objetos, um armazenando a variável resposta maue outro armazenando as variáveis explicativas (lembrando: sem variáveis string, já com as dummies).

e tambem vamos ultilizar algumas bibliotecas e seus modulos para treina o modelo

.numpy
.pandas
.searborn
.matplotlib
.sklearn

2. Defina um objeto com a função da árvore de decisão vista em aula.
Treine o modelo com os dados que você separou para treinamento.
Visualize a árvore. Talvez você queira aumentar um pouco a figura.
Produza uma visualização da matriz de classificação (ou matriz de confusão) - coloque os rótulos como "aprovados" e "reprovados" - pois afinal de contas, são essas as decisões que se podem tomar com propostas de crédito.
Calcule a acurácia na base de treinamento


3. Classifique a base de teste de acordo com a árvore que você treinou no item 2.
Produza a visualização da matriz de confusão para a base de teste.
Calcule a acurácia da base de teste. Compare com a acurácia da base de treinamento.
Treine uma nova árvore com número mínimo de observações por folha de 5 e máximo de profundidade de 10. Use o random_state = 123. Avalie a matriz de classificação. Observe a distribuição da predição - qual a proporção de proponentes foram classificados como 'maus'?
Como ficaria a acurácia se você classificasse todos os contratos como 'bons'?
