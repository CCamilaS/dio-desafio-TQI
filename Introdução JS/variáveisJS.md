# Tipagem?

A tipagem funciona como uma regra de uso de dados, quanto
mais forte for a tipagem, mais obrigatório é a declaração do tipo
de dado.
A tipagem em JavaScript é fraca, a declaração dos dados acontece
de modo dinâmico.

Ex.: Ao criarmos uma variável com valor entre aspas (“valor”) o
JavaScript já converte o dado para o tipo String.

### Tipagem

Ex.: var numero = 1;
// o JavaScript já converte o valor 1 para o tipo Number.

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula] Aula 2| Etapa 2:
Declaração de variáveis

## Sintaxe Básica em JavaScript

### Tipos primitivos

As variáveis em JavaScript podem guardar tipos de dados que
chamamos de tipos primitivos

Variáveis podem guardar valores dos tipos: Boolean; null;
undefined; Number; String; Array; Object; Function.

### O que são variáveis?

São dados que variam. Ora, ora Diana eu nem pensei nisso.

Imagina uma caixa, tu pode colocar quase qualquer coisa dentro
dela, pode ser uma lista de nomes, cartões com números, objetos
no geral...

Variáveis funcionam dessa forma
Como uma caixa que guarda valores

### Declaração de variáveis
Existem 3 modos de declarar as variáveis em JavaScript:

var – escopo global e local, pode ter seu valor alterado, se não
tiver um valor inicial será tratada como null;

let – escopo local de bloco, pode ter seu valor alterado, se não
tiver um valor inicial será tratada como null;

const – escopo local de bloco, somente leitura, o valor inicial é
obrigatório e não pode ser alterado.

### Escopo

O escopo em JavaScript define a limitação e visibilidade de um
bloco de código.

Escopo global – quando a variável é declarada fora de qualquer
bloco, sua visibilidade fica disponível em todo o código.

Escopo local – quando a variável é declarada dentro de um bloco,
sua visibilidade pode ficar disponível ou não.

# Regras de Uso de Variáveis
• Iniciar com letras, underscore _ ou cifrão $; Não iniciar com número.
Ex.: var 1nome ❌
var nome || var _nome ✔

• Não usar espaços (use o camelCase ou _);
Ex.: var nome completo ❌
var nomeCompleto || var nome_completo✔

• Não usar palavras reservadas;
Ex.: var function ❌

• Declarar variáveis no topo do bloco de código.

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula]
Aula 2| Etapa 3:
Diferenças entre atribuição,
comparação e comparação
idêntica

## Sintaxe Básica em JavaScript

- Atribuição

O sinal de igualdade “=“ em JavaScript, significa atribuição.

Ex.:
como declarar: var nome = “meu nome”;
como ler: variável nome recebe o valor meunome;

- Comparação

Para fazermos uma comparação de valores em JavaScript usamos
“==“.

Ex.:
como declarar: "0" == 0; ;
como ler: “0” tem o valor igual a 0?

// nesse caso retorna true

- Comparação idêntica

Para fazermos uma comparação de valores e tipos em JavaScript
usamos “===“.

Ex.:
como declarar: "0" === 0; ;
como ler: “0” tem o valor e o tipo idêntico a 0?

// nesse caso retorna false

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula] Aula 2| Etapa 4:
Operadores aritméticos,
relacionais e lógicos
Sintaxe Básica em JavaScript

### Operadores aritméticos
São tipos de operadores matemáticos com valor numérico:

• + adição;
• - subtração;
• * multiplicação;
• / divisão real;
• % divisão inteira;
• ** potenciação;

### Operadores relacionais

São tipos de operadores que consultam a relação entre valores:

• > maior que;
• < menor que;
• >= maior ou igual a;
• <= menor ou igual a;

### Operadores lógicos

São tipos de operadores que consultam valores lógicos:

• && - “e” – considera que todos os valores sejam true;
• || - “ou” – considera que qualquer valor seja true;
• ! - “não” – inverte o valor de true para false ou vice-versa;

## Estruturas condicionais

