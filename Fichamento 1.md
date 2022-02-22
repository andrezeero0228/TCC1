## LCCSS: A Similarity Metric for Identifying Similar Test Code

Pereira da Silva, Lucas; Vilain, Patricia (2020) "LCCSS: A Similarity Metric for Identifying Similar Test Code", 14th Simpósio Brasileiro de Componentes, Arquiteturas e Reusagens de Software, doi:  [LCCSS: A Similarity Metric for Identifying Similar Test Code](https://dl.acm.org/doi/10.1145/3425269.3425283).

## 1. Fichamento de Conteúdo
O artigo cita que uma das características mais preocupantes na produção de testes de software é a manutenibilidade  do código de teste, pois para que ele possua isso, é preciso que os métodos de teste sigam alguns padrões de código, como por exemplo nomes simples e claros, estruturados, pequenos, coesos, modulares e sem duplicação de código. Duas estratégias criadas para que não ocorra a duplicação de código no teste são a configuração implícita e configuração delegada. Para que essas estratégias possam ser aplicadas, o código duplicado deverá ser identificado previamente. 
Para resolver isso, o artigo explicita a automatização à identificação de duplicações no código teste que foi feita através de métricas de similaridade de código. Os autores propuseram uma dessas métricas, chamada de LCCSS(Sub-Sequência de Início Contígua Mais Longa). Essa métrica utiliza pares de teste para medir similaridade em seus códigos. Os pares que forem caracterizados como mais semelhantes são considerados fortes candidatos para a refatoração através da configuração implícita. 
O artigo também cita um framework desenvolvido chamado Róza, que utiliza também outras metricas de similaridade para identificar duplicações.
Foi feito um experimento utilizando LCCSS e Simian, uma ferramenta de detecção de clonagem de código. A conclusão foi que o LCCSS não precisou ser recalibrado para cada projeto testado, a fim de identificar pares de testes para serem refatorados.

## 2. Fichamento Bibliográfico

-   _implicit setup_  (configuração implícita): É uma maneira de reutilizar um código de configuração de testes para todos os casos de teste de uma determinada classe. (página 1)
- _delegated setup_  (configuração implícita): É uma maneira de reutilizar código de forma que cada caso de teste configure suas próprias variáveis chamando um ou mais métodos de criação. (página 1)

-   _maintainability_  (manutenibilidade): é um aspecto da qualidade de software que se refere à facilidade de um software de ser modificado a fim de corrigir defeitos, adequar-se a novos requisitos, aumentar a suportabilidade ou se adequar a um ambiente novo. (página 1)

## 3. Fichamento de Citações

-   _"We propose a novel similarity metric, called Longest Common Contiguous Start Sub-Sequence (LCCSS), to identify refactoring candidates. LCCSS is a metric used to measure similarity between pairs of tests."_  (página 1)
-   _"An experiment shows that LCCSS and Simian, a clone detection tool, have both identified pairs of tests to be refactored through the implicit setup strategy with maximum precision in all the eleven standard recall levels. But, unlike Simian, LCCSS does not need to be calibrated for each project."_  (página 1)
-   _"Test code maintainability is a common concern in software testing. In order to achieve good maintainability, test methods should be clearly structured, well named, small in size, and, mainly, test code duplication should be avoided."_  (página 1)


