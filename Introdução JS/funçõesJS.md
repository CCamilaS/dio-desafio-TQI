# Funções

São blocos de comandos e instruções para a execução de
determinadas tarefas:

Ex.: function nomeDaFuncao() {
${instrucao};


nomeDaFuncao();

## Como declarar?

Geralmente se utiliza a palavra reservada “function” seguida de
parênteses “()” e chaves “{}”:

Ex.: function funcao() {
console.log(“mensagem”);
}

funcao();

() – indica que é um objeto do tipo function;
{} – indica que é um bloco de instrução;

[Nome do palestrante]
[Posição]
[Nome do curso]
[Nome da aula]
Aula 5| Etapa 2:
Funções com
parâmetros
Sintaxe Básica em JavaScript

_Funções com parâmetros_
As funções podem receber em sua declaração, parâmetros, que
servem como variáveis, onde sua atribuição pode ser feita durante
a chamada da função:

Ex.: function nomeDaFuncao(parametro) {
${instrucao};
}

nomeDaFuncao(valorDoParametro);

Funções com parâmetros

Ex.: function mensagem(primeiro, segundo) {
console.log(primeiro, segundo);
}

nomeDaFuncao(“Tudo certo”, “jovem!”);