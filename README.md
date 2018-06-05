## Tarefas:
 1) Elaborar um **tutorial** passo a passo para a explicação do tema com **exemplos**. O tutorial deve ser descrito
em um **documento escrito**.
 2) Apresentar um **seminário** de aproximadamente **25 minutos** para expor os resultados sobre o tema pesqui-
sado. O grupo deve preparar um conjunto de slides de apoio à apresentação.
 3) Preparar e entregar um **exercıcio** para os alunos da turma sobre o tema.
 4) Corrigir a resposta elaborada pelos alunos do exercıcio.
 
## Tema: Padrões de Projetos Comportamentais
**O que são design patterns**?
 Em Engenharia de Software, um design pattern é uma **solução geral** repetida a problemas comuns
 que ocorrem em projetos de software. Um design pattern não é um projeto pronto que pode ser
 implementado diretamente (código). É uma **descrição ou modelo** de como resolver determinado
 problema que aparece em diferentes situações.
 
**Usos dos design patterns**:
 Os design pattern podem **diminuir o tempo de desenvolvimento** do projeto ao fornecer **modelos
 corretos e testados**. Projetos efetivos de software consideram problemas que podem não ser visíveis
 até a sua implementação. Reusar padrões de projeto ajuda a prevenir que tais erros se tornem
 grandes problemas e melhora a leitura do código para aqueles que já tem familiaridade com os padrões.
 Design patterns permitem uma boa comunicação entre desenvolvedores pois usam nomes sugestivos do que
 eles significam e quais os seus usos nas interações do software.
 
**O que são padrões de projeto comportamentais (behavioral design patterns)**?
 Em Engenharia de Software, padrões de projeto comportamentais são padrões de projeto que identificam
 **padrões comuns de comunicação** entre objetos e percebe esses padrões. Fazendo isso, esses padrões
 ganham flexibilidade em executar essa comunicação.
 
 
## 1) Cadeias de Responsabilidade (Chain of Responsibility)
É um design pattern cuja principal função é **evitar a dependência entre um objeto receptor e um
objeto solicitante**. Você tem uma série de objetos receptores e solicitantes, e cada objeto solicitante
possui uma lógica interna que determina quais objetos receptores vão poder tratar essa requisição. Caso
determinado objeto receptor não consiga tratar essa requisição, esta é passada pro próximo objeto
receptor da cadeia.

**Links** com exemplos de códigos em Java: <br />
https://pt.wikipedia.org/wiki/Chain_of_Responsibility <br />
https://sourcemaking.com/design_patterns/chain_of_responsibility <br />
https://sourcemaking.com/design_patterns/chain_of_responsibility/java/1 <br />


## 2) Command
Na programação orientada a objeto, o Command é um padrão no qual um objeto é usado para **encapsular toda informação
necessária para executar uma ação ou acionar um evento em um momento posterior**. A ideia é separar o cliente que cria um
Command do cliente que executa o Command, ou seja, o Command descopla o objeto que invoca a operação daquele que sabe
como executá-la.

**Links** com exemplos de códigos em Java: <br />
https://pt.wikipedia.org/wiki/Command <br />
https://sourcemaking.com/design_patterns/command/java/1 <br />
https://sourcemaking.com/design_patterns/command/java/2 <br />

## 3) Interpretador (Interpreter)
Dada uma linguagem, você **representa ela em uma determinada gramática**, isto é, com regras e tudo mais. Além disso, você
tem um interpretador, que é responsável por **interpretar essa representação da linguagem seguindo as regras gramaticais**.
Pode-se pensar na representação de uma música como partitura. Essa representação então é interpretada por um músico
que consegue, seguindo as regras da partitura, reproduzir o mesmo som (mesmo tom e duração).

**Links** com exemplos de códigos em Java: <br />
https://pt.wikipedia.org/wiki/Interpreter <br />
https://sourcemaking.com/design_patterns/interpreter <br />
https://sourcemaking.com/design_patterns/interpreter/java/1 <br />
https://sourcemaking.com/design_patterns/interpreter/java/2 <br />


## 4) Iterador (Iterator)
O Padrão Iterator fornece uma maneira de **acessar sequencialmente os elementos de um objeto agregado sem expor a sua
representação subjacente (estrutura de dados utilizada)**. Portanto, temos que o padrão Iterator permite acessarmos
um a um os elementos de um agregado mesmo sem saber como eles estão sendo representados,
assim torna-se irrelevante se a coleção de objetos está num ArrayList, HashTable ou que quer que
seja. Além disso, o Padrão Iterator assume a responsabilidade de acessar sequencialmente os 
elementos e transfere essa tarefa para o objeto Iterador, dessa forma o objeto agregador tem a sua 
interface e implementação simplificadas, não sendo mais o responsável pela iteração.

**Links** com exemplos de códigos em Java: <br />
https://www.devmedia.com.br/padrao-de-projeto-iterator-em-java/26733 <br />
https://sourcemaking.com/design_patterns/iterator <br />
https://sourcemaking.com/design_patterns/iterator/java/1 <br />
https://sourcemaking.com/design_patterns/iterator/java/2 <br />


## Sequência da Apresentação
1) Passagem rápida sobre o que é Design Patterns e Design Patterns Comportamentais
2) Apresentar 4 ou 5 Design Patterns (aqueles que acharmos mais relevantes)
3) Pra cada Design Pattern, explicar o que é e sua motivação de uso, e mostrar 2 exemplos (1 mais abstrato com
exemplos do mundo real e sem código, pra galera abstrair melhor o que significa o padrão
e o outro com uma aplicação mais técnica e com a implementação em Java).