São instruções para realizar determinadas tarefas a partir de uma
condição, seja de decisão ou repetição;

Ex.: Um jogo precisa mudar o placar toda vez que um jogador
marca pontuação;

0 01

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula] Aula 4| Etapa 2:
Estruturas de decisão

Sintaxe Básica em JavaScript

_if_

Podemos usar as palavras reservadas “if” para estabelecer uma
condição:
Ex.: var jogador1 = 0;
var jogador2 = 0;

if (jogador1 > 0) {
console.log(‘jogador1 marcou ponto’);
}
// como ler: se o jogador1 tiver valor maior que 0
ele marcou ponto.

_else_

No caso de a condição não ser atendida podemos usar o “else” :
Ex.: var jogador1 = 1;
var jogador2 = 0;

if (jogador1 > 0) {
console.log(‘jogador1 marcou ponto’);
} else {
console.log(‘ninguem marcou ponto’);
}

_else if_

Caso haja mais de uma condição usamos o “else if“.
Ex.: var jogador1 = 1;
var jogador2 = 0;

if (jogador1 > 0) {
console.log(‘jogador1 marcou ponto’);
} else if (jogador2 > 0) {
console.log(‘jogador2 marcou ponto’);
} else {
console.log(‘ninguém marcou ponto);
}

- ninho de if

Podemos também usar o “if” dentro de um outro “if”, chamamos
isso de aninhamento de if’s ou ninho de if’s.
Ex.: if (jogador1 = -1) {
if (jogador1 > 0) {
console.log(‘jogador 1 marcou ponto’);
} else {
console.log(‘ninguém marcou ponto’);
}
} else {
console.log(‘jogador inválido’);
}

_If ternário_

Podemos também fazer uma verificação em uma única linha
usando o “if” ternário:

Ex.: [condição] ? [instrução1] : [instrução2];

jogador1 > 0 ? console.log(‘marcou ponto’) : console.log(‘não
marcou ponto”);

// lembre de usar a interrogação “?” e dois pontos “:”

Usando switch/case

O “switch/case” funciona como uma estrutura condicional
também;

Ex.: switch (${expressao}) {
case 1:
${instrucao};
break;
case 2:
${instrução};
break;
}

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula] Aula 4| Etapa 3:
Estruturas de repetição

Sintaxe Básica em JavaScript

### Laços de repetição

São estruturas condicionais que repetem uma instrução até atingir
determinada condição:

• For;
• For/in;
• For/of;
• While;
• Do/while;

_For_

Funciona como uma repetição de instrução até que a condição
seja falsa:

for ([expressaoInicial]; [condicao]; [incremento]) {
declaracao }

Ex.: var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

for (let i = 0; i < array.length; i++) {
console.log(i);
}

_For/in_

Funciona como uma repetição a partir de uma propriedade:

for ([indice] in [objeto ou array]) {
declaracao }

Ex.: var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

for (i in array) {
console.log(i);
}

_For/of_

Funciona como uma repetição a partir de um valor:

for ([indice] of [array]) {
declaracao }

Ex.: var array = [‘valor1’, ‘valor2’, ‘valor3’, ‘valor4’]

for (i of array) {
console.log(i);
}

_For/of_

O For/of não funciona com objetos pois as propriedades variam,
diferentes do índice em um array que sempre serão números
inteiros.

Mas e se eu quiser pegar o valor mesmo assim?
Ex.: for (i of object.propriedade) {
console.log(i);
}
// porém cada caractere dentro do valor será
Impresso em linhas separadas.

_While_

Executa uma instrução “enquanto” determinada condição for
verdadeira, a verificação é feita antes da execução;

Ex.: var a = 0;
while (a < 10) {
a++;
console.log(a);
}
// como ler: enquanto a variável a for menor que 10 ela
vai receber mais um e imprimir no console.

_Do/while_

Executa uma instrução “até que” determinada condição seja falsa,
a verificação é feita depois da execução;
Ex.: var a = 0;
do {
a++;
console.log(a);
} while (a < 10)

//como ler: a variável a vai receber mais um e imprimir
no console até que seu valor chegue a 10