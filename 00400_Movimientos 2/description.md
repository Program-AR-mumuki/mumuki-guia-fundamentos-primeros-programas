Entendamos qué es lo que acabamos de hacer: escribir un programa.

Todo programa tiene exactamente un `main`: una sección del código que declara las operaciones (instrucciones) que vamos a realizar sobre el tablero **inicial**. Al ejecutar un programa  obtendremos un tablero **final**.

La sintaxis de un `main` es bastante simple:

1. escribimos una línea (renglón) que diga `def main`
1. a continuación, cero o más instrucciones: una instrucción por línea
1. y finalmente, una última línea `end`

Algunos ejemplos de `main`s:


```ruby
def main
end
```

(no hace nada)


```ruby
def main
  move! north
end
```

(mueve el cabezal una posición hacia el norte)

```ruby
def main
  move! north
  move! north
end
```

(mueve el cabezal dos posiciones hacia el norte)

Sabiendo ésto, escribir un programa que en un tablero de 2x4 con el cabezal en el origen:

![2x4h00](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/2x4h00.png)

mueva el cabezal tres veces hacia el norte:

![2x4h03](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/2x4h03.png)
