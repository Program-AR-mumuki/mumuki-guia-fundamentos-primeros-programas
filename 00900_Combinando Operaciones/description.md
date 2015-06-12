Ahora que conocemos a `push!` y `move!`, que nos sirven para controlar al cabezal, estamos en condiciones de combinar a estas dos operaciones.

Por ejemplo el siguiente programa coloca una bolita roja en la posición inicial y una negra al este.

```ruby
def main
  push! red
  move! east
  push! black
end
```

Probá copiar y ejecutar este programa. Te mostraremos el resultado al ejecutarlo en un tablero de 2x2, y en otro de 3x2, ambos con el cabezal inicialmente en `(0, 0)`.
