Para pensar:

Notá que estos dos programas hacen lo mismo:

```puppet
program {
  Mover(Este)
  Mover(Este)
  Mover(Sur)
}
```

```puppet
program {
  Mover(Este)
  Mover(Sur)
  Mover(Este)
}
```

Moraleja: ¡No hay una sóla forma de resolver un problema!