# Anotações Lógica da Programação



\- Programar não é somente a linguagem de programação, mas a lógica por trás da resolução de problemas, que pode ser feita por diversos caminhos.

\- Lógica de programação significa contextualizar a lógica na programação de computadores, buscando a melhor sequência para a solução do problema. 

\- Metacognição : pensar sobre como você pensa.

\- Abstração: habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais. 



**- Algoritmo**: sequência de passos/ações para resolver um problema

(Importante para programação: indicar o início e o fim de determinada atividade). 

​	> Os programas são sequências de passos, e mudar a ordem desses passos interfere no funcionamento, gerando problemas.  

​	> Funções para repetir a mesma ação x vezes. 

​	> Funções condicionais (fazer x se y)

**\- Pseudocódigo:** forma genérica de se escrever um algoritmo, usando uma linguagem simples (nativa, ex: pt); usada por quem está aprendendo a programar. 



**\- Fluxogramas :** ferramenta usada para representar graficamente o algoritmo, ou seja, a sequência lógica e coerente do fluxo de dados. Representação esquemática de um processo; documentação dos passos necessários para a execução de um processo qualquer. 

(ex) Início > Entrada > Processamento > Saída > Fim

Os diferentes formatos de blocos no fluxograma indicam diferentes métodos, ou seja, representam diferentes coisas). Não existe um padrão específico, apenas precisa ser claro e coeso em si mesmo. 



**\- Variáveis :** um objeto/posição capaz de reter e representar um valor ou expressão. Espaço da memória do computador, destinado a um dado que é alterado durante a execução do algoritmo. 

   \> Sempre começa por letra; não pode ter espaços.

  \> Declaração de variáveis ( em um pseudocódigo: DECLARA nota1 : número; LEIA (nota1))

