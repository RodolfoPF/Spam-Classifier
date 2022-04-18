# Spam-Classifier
Classificador de mensagens em spam ou não.


A detecção de spam é uma das principais aplicações do Machine Learning nas interwebs hoje. Praticamente todos os principais provedores de serviços de e-mail têm sistemas de detecção de spam integrados e classificam automaticamente esse e-mail como 'Lixo Eletrônico'.

Nesta missão, usaremos o algoritmo Naive Bayes para criar um modelo que possa classificar as mensagens SMS do conjunto de dados (https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) como spam ou não spam, com base no treinamento que damos ao modelo. É importante ter algum nível de intuição sobre a aparência de uma mensagem de texto com spam. Normalmente, eles têm palavras como 'grátis', 'ganha', 'vencedor', 'dinheiro', 'prêmio' e afins neles, pois esses textos são projetados para chamar sua atenção e, em certo sentido, tentá-lo a abri-los. Além disso, as mensagens de spam tendem a ter palavras escritas em letras maiúsculas e também tendem a usar muitos pontos de exclamação. Para o destinatário, geralmente é bastante simples identificar um texto de spam e nosso objetivo aqui é treinar um modelo para fazer isso por nós!

Ser capaz de identificar mensagens de spam é um problema de classificação binária, pois as mensagens são classificadas como 'Spam' ou 'Não Spam' e nada mais. Além disso, este é um problema de aprendizado supervisionado, pois estaremos alimentando um conjunto de dados rotulado no modelo, com o qual ele pode aprender para fazer previsões futuras.

## Introdução ao teorema de Naive Bayes

O classificador multinomial Naïve Bayes é um dos modelos mais populares no aprendizado de máquina. Tomando como premissa a suposição de independência entre as variáveis do problema, o modelo de Naïve Bayes realiza uma classificação probabilística de observações, caracterizando-as em classes pré-definidas.

Sendo um modelo adequado para classificação de atributos discretos, o Naïve Bayes tem aplicações na análise de crédito, diagnósticos médicos ou busca por falhas em sistemas mecânicos.

É interessante saber que o Naïve Bayes é um dos modelos mais conhecidos a aplicar o conceito de probabilidade. Esse modelo, como o nome indica, faz uso do teorema de Bayes como princípio fundamental.

Como curiosidade, o teorema foi desenvolvido pelo estatístico, filósofo e ministro presbiteriano Thomas Bayes (1701 - 1761) e publicado depois de sua morte pelas mãos de Richard Price (1723 - 1791), um padre, filósofo e matemático galês, sendo definido como:

P(E)P(E) = P(H)P(H)

Em que P (H) é a probabilidade de que uma hipótese (H) seja verdadeira, antes de qualquer evidência (E) ser conhecida. O termo P(H) é a probabilidade de observarmos uma evidência (E), dado que a hipótese (H) é verdadeira. Por outro lado, P(E) é a probabilidade de observação da evidência (E) e P(E) é a probabilidade de que a hipótese (H) seja verdadeira, dada a evidência observada (E).

O algoritmo Naïve Bayes é uma aplicação direta do teorema homônimo. O termo naïve, (do inglês, ingênuo) se refere à premissa central do algoritmo de que os atributos considerados são não correlacionados entre si.
Fonte: https://www.digitalhouse.com/br/blog/naive-bayes/

