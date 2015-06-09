Entendamos qué es lo que acabamos de hacer: escribir un programa.

Todo programa tiene exactamente un `program`: una sección del código que declara las operaciones (instrucciones) que vamos a realizar sobre el tablero.

La sintaxis de un `program` es bastante simple:

1. escribimos una línea (renglón) que diga `program`, seguido de una llave de apertura: `{`
1. a continuación, cero o más instrucciones: una instrucción por línea
1. y finalmente, una última llave que cierra la que abrimos anteriormente `}`

Algunos ejemplos de `program`s:


```puppet
program {
}
```

(no hace nada)


```puppet
program {
  Mover(Norte)
}
```

(mueve el cabezal una posición hacia el norte)

```puppet
program {
  Mover(Norte)
  Mover(Norte)
}
```

(mueve el cabezal dos posiciones hacia el norte)

Sabiendo ésto, escribir un programa que en un tablero de 2x4 mueva el cabezal tres veces hacia el norte.