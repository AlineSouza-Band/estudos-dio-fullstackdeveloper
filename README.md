# estudos-dio-fullstackdeveloper
Estudos Dio full Stackdeveloper

###                        Introdução a programação :computer:

"Ao estudar lógica de programação nos deparamos com alguns conceitos como: algoritmos, fluxogramas, pseudocódigo e sobre linguagem estruturada.

É importante entendermos esses conceitos para ter uma base sólida no aprendizado de programação. Vamos resumir alguns conceitos:

Um algoritmo é uma sequência de passos, com começo, meio e fim, que realiza uma tarefa específica. Muitas vezes para auxiliar na criação e interpretação de um algoritmo nós podemos utilizar uma ferramenta chamada fluxograma, que é um diagrama com símbolos específicos para indicar cada passo e ordem de um algoritmo.

Partindo para algo mais prático, podemos utilizar o “pseudocódigo”, que é um “código” entre a linguagem natural e a codificação propriamente dita. Ela utiliza a estrutura de uma linguagem mas com termos mais simples para facilitar a interpretação do algoritmo. Como podemos ver no exemplo abaixo.

```
Algoritmo "Somar"

inteiro numero1, numero2, soma;
Exiba: "Digite dois números que serão somados";
leia (numero1,numero2);
soma = numero1+numero2;
Exiba: "O resultado da soma é "soma;
fim;
```

