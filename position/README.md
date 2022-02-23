# CSS Position - Case

<img align="center" alt="CSS" height="300" width="400" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">

A propriedade POSITION define como o elemento deve ser renderizado na página HTML. Ele é comumente relacionado às propriedades TOP, BOTTOM, LEFT e RIGHT para definição do deslocamento do elemento.

Valores possíveis: static, relative, absolute. Fixed e sticky.

## Static (default)

Segue o comportamento natural da página, não possui possibilidade de aplicação das propriedades top, bottom, left ou right.

## Relative

Com a determinação do position relative o elemento mantém o seu posicionamento segundo o fluxo  normal da página. Todavia, a definição das propriedades top, left, bottom e right altera o posicionamento do elemento. É possível assim definir o deslocamento vertical e horizontal.

## Absolute

Com a determinação do position absolute o elemento é posicionado de forma relativo ao seu ancestral mais próximo e cuja posição é relativa. Caso ele não tenha um ancestral relativo, ele será posicionado em relação ao body. Desta forma, o elemento é absoluto em relação à página e sai do fluxo normal desta. É comum a sua utilização junto o z-index. Suporta os valores top, right, bottom e left.

## Fixed

Com a determinação do position fixed o elemento sai do fluxo normal da página (não recebe um espaço), e o seu posicionamento é relativo à viewport, que corresponde à área visível da página. Desta forma, ele sempre fica na mesma posição da página, mesmo durante o scroll. Suporta os valores top, right, bottom e left. Não deixa um gap onde normalmente ele é renderizado.

## Sticky

Com a determinação do position sticky o elemento não sai do fluxo normal da página. Ele possui um comportamento duplo: inicialmente ele se comporta como relativo, mas ao atingir o limite de scroll ele passa para um comportamento fixed segundo o que foi definido por top, left, bottom e right.

## Initial

Com a determinação do position initial o navegador atribui o valor padrão da propriedade, ou seja, o valor static.

## Inherit

Com a determinação do position inherit o elemento filho herda a definição do position de seu pai.


## 💻 Caso de estudo: Newsletter

<img align="center" alt="Desktop" src="./illustrations/desktop.png">

<img align="center" alt="Tablet" src="./illustrations/tablet.png">

* Alerta de assinatura deve ser fixo
* As tags de notícia devem ficar fixas assim que atingirem o topo da página.
* O card de notícias deve ter três reponsividades.

