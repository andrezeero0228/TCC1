## Measuring Software Testability Modulo Test Quality


Terregani, Valerio; Salza, Pasquale; Pezze, Mauro(2020) "Measuring Software Testability Modulo Test Quality", Proceedings of the 28th International Conference on Program Comprehension, doi:  ["Measuring Software Testability Modulo Test Quality](https://dl.acm.org/doi/10.1145/3387904.3389273).

## 1. Fichamento de Conteúdo
O artigo cita a importância de entender até que nível conseguimos testar cada software e seus componentes de modo unitário. Sendo assim, a característica chamada testabilidade é o atributo que mede e relaciona as características do código com seu esforço em testá-lo. Com a literatura que temos hoje, o que sabemos da testabilidade é que existe uma relação entre o esforço de testar um componente com seu tamanho e complexidade do código. O artigo relata uma correlação de algumas métricas de classe com métricas de testes, porém ressalta algumas limitações: os dados não se generalizavam, devido ao pequeno número de projetos analisados, e também a qualidade dos testes não era levada em conta, o que pode ser um equívoco, pois classes poderiam apresentar um esforço de teste baixo por conta da qualidade ruim, e não especificamente porque a classe era fácil de testar. O artigo, então, propôe uma abordagem que mede a testabilidade, relacionando o esforço do teste com a qualidade do mesmo, que foi mensurado a partir do percentual de cobertura do código. Os resultados foram colhidos utilizando como base de dados 9861 classes Java, pertencendo a 1186 projetos, o que totalizou um milhão e meio de linhas de código. Foi confirmado a relação do esforço do teste em relação à qualidade do teste.

## 2. Fichamento Bibliográfico

-   _test suite_ : coleção de casos de teste que se destinam a ser usados ​​para testar um programa de software para mostrar que ele tem algum conjunto específico de comportamentos.

-   _datasets_ : é um conjunto de dados organizado de tal maneira que possa ser utilizado como base de uma pesquisa ou experimento.
-   _refactoring actions_ : processo de remodelar o código de um software a fim de melhorar sua estrutura, sem alterar seu funcionamento.


## 3. Fichamento de Citações

-   _"The results confirm that normalizing the test effort with respect to the test quality largely improves the correlation between class metrics and the test effort"_ 
- 
-   _"Indeed, a class may have a low test effort because the associated tests are of poor quality, and not because the class is easier to test."_
-   _"Software testability estimates such property by relating code characteristics to the test effort."_ 


