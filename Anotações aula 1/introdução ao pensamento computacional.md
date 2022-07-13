# Introdução ao pensamento computacional.
O pensamento computacional se divide em pilares, são 4:

- Decomposição
- Reconhecimento de padrões 
- Abstração
- Design de algoritmos

## Habilidades complementares:

Raciocínio Lógico – forma de pensamento estruturado, ou raciocínio que permite encontrar a conclusão ou determinar a resolução de um problema.

	             - Indução = fenômeno observado
Classificado -    - Dedução = previsões e explicações para o fenômeno
               - Abdução = premissa, a partir de algo observado você pressupõe alguma coisa
	             (a grama está molhada = premissa: se a grama está molhada, então choveu/                              n                          nem sempre a premissa vai estar certa)

lembrar de separar os pontos dos problemas, pra saber como resolver. Escrever o que é o problema e como posso resolver vai me ajudar a ver com mais clareza.

## PILARES:

DECOMPOSIÇÃO
É preciso compreender como executar cada etapa de um pensamento computacional.
Se um problema é complexo, eu preciso dividí-lo em problemas menores que sejam resolvíveis e facéis de gerenciar.

				                     ESTRATÉGIA
Processo de quebrar e determinar partes
Menores e gerenciáveis.

Combinar os elementos recompondo o 
Problema original. 

Ordem de execução de tarefas menores 


### Então, como decompor?
identifico e coleto o problema, agrego dados e entrego a funcionalidade.

Reconhecimento de Padrões

•	Modelo base
•	Estrutura invariante
•	Repetição
Reconhecer padrões – similaridades e diferenças
Por que determinar padrões?
- Detectando padrões, eu generalizo com o objetivo de ter resolução para problemas diferentes.
- Determino padrões por meio de:            Categorias = Tipo de media, dependem do domínio      .        .                                                                                     (classificar o contexto)
				                 Classes = Grau de similaridade entre grupos   .  .  . . . . . . .                                                                     conhecidos x objetos desconhecidos

Abstração
Passar pro código tudo oq eu consegui extrair com o pensamento computacional.

TIPOLOGIA E VARIÁVEIS (7 ETAPAS)
PRIMEIRA ETAPA TIPOLOGIA E VARIÁVEIS
A FUNÇÃO DO PC É PROCESSAR INFORMAÇÕES QUE EU PASSO PRA ELE, ELE FAZ ISSO POR MEIO DE DADOS E INSTRUÇÕES.
Os dados são tratados e processados. Os dados são feitos por numéricos e caracteres e lógicos esses são os dados primitivos.
O mais comum é o numérico. Está dividido entre inteiro e real. 
O caractere é tudo aquilo não representado por número. Porém um número pode ser um caractere, desde que bem representado como string ou como caractere.
Caractere booleano, atrelado a lógica booleana, só há dois resultados possíveis (verdadeiro e falso)
O que é variável?  Variável é uma estrutura mutável e inconstante, é importante dar sentido a minha variável. Colocar nomes nelas pra ficar fácil entender o código. Dentro disso o papel da variável pode ser de ação ou controle. A ação modifica o estado do algorítimo e o controle vai definir uma regra no algorítimo.
Constante não muda, o valor que eu colocar na minha constante vai ser o mesmo até o fim do código. 

INSTRUÇÕES PRIMITIVAS
 As instruções ditam oq vai acontecer no algoritmo, normalmente é número.
Ou seja, eu uso as linguagens de programação, é importante lembrar que cada linguagem se refere a um objeto de uma forma. Uma dica muito importante é colocar no papel oq eu quero que o algoritmo faça, assim vou ter uma ideia melhor doq fazer no código
ESTRUTURAS CONDICIONAIS E OPERADORES
Estrutura condicional diz que há uma condição que se satisfeita uma determinada ação vai ser realizada, nessa estrutura eu uso os operadores relacionais

=    igual a
<> diferente de
> maior que
< menor que
>= maior ou igual a
<= menor ou igual a

E também tem os operadores lógicos
and (e)
or (ou)
not (não)
eu uso esses operadores qdo preciso de uma resposta simples, como sim ou não.

ESTRUTURAS DE REPETIÇÃO
Eu uso qdo preciso que um pedaço do código seja repetido mais de uma vez com diferentes valores dentro das variáveis.
As repetições ajudam a reduzir linhas, fica um código limpo, e reduz os erros

VETORES E MATRIZES
O vetor vai ser uma sequencia de tipos de dados. Um vetor é uma variável que possui uma sequencia um tamanho pré-fixado que recebe N valores.