(***obs*:** o “DECLARA” serve para determinar o nome da variável “nota1” e estabelecer que é um número. Já o “LEIA” serve para pedir um valor para o usuário, que fica armazenado sob o nome da variável determinada (neste caso, “nota1”). 

\> Tipos de variáveis: Numéricas, Caracteres, Alfanuméricas, Lógicas (V ou F). 



**\- Constantes:** Valores imutáveis, que não são alterados durante a vida útil do programa. 

  \> ex: DECLARA pi : 3,14 (sempre que “pi” for usado, será o mesmo valor, tornando-se uma constante). 

 

\- **Programa Flowgorithm** 

  \> Declaração: estabelecer variáveis

  \> Entrada: receber dados de cada variável

  \> Atribuição: estabelecer determinada expressão, podendo usar as variáveis e os valores de entrada

  \> Saída: define a atribuição ou variável que o programa devolve. 

 

\- **Expressões aritméticas**

  \> utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variações. (ex: 50 + 50; total + 50...)

  \> Operadores: soma (+), subtração (-), multiplicação (*), divisão (/), potenciação (^), porcentagem (%). 

 

**\- Expressões literais**

  \> com constantes e/ou variáveis, que têm como resultado valores literais. São utilizadas para a atribuição de valor para uma variável ou constante. (ex: nome = “José da Silva”; média= (nota1 + nota2)/2) 

 

**\- Expressões relacionais**

  \> compostas por outras expressões ou variáveis numéricas com operadores relacionais. Retornam valores lógicos (verdadeiro / falso). 

  \> operadores: maior que (>), maior ou igual (>=), menor que (<), menor ou igual (<=), igualdade (==), diferente (!= ou <>).

 

\- Tomadas de decisão: necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução. 



**\- Concatenação**

​	\> Termo usado em computação usado para designar a operação de unir o conteúdo de duas strings (sequência de caracteres). 

​	\> Agrupamento de duas ou mais células (fórmulas, textos ou outras informações) em um mesmo resultado. Útil para exibir informações pro usuário (saída de dados). (ex: nome + sobrenome concatenados em nomecompleto).

​	\> No Flowgorithm usar o caractere “&”. Por exemplo, em saída: [“Sua média é: “ & media] > assim, os dois (ou mais) strings aparecem juntos na saída, mesmo sendo diferentes células de informação.

 

**\- Estrutura de repetição**: Estrutura que permite executar mais de uma vez o comando ou o conjunto de comandos, de acordo com uma condição ou com um contador. 

  	\> Pode ser aplicado por uma estrutura de alternativas, na qual continua caso determinada condição seja verdadeira ou falsa.

 

**\- Linguagens de programação:** escrita formal, com instruções e regras usadas para gerar problemas. Pode ser desenvolvido em qualquer dispositivo que suporte sua execução. Meio de comunicação entre humanos e dispositivos. É preciso fornecer para a máquina todas as informações possíveis, já que aquilo que é óbvio para uma pessoa não o é para o computador. 

​	\> Linguagens de Alto nível (sintaxe se aproxima mais da nossa linguagem); e de Baixo nível (se aproxima mais da linguagem de máquina, precisa ter conhecimento direto da arquitetura do computador. 

 

**\> Compilação:** o código fonte é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido pelo processo denominado compilação. São transformadas em um programa executável. 

**\> Interpretação**: nessas linguagens, o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador. 

 

**\- Portugol:** pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independente da linguagem de programação. Pensar no problema em si e não no equipamento que vai executar esse algoritmo. 



### Portugol Studio

- O programa começa e termina com chaves (abre e fecha : {})

- Cada comando é dado entre chaves – indicando início e fim. 

 

* **Desvio condicional** 

\> é utilizada a palavra reservada “se”, a condição a ser testada é colocada entre parênteses e as instruções que devem ser executadas se for verdadeira entre chaves. 

\> para determinar o comando a executar caso a expressão seja falsa, pode ser usado o “senão”. 

\> caso: semelhante a se e senão, e reduz a complexidade na escolha de diversas opções. Um “menu” com várias opções diferentes. Neste comando, não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos. 

   \> Um menu com várias opções poderia ser feito por meio de uma cadeia de comandos “se”, no entanto, esta forma seria inconveniente para listas muito grandes. 



- **Laços de repetição**

 \- estrutura para executar mais de uma vez o mesmo comando ou conjunto de comandos de acordo com uma condição ou contador. 

 \- usar o comando “faca”, a seguir, entre chaves{}, colocar o comando/conjunto de comandos. Depois das chaves, usar o comando “enquanto” e, entre parênteses (), colocar a condição para a repetição.

 

- **Matrizes e vetores**

   \> matriz: coleção de variáveis do mesmo tipo, acessíveis com um único nome e armazenados contiguamente (em sequência) na memória.

\> a individualização de cada variável de um vetor é feita através do uso de índices (localizar a posição de determinada informação dentro da matriz);

\> os vetores são matrizes de uma só dimensão (ex: só colunas).

   \> os vetores serão declarados por “cadeia/inteiro/real variável []”, indicando o número de posições dentro dos colchetes. 

   \> as matrizes serão declaradas por “cadeia/inteiro/real variável[][]”, indicando o número de linhas e colunas, respectivamente, dentro de colchetes separados. 

\> sempre começar a numeração por 0. 

Ex.: vetor

cadeia frutas [4]:

frutas[0]= ”Maçã”

frutas[1]= ”Pera”

frutas[2]= “Uva”

frutas[3]= “Laranja”

escreva(frutas[x])



Ex.: matriz 

cadeia cesta [][] = {{“Maça”, “100”}, {“Pêra”, “200”}, {“Melão”, “300”}}

escreva(“Fruta: “ + cesta[x][y] + “, Quantidade: “ + cesta[x][y]). 

(obs: ao colocar as chaves sem nada depois da variável, o programa faz essa contagem automaticamente).



#### Comandos Portugol

```
- {} : início e final do programa e de cada comando
- real: definir variáveis e classificar como número real.
- caracter: recebe uma letra
- cadeia: recebe cadeia de caracteres (palavra)
- escreva (...): define uma saída de texto para o programa. 
- leia (variável): pede que o usuário insira determinada informação, que ficará armazenada na variável determinada. 
- + : para concatenar informações em uma mesma saída.  
- se : expressão condicional (Obs: a expressão fica dentro de parênteses, e entre chaves fica o comando caso a condição seja verdadeira)
- “\n” : quebra de linha (em caso de saída de texto)
- //(...) : Comentário (não faz parte do programa, mas serve para se guiar e ajudar outras pessoas que o leem entenderem melhor para que serve cada parte, etc.
- caso: bloco de comandos para diversas opções de escolha do usuário. “pare” é usado para parar os comandos entre cada caso. 
- faca {}, enquanto(): laço de repetição. 
- variável ++: variável = variável + 1. 
- cadeia/real... Vetor[x]: declara um vetor de x posições.
- cadeia/real...  Matriz [x][y]: declara uma matriz de x linhas e y colunas. 
(“Matriz” e “Vetor” serão substituídos pelo nome da variável)
```

