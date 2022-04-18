# Spam-Classifier
Classificador de mensagens em spam ou não.


A detecção de spam é uma das principais aplicações do Machine Learning nas interwebs hoje. Praticamente todos os principais provedores de serviços de e-mail têm sistemas de detecção de spam integrados e classificam automaticamente esse e-mail como 'Lixo Eletrônico'.

Nesta missão, usaremos o algoritmo Naive Bayes para criar um modelo que possa classificar as mensagens SMS do conjunto de dados (https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) como spam ou não spam, com base no treinamento que damos ao modelo. É importante ter algum nível de intuição sobre a aparência de uma mensagem de texto com spam. Normalmente, eles têm palavras como 'grátis', 'ganha', 'vencedor', 'dinheiro', 'prêmio' e afins neles, pois esses textos são projetados para chamar sua atenção e, em certo sentido, tentá-lo a abri-los. Além disso, as mensagens de spam tendem a ter palavras escritas em letras maiúsculas e também tendem a usar muitos pontos de exclamação. Para o destinatário, geralmente é bastante simples identificar um texto de spam e nosso objetivo aqui é treinar um modelo para fazer isso por nós!

Ser capaz de identificar mensagens de spam é um problema de classificação binária, pois as mensagens são classificadas como 'Spam' ou 'Não Spam' e nada mais. Além disso, este é um problema de aprendizado supervisionado, pois estaremos alimentando um conjunto de dados rotulado no modelo, com o qual ele pode aprender para fazer previsões futuras.