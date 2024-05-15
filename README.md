# Corrector

Este proyecto permite cargar un texto y ver las palabras que no se encuentren en el diccionario (por lo que podemos asumir que están mal escritas).

## Como usar

Ejecutar en el terminal el siguiente comando. Tener en cuenta que diccionario se puede omitir y seguirá funcionando, pero esto te permite elegir un diccionario diferente al que se ofrece en el repositorio. El texto debe estar en formato .txt
```
./corrector diccionario textos/[texto a corregir]
```

## Especificaciones

El código guarda las palabras del diccionario en diferentes guirnaldas dependiendo de las 2 primeras letras. Después lee cada palabra del texto y verifica en la lista correspondiente si la misma existe.
