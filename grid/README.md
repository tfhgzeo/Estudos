# CSS GRID

## GRID

-   Bidimensional
-   Divisão de toda a página em linhas e colunas
-   Colocar elementos aonde quiser nesse divisão

## GRID OU FLEXBOX

-   Grid: Duas dimensões (Colunas e Linhas)
-   Flexbox: Uma dimensão (Ou Coluna ou Linha)
-   Um complementa o trabalho do outro
-   Verificar quais navegadores ainda não estão aceitando o Grid

## PROPRIEDADES

Vamos separar em 2 grupos:
`Container`e `Item(s)`

### CONTAINER

-   display: grid;
-   grid-template-columns;
-   grid-template-rows;
-   grid-gap;
    -   grid-row-gap;
    -   grid-columns-gap;
-   grid-template-areas;

... e mais 4 propriedades e **Alinhamentos**

### ITEM(s)

-   grid-column
    -   grid-column-start;
    -   grid-column-end;
-   grid-row
    -   grid-row-star;
    -   grid-row-end;
-   grid-area

... e mais 2 propriedades de **Alinhamento**

## GRID Alinhamento

Existem 6 propriedades de alinhamento:

1. `justify-content`
2. `aling-content`
3. `justify-items`
4. `aling-items`
5. `justify-self`
6. `aling-self`

vamos separar em 2 grupos

1. `justify` e `aling`
2. `content` , `items` e `self`

## justify e Aling

Sabendo que o Grid é bidimensional, nós temos o eixo x e o y.

o **eixo x** é o posicionamento horizontal, da esquerda para a direita.

o **eixo y** é o posicionamento vertical, de cima para baixo

## Content, Items e Self

Juntando o `Justify`, ou `aling`, com esses elementos: `content`, `items` e `self`; nos observamos
nessas propriedades

___
### Content

`justify-content` e `aling-content` nos permite alinha o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são um pouco mais raras, pois só é a plicado caso o grid seja menor que a area definida. (Por exemplo, quando usamos o px o tamanho do grid, podemos terminar com um grid pequeno, para o tamanho da area do grid)

POdemos usar **7 Valores**:

1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

__
### Items

`justify-items` e `aling-itens` vai permitir alinhar os items do nosso grid, em qualquer espaço disponivel, para célula que ele habitar.

Podemos usar **4 Valores**

1. start
2. end
3. center
4. stretch

___
### Self

`justify-self` e `aling-self` vai nos permitir alinhar o item em si.

Faz a mesma coisa que o `justify-items` e `aling-items`, porem, aplicando diretamente no item de um grid. 