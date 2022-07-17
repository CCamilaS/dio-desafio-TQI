# INTRODUÇÃO AO GIT E GITHUB

#### Comandos e flags pro git no Windows:

- Cd – (change directory) mudar pra uma pasta específica no usuário
- Cd  / - se eu der ENTER eu mudo pra base do diretótio C: e saio do usuário
- Cd .. – uso esse comando pra sair da pasta e voltar pra base do diretório
- dir – uso no prompt pra listar diretórios (pastas) dentro do usuário
- mkdir – (make directory) criar pasta
- del + nome do repositório – delete, vai deletar ARQUIVO não um repositório
- rmdir /S /Q – (remove directory) esse comando apaga o repositório junto com os arquivos dentro dele
- rmdir – apaga o repositório apenas se ele estiver vazio
- cls – (clear screen) limpar o prompt de comando
- TAB – autocompleta nomes de pastas e diretórios, eu posso usar pra procurar nomes extensos dentro dos diretórios
- Pra limpar no git bash eu uso ctrl + l
- No terminal > - é um redirecionador de fluxo para um arquivo
- Echo – printa oq vc escrever e te devolve
- Pra navegar entre os comandos que já dei no terminal eu uso a seta pra cima (muito útil pra não precisar digitar comandos longos de novo)
- Mv – mover arquivo pra dentro de uma pasta pelo terminal
- Git add -  adicioa o commit
- Git add * - pega tudo o que foi comitado e adiciona
- Git remote add origin – pra adicionar arquivos para o meu repositório do git hub

## Ordem de códigos git pra subir pro git hub

- Git add *
- Git commit -m
- Git push origin master

#### SILENCE FOR SUCESS – se der tudo certo na criação da pasta, o terminal ficará em silêncio, ou seja, ele vai me voltar um resultado limpo.

- Sha1 – é um tipo de criptografização do código, mostra se foram feitas alterações ou não por meio de chaves geradas de 40 caracteres. 

### TRÊS TIPOS BÁSICOS DE OBJETOS DO GIT

- Blobs – o git lida com dados por meio de objetos. O blob guarda os arquivos dentro dos objetos, Blob armazena metadados, ele tem o tipo do objeto (Blob), tamanho do arquivo, \0 e o conteúdo do arquivo, seja binário ou em texto.

- Trees – a tree armazena blob, blob é o bloco básico de composição, a tree armazena e direciona para diferentes tipos de blobs. A arvore tbm contém metadados. A arvore guarda o NOME do arquivo. O blob só guarda o sha1 do arquivo.  

- Commits – o commit junta blob e tree, 

#### CHAVE SSH E TOKEN
- Chave SSH – é uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas. 

## DESAFIO GIT/GITHUB

- Pra adicionar um link útil no READ.ME eu escrevo [nome do link] (link aqui)
