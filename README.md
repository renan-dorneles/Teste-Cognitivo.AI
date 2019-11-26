# Teste-Cognitivo.AI
Código teste para processo seletivo na Cognitivo.AI
A estratégia para modelagem dos dados da airbnb foi adotada a partir da resposta que seria predita. Optou-se por responder o problema de classificação sobre qual o tipo de quarto, baseando-se nas demais variáveis. Este problema também foi selecionado, pois apresentava uma quantidade significativa de variáveis no arquivo principal escolhido, além de ser um tipo de problema de familiaridade do desenvolvedor, facilitando a finalização do código no prazo estipulado.

Como o problema escolhido era de classificação em múltiplas categorias, utilizou-se a entropia cruzada de multicategorias para a solução do problema (ou log-loss), mas para a seleção dos múltiplos modelos, optou-se por um equilíbrio entre uma acurácia melhor vs. uma função de perda menor.

O modelo de rede neural com utilização da experimentação Talos foi escolhido, por permitir a procura de parâmetros de forma mais ampla, facilitando o teste de performance em mais situações. Este modelo apresentou-se bem sucedido, pois, em sua base de validação apresentou acurácia acima 80% e f-score (balanceamento entre as classes) acima de 80% também.