Você pode se aprofundar sobre o tema lendo o nosso artigo sobre os “[Conceitos usados no aprendizado de programação](https://www.treinaweb.com.br/blog/conceitos-usados-no-aprendizado-de-programacao/)”.

## Variáveis e constantes na programação

Ao desenvolver um algoritmo nós precisamos lidar com algum dado ou informação que será manipulado pelo nosso programa. Para lidar com esses dados nós utilizamos as variáveis e constantes.

As variáveis são utilizadas para armazenar dados simples, dado este que pode ser alterado de alguma forma dentro de nosso programa. Como podemos armazenar diferentes tipos de dados, as variáveis também possuem tipos como:

- **int:** (valor número do tipo inteiro).
- **float:** (valor número do tipo decimal).
- **double:** (valor numérico do tipo decimal de precisão dupla).
- **char:** (caractere do tipo texto), string (conjunto de caracteres do tipo texto).
- **boolean:** (representa somente dois valores, verdadeiro ou falso).

As constantes, ao contrário das variáveis, armazenam dados que não podem ser alterados no desenvolvimento do algoritmo, elas possuem um valor fixo. São utilizadas para guardar valores matemáticos ou textos que são estáticos.

## Operadores matemáticos usados na programação

Utilizamos operadores matemáticos a todo momento quando vamos desenvolver um software, independente da linguagem ou paradigma, portanto é fundamental saber como utilizar cada operador.

Partindo do básico, com frequência utilizamos funções com operações básicas da matemática, para realizar essas operações utilizando uma linguagem de programação nós utilizamos os seguintes operadores:

| Operador | Descrição     |
| -------- | ------------- |
| +        | Adição        |
| -        | Subtração     |
| /        | Divisão       |
| *        | Multiplicação |

Vale ressaltar que, como aprendemos em expressões matemáticas, cada operação tem precedência perante outras, seguindo a lógica dos parênteses, potenciação e raiz quadrada, multiplicação e divisão, soma e subtração.

## Operadores de comparação na programação

Usamos os operadores de comparação para analisar os valores em uma condição, onde o retorno dessa condição será um valor booleano, ou seja, verdadeiro ou falso. Com isso podemos tratar o comportamento de um algoritmo dependendo dos resultados obtidos.

Os operadores podem variar dependendo da linguagem de programação, pois algumas possuem certas particularidades, mas temos os mais comuns e utilizados na grande maioria delas, que são:

- \> (maior): Retorna verdadeiro caso o primeiro valor seja maior que o segundo.
- \>= (maior ou igual): Retorna verdadeiro caso o primeiro valor seja maior ou igual ao segundo.
- < (menor): Retorna verdadeiro caso o primeiro valor seja menor que o segundo.
- <= (menor ou igual): Retorna verdadeiro caso o primeiro valor seja menor ou igual ao segundo
- == (igual a): Retorna verdadeiro caso o primeiro valor seja igual ao segundo.
- != (diferente de): Retorna verdadeiro caso o primeiro valor seja diferente do segundo.

No javascript por exemplo temos também o operador `===`que além de comparar os valores também leva em consideração o tipo da variável.

Em nosso artigo sobre [Operadores de comparação](https://www.treinaweb.com.br/blog/operadores-de-comparacao-na-programacao/) na programação aplicamos na prática o uso dos operadores de comparação e utilizamos fluxogramas para facilitar a interpretação, vale a leitura caso você queira se aprofundar sobre o assunto.

## Operadores lógicos

Além dos operadores matemáticos e de comparação, existem os operadores lógicos. Estes são os que trazem mais dúvidas aos iniciantes em lógica de programação se tratando do estudo de operadores.

Em programação existe um tipo de dado chamado booleano, tipo este que guarda somente duas informações: Verdadeiro ou Falso. Ao criar uma estrutura de condição, o retorno desta condição será um dado booleano, para criar essas condições as linguagens também possuem os operadores lógicos. Dessa forma podemos criar operações lógicas mais complexas, esses operadores são:

- && (E): Retorna verdadeiro **quando todas** as expressões da condição são verdadeiras, caso contrário, retorna falso.

![img](https://dkrn4sk0rn31v.cloudfront.net/2020/01/15112656/operador-logico-e.png)

- || (OU): Retorna verdadeiro quando pelo **menos uma** das expressões da condição é verdadeira.

![img](https://dkrn4sk0rn31v.cloudfront.net/2020/01/15112711/operador-logico-ou.png)

- ! (negação ou “not”): Retorna o oposto do valor em questão.

![img](https://dkrn4sk0rn31v.cloudfront.net/2020/01/15112750/operador-logico-nao.png)

Temos um artigo falando somente sobre os [Operadores lógicos](https://www.treinaweb.com.br/blog/operadores-logicos/), para se aprofundar no tema indico a leitura do mesmo.

## Estruturas condicionais e de repetição

Utilizando os operadores de comparação e lógicos podemos criar as estruturas condicionais. Em relação as estruturas condicionais, podemos separar em dois tipos de estrutura:

- Simples - Utilizamos a condição SE (IF), caso a condição seja verdadeira, o algoritmo executa a tarefa solicitada, caso contrário o bloco da condição é ignorado.
- Composta - Utilizamos a condição SE (IF), caso a condição seja verdadeira, o algoritmo executa a tarefa solicitada, caso contrário utilizamos a condição SENÃO (ELSE), desta forma o algoritmo irá executar a tarefa do bloco SENÃO.

Em algumas situações será necessário executar mais de uma vez o bloco referente às estruturas condicionais, para isso utilizamos as estruturas de repetição. As estruturas de repetição mais comuns são:

- ENQUANTO (WHILE) - Enquanto o resultado da condição for verdadeira, o algoritmo executa o bloco proposto, por fim é necessário que algo dentro do bloco altere a condição. Mais indicado para ser utilizado quando não sabemos quantas vezes o bloco será executado.
- PARA (FOR) - A condição PARA tem o mesmo princípio que utilizar enquanto (while), porém este recurso é mais utilizado quando se sabe o número de iterações da repetição, como listar os valores de um vetor por exemplo, também vale ressaltar a legibilidade do código, por ser mais limpo e elegante.

Em nosso artigo sobre [estruturas condicionais e de repetição](https://www.treinaweb.com.br/blog/estruturas-condicionais-e-de-repeticao/) aprofundamos a explicação de cada estrutura e condição, com exemplos práticos e com fluxogramas.

## Modularização: Funções e Procedimentos

Utilizando funções e procedimentos podemos modular a construção de um software, ou seja, definir em tarefas menores partes do sistema que possuem responsabilidades específicas. O uso deste recurso traz muitas vantagens como reutilização de código, facilidade de manutenção, melhor legibilidade, entre outras.

Podemos definir de forma básica funções e procedimentos da seguinte forma:

- Funções - Uma função é um conjunto de comandos que pode ser separado por um “bloco” de código visando o processamento de uma tarefa específica, onde esta função recebe parâmetros e **retorna** um valor.
- Procedimento - Os procedimentos são similares às funções, tanto na sua criação como no conceito de ter uma responsabilidade específica, porém nós utilizamos os procedimentos quando não há retorno, para mostrar uma mensagem por exemplo.

Utilizando o conceito de modularização podemos facilitar a construção de sistemas mais complexos dividindo as responsabilidades em blocos menores e específicos"



##                   Pensamento Computacional :thought_balloon:


"O pensamento Computacional é muito importante para tomada de decisões . É possivel ser um cidadão mais crítico, lógico, que saiba trabalhar em equipe  e resolver problemas.

Na educação está presente em quatro pilares:

- **Decomposição:** Ao se deparar com um problema complexo, o aluno deve dividi-lo em pequenas partes, assim conseguirá solucioná-las com mais facilidade; 

- **Reconhecimento de padrões:** Identificação de aspectos comuns nos processos para resolução do problema; 

- **Abstração:** Dá prioridade aos elementos que têm relevância, diferenciando-os daqueles que podem ser deixados de lado; 

- **Algoritmos:** Criação de um grupo de regras para a solução de problemas. ""

   Sites pesquisados: https://www.treinaweb.com.br/blog/guia-de-introducao-a-programacao
  
  https://idocode.com.br/blog/programacao/pensamento-computacional-por-que-e-importante-desenvolver/
