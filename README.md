## Documentação de como Trabalhar com layout usando Flex-Box.
* [Display Flex](https://github.com/AndreAquilau/docs-flex-box#display-flex)
* [Flex-Direction](https://github.com/AndreAquilau/docs-flex-box#flex-direction)
* [Flex-Wrap](https://github.com/AndreAquilau/docs-flex-box#flex-wrap)
* [Justify-Content](https://github.com/AndreAquilau/docs-flex-box#justify-content)
* [Align-Items](https://github.com/AndreAquilau/docs-flex-box#align-items)
* [Flex-Grow](https://github.com/AndreAquilau/docs-flex-box#flex-grow)
* [Order](https://github.com/AndreAquilau/docs-flex-box#order)
* [References](https://github.com/AndreAquilau/docs-flex-box#references)

#### Display Flex
* O Display Flex é aplicado no container.
* Default mode: column, align: flex-start, flex-wrap: nowrap.
~~~css
.container {
    display: flex;
    align
}
~~~

#### Flex-Direction
* O Flex-Direction é aplicado no container.
* Define a direção dos items se serão em colunas ou em linhas
* recebi quatro valores
> ~~column~~, ~~column-reverse~~, ~~row~~, ~~row-reverse~~.
~~~css
.container {
    flex-direction: column | column-reverse | row row-reverse;
}
~~~

#### Flex-Wrap
* O Flex-wrap é aplicado no container.
* Define se os box filhos irão quebrar a linha ou não.
* recebi três valores
> ~~nowrap~~, ~~wrap-reverse~~, ~~wrap~~.
.container {
  flex-wrap: nowrap | wrap | wrap-reverse;
}

#### Justify-Content
* O Justify-Content é aplicado no container.
* A propriedade define o alinhamento no main-axis ou na horizontal no eixo X.
> flex-start, flex-end, center, space-between, space-around, space-evenly, start, end, left, right;
~~~css
.container {
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right;
}
~~~

#### Align-Items
* O Align-Items é aplicado no container.
* A propriedade define o alinhamento no cross-axis ou na vertical no eixo Y.
> stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end;
~~~css
.container {
  align-items: stretch = /*não pode ter altura.*/ | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end;
}
~~~


#### Flex-Grow
* O Flex-Grow é aplicado no items.
* A propriedade define a capacidade de um item crescer em relação os outros items.
* Não aceita valores negativos, Default Zero.
~~~css
.item {
  flex-grow: 2;
}
~~~

#### Order
* O Flex-Order é aplicado no items.
* A propriedade define a posição do item se irá para frente ou para trás.
* Default é Zero.
~~~css
.item {
  order: 1 /*irá andar uma posição*/;
}
~~~

#### References
* [Flex-Box Guia](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Flex-Box Help](https://flexbox.help/)
