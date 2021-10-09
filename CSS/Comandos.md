# Comandos CSS

A documentação completa do CSS fica em:

[Documentação MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[Documentação CSS](https://devdocs.io/css/)
[W3 Schools](https://www.w3schools.com/cssref/)

Abaixo temos um resumo com os códigos mais usados no CSS

### COR

`color`

### TEXT DECORATION

`text-decoration`
atributos (`underline`) - Sublinhado
atributos (`overline`) - Linha acima do texto
atributos (`line-through`) - Riscado

### FONT SIZE

`font-size`
atributos (`16px`) - Tamanho da Fonte

### FONT STYLE

`font-style`
atributos (`italic`) - Italico

### TEXT TRANSFORM

`text-transform`
atributos (`capitalize`) - Coloca a primeira letra de cada palavra em maisucula
atributos (`uppercase`) - Coloca tudo em maisucula
atributos (`lowercase`) - Coloca tudo em minuscula

### TEXT ALIGN

`text-align`
atributos (`justify`) - Justifica o texto
atributos (`left`) - Justifica o texto a esquerda
atributos (`right`) - Justifica o texto a Direita
atributos (`center`) - Justifica o texto ao centro

### LIST STYLE TYPE

`list-style-type`
atributos (`circle`) - Coloca bolinhas sem preenchimento
atributos (`disc`) - Coloca bolinhas com preenchimento
atributos (`decimal`) - Coloca numeros ordenados
atributos (`decimal-leading-zero`) - Coloca numeros ordenados com 0 a esquerda
atributos (`upper-alpha`) - Coloca letras minusculas em ordem alfabetica
atributos (`lower-alpha`) - Coloca letras maisuculas em ordem alfabetica
atributos (`lower-roman`) - Coloca numeros romanos minusculos em ordem alfabetica
atributos (`upper-roman`) - Coloca numeros romanos maisuculos em ordem alfabetica

### TEXT DECORATION

`text-decoration`

atributos (`underline`) - Sublinhado
atributos (`overline`) - Linha acima do texto
atributos (`line-through`) - Riscado

## FLEX BOX

### FLEX DIRECTION

`flex-direction`

atributos (`row`) - Direção do Texto da esquerda para direita da tela
atributos (`row-reverse`) - Direção do Texto da direita para esquerda da tela
atributos (`column`) - Direção do Texto da cima para baixo
atributos (`column-reverse`) - Direção do Texto da baixo para cima

### FLEX WRAP

`flex-wrap`

atributos (`nowrap`) - Não permite a quebra de linha
atributos (`wrap`) - Permite a quebra de linha assim que um dos items não cabe na linha
atributos (`wrap-reserve`) - Permite a quebra de linha assim que um dos items não cabe na linha, no sentido contrário

### FLEX fLOW

União do Wrap com direction

`flex-flow`

atributos (`row nowrap`) - Direção do Texto da esquerda para direita da tela e Não permite a quebra de linha
atributos (`row wrap`) - Direção do Texto da esquerda para direita da tela e permite a quebra de linha
atributos (`row wrap-reverse`) - Direção do Texto da esquerda para direita da tela e Permite a quebra de linha assim que um dos items não cabe na linha, no sentido contrário.

atributos (`row-reverse nowrap`) - Direção do Texto da direita para esquerda da tela e Não permite a quebra de linha
atributos (`row-reverse wrap`) - Direção do Texto da direita para esquerda da tela e permite a quebra de linha
atributos (`row-reverse wrap-reverse`) - Direção do Texto da direita para esquerda da tela e Permite a quebra de linha assim que um dos items não cabe na linha, no sentido contrário.

atributos (`column nowrap`) - Direção do Texto da cima para baixo e Não permite a quebra de linha
atributos (`column wrap`) - Direção do Texto da cima para baixo e permite a quebra de linha
atributos (`column wrap-reverse`) - Direção do Texto da cima para baixo e Permite a quebra de linha assim que um dos items não cabe na linha, no sentido contrário.

atributos (`column-reverse nowrap`) - Direção do Texto da baixo para cima e Não permite a quebra de linha
atributos (`column-reverse wrap`) - Direção do Texto da baixo para cima e permite a quebra de linha
atributos (`column-reverse wrap-reverse`) - Direção do Texto da baixo para cima e Permite a quebra de linha assim que um dos items não cabe na linha, no sentido contrário.

### JUSTIFY content

Justifica o Conteudo
`justify-content`

atributos (`flex-start`) - Inicio do Container
atributos (`flex-end`) - Final do Container
atributos (`center`) - ao centro do Container
atributos (`space-between`) - Cria um espaçamento igual entre os elementos
atributos (`space-around`) - Os espaçamentos do meio são duas vezes maior que o inicial e final

### ALIGN ITEMS

Alinhamento dos Items Horizontal
`align-items`

atributos (`center`) - alinhamento dos items ao centro
atributos (`stretch`) - Defaul, e os flex items cresçam igualmente
atributos (`flex-start`) - alinhamento dos items no inicio
atributos (`flex-end`) - alinhamento dos items no final
atributos (`baseline`) - alinhamento de acordo com a linha base da tipografia dos itens

### ALIGN CONTENT

Alinhamento dos Items Vertical
`align-content`

atributos (`center`) - alinhamento dos items ao centro
atributos (`stretch`) - Defaul, e os flex items cresçam igualmente
atributos (`flex-start`) - alinhamento dos items no inicio
atributos (`flex-end`) - alinhamento dos items no final
atributos (`space-between`) - Cria um espaçamento igual entre os elementos
atributos (`space-around`) - Os espaçamentos do meio são duas vezes maior que o inicial e final

### FLEX GROW

`flex-grow`
atributos (`0`) - Espaçamento dentero do item depois do texto
atributos (`1`) - Espaçamento dentero do item depois do texto
atributos (`2`) - Espaçamento dentero do item depois do texto
atributos (`3`) - Espaçamento dentero do item depois do texto
etc...

### FLEX BASIS

`flex-basis`
atributos (`auto`) - Caso o item não tenha tamanho, este será proporcional ao cointeudo do item
atributos (`px` or `%` or `em`) - Valores exattos previamente definios
atributos (`2`) - Espaçamento dentero do item depois do texto
atributos (`0`) - terá relação com a definição do flex-grow

### FLEX SHRINK

`flex-shrink`
atributos (`auto`) -Caso o item não tenha tamanho, este será proporcional ao cointeudo do item
atributos (`px` or `%` or `em`) - Valores exattos previamente definios
atributos (`2`) - Espaçamento dentero do item depois do texto
atributos (`0`) - terá relação com a definição do flex-grow

### FLEX

Junção do Grow, Shrink e Basis - nessa ordem
`flex`

### Order

Ordena os item selcionados no flex de acordo com a numeração da classe
`order`

### ALIGN SELF

`align-self`

atributos (`auto`) - valor pádrão, irá respeitar a definição de align-items do container
atributos (`flex-start`) - inicio do container
atributos (`flex-end`) - final do Container
atributos (`center`) - relativo ao centro de acordo com o eixo x ou Y
atributos (`baseline`) - utiliza linha base da tipografia
atributos (`stretch`) - Ocupa todo o espaço
