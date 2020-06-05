![logotipo de The Bridge](https://user-images.githubusercontent.com/27650532/77754601-e8365180-702b-11ea-8bed-5bc14a43f869.png "logotipo de The Bridge")

# :shinto_shrine: - CSS Toggle #

## Introducción ##

Un toggle no es más que un **checkbox**, o casilla de verificación,  con mucho estilo. Las opciones de personalización, en cuanto a estilo, de `<input type="checkbox" />` son casi inexistentes. Puedes comprobarlo en [W3Schools - Custom checkbox].

![pic1]

Aún así, te habrás encontrado muchos ejemplos de "switch" o interruptor, con dos estados, y que no se parecen en nada a un "checkbox".

Esto se logra con varias herramientas:
- [CSS Tricks - Checkbox hack] para poder hacer invisible aquello que no podemos darle estilo e interactuar con el valor de ese elemento de formulario.
- [CSS Tricks - After y before] para crear estilos sobre HTML sin necesidad de crear etiquetas adicionales. Puedes mirar también [::after] y [::before]

![pic2]

## Requisitos ##

- Precurso web

## Iteraciones ##

Tu "Toggle" será completamente accesible y sin Javascript, así que tendrás que aplicar el marcado correcto.

Sin marcar:

![normal]

Marcado:

![checked]

1. Crea un formulario, label e input.

2. Aplica el [CSS Tricks - Checkbox hack] y haz invisible el `input`

3. Aplica estilos gracias a [::after] y [::before]

[normal]: normal.png
[checked]: checked.png
[pic1]: https://media.giphy.com/media/3ohhwuZW3cEWzJehhu/giphy.gif
[pic2]: https://media.giphy.com/media/3ohhwoWSCtJzznXbuo/giphy.gif

[W3Schools - Custom checkbox]: https://www.w3schools.com/howto/howto_css_custom_checkbox.asp "Custom checkbox"
[CSS Tricks - Checkbox hack]: https://css-tricks.com/the-checkbox-hack "Checkbox hack"
[CSS Tricks - After y before]: https://css-tricks.com/almanac/selectors/a/after-and-before "After y before"
[::after]: https://developer.mozilla.org/en-US/docs/Web/CSS/::after "::after"
[::before]: https://developer.mozilla.org/en-US/docs/Web/CSS/::before "::before"
