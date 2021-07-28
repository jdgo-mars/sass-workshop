# sass-workshop

## Atalhos Uteis VSCode
* Abrir um ficheiro `ctrl/cmd + p` e escrever nome do ficheiro
* Fazer uma acao `ctrl/cmd + shift + p` escrever o nome da acao (e.g. Simple Browser: Show)
* Abrir/Fechar terminal `ctrl + ` `
* Abrir/Fechar sidebar `ctrl/cmd + b `

## Estrutura 
Os scripts para correr o projeto estao especificados dentro do ficheiro package.json ([Mais info sobre o package.json](https://nodesource.com/blog/the-basics-of-package-json-in-node-js-and-npm/)), na secao `scripts`.
Existem duas tarefas:
1. `conceitos` que engloba os conceitos de sass estudados nas aulas.
2. `projeto` que e um website desenvolvido usando sass.

O codigo Sass encontra-se na pasta `src/scss/`.
E esta dividida em duas pastas uma `conceitos` e outra `projeto`.

Os ficheiros css sao compilados para a pasta `assets/css/`.

Existem duas paginas html uma `@conceitos` e outra `@projeto` (o `@` nao significa nada especifico, e apenas para as duas paginas estarem bem visiveis na sidebar).

### Outros ficheiros
* gitpod.yml e um ficheiro de configuracao do (Gitpod)[https://www.gitpod.io/docs/config-gitpod-file].
* .gitignore permite ignorar ficheiros que nao queremos guardar no nosso repositorio, como e o caso do ficheiros css.
* pasta .vscode configuracoes do vscode como por exemplo o tamanho de letra.

## Como correr a pagina com os conceitos de SASS
1. Abrir o terminal
2. Digitar o seguinte comando `npm run conceitos`
3. Para parar a tarefa/processo `ctrl + c`

## Como correr o projeto
1. Abrir o terminal
2. Digitar o seguinte comando 
3. Para parar a tarefa/processo `ctrl + c`
