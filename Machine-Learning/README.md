## Básico

O livro "ISLR" (Introduction to Statistical Learning) cobre todos esses tópicos e é sem dúvida o melhor livro de Machine Learning para iniciantes.

## Intermediário/Avançado

#### SVM

O livro "ISLR" aborda o algoritmo.

#### Lidar com classes desbalanceadas

Geralmente não é algo muito abordado em livros. Recomendo [este artigo](https://machinelearningmastery.com/combine-oversampling-and-undersampling-for-imbalanced-classification/) por mostrar como oversampling e undersampling são utilizados na prática e com a biblioteca imblearn, que é a mais utilizada para esse propósito.

#### Evitar Data Leakage

Não tem muito conteúdo abordando isso. Acho que vale marcar uma conversa para discutirmos esse assunto, porque é um problema que pode acontecer no dia a dia do Data Scientist e facilmente passar despercebido.

#### Feature Selection

Existem muitas técnicas. [Este artigo](https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/) dá uma boa noção dos "filter-based methods". O livro "ISLR" aborda "Stepwise Selection".

#### Gradient Boosting Machines

Para entender o conceito do algoritmo eu recomendo [este artigo](https://explained.ai/gradient-boosting/index.html) e essa série de 4 vídeos: [parte 1](https://www.youtube.com/watch?v=3CC4N4z3GJc&ab_channel=StatQuestwithJoshStarmer).
Há vários módulos que implementam o algoritmo, o meu preferido, pelo desempenho e capacidade de aceitar variáveis categóricas em string e valores NaNs, é o [LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html).

#### Otimização de Hiperparâmetros

Os metódos mais relevantes são Grid, Random e Bayesian. Para os dois primeiros [este artigo](https://machinelearningmastery.com/hyperparameter-optimization-with-random-search-and-grid-search/) já dá uma boa noção. Já pro Bayesian Optimization, que é o método mais performático em geral e o que mais uso, [este artigo](https://distill.pub/2020/bayesian-optimization/) é muito bem elaborado.
Em relação aos módulos que implementam Bayesian eu recomendo tanto o [HyperOpt](http://hyperopt.github.io/hyperopt/) quanto o [Optuna](https://optuna.org/). Dependendo da situação um pode ser mais adequado que o outro.

## Deep Learning/NLP

#### Bag of Words/TF-IDF

É um tópico bem simples na verdade, qualquer artigo na internet é suficiente pra entender. [Este](https://medium.com/analytics-vidhya/fundamentals-of-bag-of-words-and-tf-idf-9846d301ff22) por exemplo, que foi o primeiro que achei, já considero decente.

#### Multilayer Perceptron, CNN e RNN/LSTM

Gosto bastante do livro "Deep Learning with Python" para esses tópicos. Acho que ele tem um equilíbrio muito bom entre teoria e prática e ainda vai ter passar quase tudo o que precisa saber sobre Tensorflow-Keras. Como uma opção de curso eu recomento [este do Coursera](https://www.coursera.org/specializations/deep-learning), provavelmente seja o melhor disponível atualmente.

#### Weak Supervision

Assunto muito pouco explorado. Acho que vale uma conversa para eu explicar melhor. Mas a [página do framework Snorkel](https://www.snorkel.org/get-started/) (o que utilizo) tem bastante conteúdo interessante, principalmente na seção "tutorials".