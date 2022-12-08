# Análise de dados e Machine Learning
Primeiramente, bom momento para você, caro leitor, que prestigia meu humilde projeto!

Este modelo foi criado há algum tempo, mas só agora tive coragem de refazê-lo da melhor maneira possível.

Ele nasceu como um projeto simples de machine learning, sua única função era não passar vergonha na competição House Prices - Advanced Regression Techniques (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview), e deu tudo certo!

Atualmente, ocupo a posição 1202 de 4561 equipes inscritas na competição, o que é muito bom, já que o modelo é o mais simples possível.

A análise dos dados foi a mais simples possível, apenas chequei correlações, outliers e visualizei parte dos dados.
A limpeza também foi simples, rápida, básica, mas eficiente. Nas colunas categóricas, utilizei o valor mais frequente para preencher os vazios. Nas numéricas, a média.

Tudo isso foi feito utilizando Pipelines, assim o processo fica mais simples e fácil de generalizar, além de ser uma ótima base para os outros projetos mais complexos.

Para o modelo, a escolha padrão é o XGBoost Regressor. Os testes com árvores de decisão clássicas, redes neurais e regressão linear não chegaram aos pés do XGBRegressor.

Para ter uma ideia da diferença entre eles, podemos observar o score de cada modelo na competição: o modelo utilizando regressão de Lasso, que é um tipo de regressão linear tunada, obteve o score: 0.25724, enquanto o modelo XGBRegressor obteve score: 0.13192, suficiente para pular centenas de posições no leaderboard.
Essa pontuação é o Erro Médio Absoluto, calculado a partir da média dos erros de cada previsão do modelo, por isso quanto menor, melhor.

Bom, esse é o projeto! Espero que você tenha gostado, e estou disponível para tirar qualquer tipo de dúvida.
Até mais!
