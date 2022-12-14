# Neovim-Tutorial
### Tutorial básico de como utilizar o neovim


### Tópicos
1. [Introdução](#introducao)
2. [Modo Normal](#modo_normal)

<div id='introducao'/>

## Introdução
Para iniciar o Neovim devemos abrir o terminal e inserir o seguinte comando:

```bash
$ nvim nome_do_arquivo
```

Neovim possui vários modos, cada um deles tem sua especificidade e altera a maneira de interagir com o conteúdo. Para alternar de um modo para o outro basta pressionar a tecla correspondente a partir do modo normal. Por exemplo, se estivermos no modo normal e quisermos alternar para o modo de inserção, basta pressionar a tecla `i`. Se estivermos no modo de inserção e quisermos entrar no modo visual, teremos que apertar a tecla `ESC` para retornar ao modo normal e depois pressionar `v`.

MODO      | TECLA | DESCRIÇÃO
----------|-------|-------------------------------------------------------------------------------------------------
`{normal}`|`ESC`  |modo padrão do neovim, utilizado para navegar pelo código e acessar o terminal de comandos.
`{insert}`|`i`    |modo de edição livre, permite a inserção de caracteres no arquivo.
`{visual}`|`v`    |modo utilizado para selecionar parte do código, nele é possível selecionar grupos de caracteres.

Ao entrarmos no neovim, por padrão, somos colocados no modo `normal`. Para checarmos em que modo  atualmente estamos podemos verificar a mensagem posicionada no canto inferior esquerdo do terminal.


  1. Normal <img src="/view/img/normal_mode.png">
  2. Insert <img src="/view/img/insert_mode.png">
  3. visual <img src="/view/img/visual_mode.png">
  
  <div id='modo_normal'/>

## Modo Normal 
O modo normal é a porta de entrada para os outros modos e também nos permite navegar pelo código de forma ágil sem necessitar colocar a mão no mouse para mover o cursor, tudo é feito no teclado.

Para mover o cursor pelo código podemos utilizar as seguites teclas:

TECLA | FUNÇÃO
------|--------------------
`h`   | move para direita
`j`   | move para baixo
`k`   | move para cima
`l`   | move para esquerda



No modo normal temos acesso ao terminal de comandos, que pode ser acessado digitando `:` seguido pelo `comando` desejado e `<Enter>` para executá-lo.
```
: <comando> <Enter>
```
Os dois comandos mais básicos que podemos utilizar são o de salvar e sair.

TECLA | DESCRIÇÃO
-------|----------
:w     | salva todas as alterações no documento
:q     | fecha o neovim se todas as alterações estiverem salvas
:wq    | salva todas as alterações e fecha o neovim
:q!    | força o fechamento sem salvar as alterações