FUNÇÕES
As funções vêm da ideia da matemática.
São blocos de instruções que realizam tarefas específicas. Decomposição do algoritmo.

INSTRUÇÕES DE ENTRADA/SAÍDA
consiste na inserção e recebimento de dados do mundo real por meio de ação de alguma interface, seja teclado, mouse, arquivos, entre outros.
Existem dois tipos de saída no algoritmo, saída programada ou saída por interrupção
Programada = condicional ou não
A saída na programação é o código

INTRODUÇÃO ÀS LINGUAGENS DE PROGRAMAÇÃO (5 ETAPAS)
INTRODUÇÃO
HISTÓRIA DA COMPUTAÇÃO.
Linguagem de programação é um método composto por um conjunto de regras sintáticas e semânticas de implementação de um código fonte.
Cada linguagem possui um conjunto de palavras próprias. Pode ser traduzido ou interpretado.

COMO UM PC ENTENDE UM PROGRAMA?
 Um código fonte é um código que eu gero a partir de um programa, pode ser traduzido ou interpretado.
TRADUÇÃO = GERAÇÃO DO PROGRAMA OBJETO, EXECUÇÃO DO PROGRAMA OBJETO
INTERPRETAÇÃO = PROGRAMA FONTE INTERPRETADO DIRETAMENTE (RUBY, PYTHON)
Interpretação torna o programa mais lento.
TRADUÇÃO = EXECUÇÃO RÁPIDA, PROGRAMAS MENORES
INTERPRETAÇÃO = MAIS FLEXIBILIDADE, MAIS FÁCIL, PORÉM MAIS LENTA


CARACTERÍSTICA DE UM PROGRAMA
QUAIS SÃO AS BOAS PRÁTICAS DA PROGRAMAÇÃO?
São elas:
 	Legibilidade – ter boa leitura, coerência
 	Redigibilidade – coerência nas instruções, código de fácil escrita, simples escrita, bater o olho e entender
 	Confiabilidade - executar oq promete, 
 	Custo - baixo custo, código eficiente, treinamento, codificação, compilação, execução e infra-estrutura.
 	Atualizações
 	Uso para IA
 	Disponibilidade para mercado
 	Comunidade ativa
 	Adoção pelo mercado

ANÁLISES DE CÓDIGO
Análise léxica, sintática e semântica
LÉXICA
Leitura. A função dela é ler o código fonte.
Nesse processo ela vai:
Particionar (elementos chamados tokens) e classifica-los, classificar e eliminar oq não for necessário como espaços em branco e comentários
SINTÁTICA
A sintaxe de um programa é a forma que ele define qual a estrutura usada naquela linguagem específica. Cada linguagem te uma sintaxe associada
SEMÂNTICA
A semântica estuda os significados das palavras e sinais da linguagem, é a lógica do programa.
O erro de semântica é preciso ser debugado pelo programador linha a linha. 

PARADIGMAS DE PRGRAMAÇÃO
Paradigma possui regras para a resolução de problemas limitado a um contexto específico.
Quais existem?
Orientação a objetos (Ruby)
Procedural (ideia de sequência)
Funcional (instruções baseadas em funções)
Estruturado (blocos alinhados)
Computação distribuída (módulos independentes)
Lógico 
Os mais usados são:
Orientado a objetos
Estruturado

PARADIGMA ESTRUTURADO
Usado para:
- problemas simples e diretos
- aprender programação
É importante aprender o C pq é oq mais usa em faculdades e aprendizado

ORIENTAÇÃO A OBJETO
Na orientação a objeto, tudo é objeto.
Classe e método, pensar em como eu faço
O método é associado a uma classe.

Classificação – classe
O que é um objeto? 
Aloca em memória operações associadas a objetos (poo)
Aloca em memória operação desassociada, é variável (estruturada)

PILARES DA ORIENTAÇÃO A OBEJTOS
herança, encapsulamento, polimorfismo, abstração.

HERANÇA
- CLASSE
Classe filha herda características de classe mãe, mas pode ter características próprias.
Classe mãe – comportamento geral
Classe filha – comportamento específico
Poo – reuso de código
Estruturado – problemas específicos
Pensar em qual é o problema e qual seria melhor usar, poo ou Paradigma estruturado.
 	Linguagem interpretada é mais lenta

ALGORÍTMOS EM PORTUGOL
Usar o portugol web studio pra praticar raciocínio lógico.
