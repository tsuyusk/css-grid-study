# Grid: Alinhamento

---

Existem 6 propriedades para alinhamento:

1.  `justify-content`
2.  `align-content`
3.  `justify-items`
4.  `align-items`
5.  `justify-self`
6.  `align-self`

Vamos separar em 2 grupos:

1. `justify` e `align`
2. `content`, `items` e `self`

---

## Justify e align

Sabendo que o grid é bidimensional, nós temos o eixo X e o eixo Y.

**X** => Horizontal (da Esquerda para a Direita)
**Y** => Vertical (de Cima para baixo)

(Study/2)

---

## Content

`justify-content`(x) e `align-content`(y) nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

- Raramente utilizadas
- Somente aplicadas caso o grid seja menor que a área definida

**7 Valores**

1. start
2. end
3. center
4. strech
5. space-between
6. space-around
7. space-evenly

---

## item

`justify-items`(x) e `align-items`(y) nos permite alinhar os items do grid, em qualquer espaço disponivel na celular em que ele vai habitar

**4 valores**

1. start
2. end
3. center
4. strech

---

### self

`justify-items`(x) e `align-items`(y) nos permite alinhar o item entre sí.

Faz o mesmo que o `justify-items` e `align-items`, porém aplicando diretamente no item de um grid
