# Bienvenido a Flexbox Froggy.

## NIVEL 1,2,3 Y 4.

Bienvenido a Flexbox Froggy, un juego donde ayudarás a Froggy y a sus amigos escribiendo código CSS.

- 1. justify-content : End
- 2. justify-content : center
- 3. justify-content: space-around;
- 4. justify-content : space-between;


## NIVEL 5,6 y 7

Ahora usa align-items. Esta propiedad CSS alinea elementos verticalmente y acepta los siguientes valores:

- 5. align-items: flex-end;
- 6. justify-content: center;
  align-items: center;
- 7. justify-content: space-around;
  align-items: flex-end;


## Level 8 Y 9

Las ranas necesitan ponerse en el mismo orden que sus hojas de lirio usando flex-direction.

- 8. flex-direction: row-reverse;
- 9. flex-direction: column;

## Level 10,11,12 Y 13

Ayuda a las ranas a llegar a sus hojas de lirio. A pesar de que ellas parecen estar cerca, necesitarás usar flex-direction y justify-content para llegar hasta allí.

- 10. flex-direction:row-reverse;
  flex-wrap:wrap;
  justify-content:flex-end;
- 11. flex-direction: column;
  justify-content: flex-end;
- 12. flex-direction: column-reverse;
  justify-content: space-between;
- 13. flex-direction: row-reverse;
  justify-content: center ;
  align-items: flex-end ;


## NIVEL 14 AND OTHERS.

- A veces, invertir el orden de una fila o columna de un contenedor no es suficiente. En esos casos, nosotros podemos aplicar la propiedad order a elementos individuales. Por defecto, los elementos tienen un valor 0, pero nosotros podemos usar esta propiedad para establecerlo a un número entero positivo o negativo.

- Usa la propiedad order para reordenar las ranas de acuerdo a sus hojas de lirio.

## Flex-wrap, la cual acepta los siguientes valores:

- nowrap: Cada elemento se ajusta en una sola línea.
- wrap: los elementos se envuelven alrededor de líneas adicionales.
- wrap-reverse: Los elementos se envuelven alrededor - de líneas adicionales en reversa.


## NIVEL 20

Las dos propiedades flex-direction y flex-wrap son usadas a menudo en conjunto con la propiedad abreviada flex-flow, la cual fue creada para combinarlas. Esta propiedad abreviada, acepta un valor de cada una separada por un espacio.

Por ejemplo, puedes usar flex-flow para establecer filas y envolverlas.

## NIVEL 21

Puedes usar align-content para establecer como múltiples líneas están separadas una de otra. Esta propiedad acepta los siguientes valores:

- flex-start: Las líneas se posicionan en la parte superior del contenedor.
- flex-end: Las líneas se posicionan en la parte inferior del contenedor.
- center: Las líneas se posicionan en el centro (verticalmente hablando) del contenedor.
- space-between: Las líneas se muestran con la misma distancia entre ellas.
- space-around: Las líneas se muestran con la misma separación alrededor de ellas.
- stretch: Las líneas se estiran para ajustarse al contenedor.
- Esto puede ser confuso, pero align-content determina el espacio entre las líneas, mientras que align-items determina como los elementos en su conjunto están alineados dentro del contenedor. Cuando hay solo una línea, align-content no tiene efecto.

