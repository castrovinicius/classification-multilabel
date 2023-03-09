#### Projeto: Classification Multilabel

Este projeto tem como objetivo implementar algoritmos de classificação multilabel em textos. Utilizamos uma base de dados de perguntas feitas no [stack overflow](https://pt.stackoverflow.com/). 

Em **class_mult.ipynb** é explorado alguns algoritmos de machine learning. tais quais:

1. One vs Rest
2. Binary Relevance
3. Classifier Chain
4. MLkNN

O algoritmo **One vs Rest** é um método de classificação binária que é usado para classificar instâncias em várias classes. Neste método, cada classe é tratada como uma classe separada e um modelo de classificação binária é treinado para cada classe. O modelo prediz se a instância pertence à classe ou não. Esta abordagem pode ser usada para problemas multi-label como cada label pode ser tratado como uma classe separada.

**Binary Relevance** **(BR)** é um método simples para resolver problemas multi-label. Neste método, um modelo de classificação binário é treinado para cada label individualmente e as previsões são feitas independentemente para cada label. Este método não considera as correlações entre os labels e, portanto, não pode aproveitar essas relações para melhorar o desempenho da classificação.

**Classifier Chain** **(CC)** é uma abordagem que tenta aproveitar as correlações entre os labels enquanto resolve problemas multi-label. Neste método, os modelos são treinados em uma seqüência ordenada onde cada modelo usa as previsões dos modelos anteriores como entrada adicional. Esta abordagem permite que os modelos compartilhem informações entre si e melhorem o desempenho da classificação.

**MLkNN (Multi-Label k Nearest Neighbors)** é um algoritmo de aprendizado supervisionado baseado em instâncias que foi projetado especificamente para solucionar problemas multi-label. Neste algoritmo, o conjunto de dados é dividido em duas partes: o conjunto de treinamento e o conjunto de teste. Para cada instância no conjunto de teste, os k vizinhos mais próximos são encontrados no conjunto de treinamento usando distâncias predefinidas entre as instâncias do conjunto de treinamento e do conjunto de teste. As previsões finais são feitas usando os labels dos vizinhos mais próximos encontrados no conjunto de treinamento.

#### Contato

Encontrou algum erro ou tem uma sugestão de melhoria?

Entre em contato comigo pelo e-mail: [vinicius.castro97@hotmail.com](mailto:vinicius.castro97@hotmail.com)

#### Certificado

[Alura](https://cursos.alura.com.br/certificate/48605282-1ece-40fd-9397-b44bb5ba9421)
