# Neovim-Tutorial
### Tutorial básico de como utilizar o neovim


### Tópicos
1. [Introdução](#introducao)
2. [Modo Normal](#modo_normal)

<div id='introducao'/>

## Introdução

Neovim possui vários modos de interação, cada um deles tem sua especificidade e alteram a maneira de interagir com o conteúdo. Para alternar de um modo para o outro basta pressionar a tecla correspondente a partir do modo normal. Por exemplo, se estivermos no modo de inserção e quisermos entrar no modo visual, teremos que apertar a tecla `ESC` para retornar ao modo normal e depois pressionar `v`. Se estivermos no modo normal e quisermos alternar para o modo de inserção, basta apenas apertar a tecla `i`.

Ao entrarmos no neovim, por padrão, somos colocados no modo `normal`. Para checarmos em que modo  atualmente estamos podemos verificar a mensagem posicionada no canto inferior esquerdo do terminal.


<img src="/view/img/normal_mode.png">
<img src="/view/img/insert_mode.png">
<img src="/view/img/visual_mode.png">


MODO      | TECLA | DESCRIÇÃO
----------|-------|-------------------------------------------------------------------------------------------------
`{normal}`|`ESC`  |modo padrão do neovim, utilizado para vanegar pelo código.
`{insert}`|`i`    |modo de edição livre, permite a inserção de caracteres.
`{visual}`|`v`    |modo utilizado para selecionar parte do código, nele é possível selecionar grupos de caracteres.

## Modo Normal <div id='modo_normal'/>
O modo normal é a porta de entrada para os outros modos e também nos permite navegar pelo código de forma ágil sem necessitar colocar a mão no mouse para mover o cursor.

Para navegarpelo código podemos utilizar as seguites teclas:

TECLA | FUNÇÃO
------|--------------------
`h`   | move para direita
`j`   | move para baixo
`k`   | move para cima
`l`   | move para esquerda

No modo normal temos acesso ao terminal de comandos, que pode ser acessado digitando `:` seguido pelo comando desejado e `<Enter>`para executálo

exemplo: `:` `<comando desejado>` `<Enter>`



