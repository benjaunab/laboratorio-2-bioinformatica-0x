# laboratorio-2-bioinformatica-0x
### Benjamin Flores Oviedo

## Parte 1: Colectar genes homólogos

### ¿Qué función cumple el gen SRY?
_R_: El gen SRY es un factor de transcripcion perteneciente al grupo de alta mobilidad.

### ¿Cuántos genes ortólogos están anotados en esa base de datos?
_R_: Posee 26 ortológos.

## Parte 2: Alineamiento múltiple

### ¿Qué es el EMBL-EBI?
_R_: El EMBL-EBI o instituto europeo de bioinformatica es una sitio web que comparte datos experimentales, realiza investigación básica en biología computacional entre otras cosas.
  
### ¿Cuántos tipos de alienamiento múltiple se pueden realizar en EMBL-EBI?
_R_: generalmente la alineación son de tres o más secuencias de proteinas o acidos nucleicos.

### ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?
_R_: El MUSCLE es la herramienta mas especifica. 
  
### ¿Qué otros tipo de herramientas ofrece EMBL-EBI?
_R_: EMBL-EBI ofrece un monton de herramientas relacionadas con material genetico y proteinas.

### ¿Cuál es el costo de abrir un gap?
_R_: En las opcion estandar la penalizacion de abrir un GAP es de 1.53.

### ¿Cuál es el costo de extender un gap?
_R_: El costo es de 0.123

### ¿Cuál es la longitud total del alineamiento?

_R_: 1932 nucleotidos.

### ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?

_R_: La especie Pan troglodytes(Chimpancé común). 

### ¿Cuál es el más lejano?

_R_: El Pteropus alecto(zorro volador negro)

### ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?

_R_: El Equus przewalskii

### ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?

_R_: En este caso, que es un alinamiento global, al aumentar el costo de abrir gap el programa va a preferir no abrir tantos gap, pero si alargarlos, mientras que al disminuir ocurrira lo contrario. Como consecuencia el alinamiento sera más largo.    

### ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?

_R_: La herramienta preferira no extender los gap, entonces se vera un alinamiento con mas gap intercalados que consecutivos, Y al disminuirlo sera lo contrario.

### ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? prueba lo mismo pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento

_R_: El alinamiento no cambio, quedo con el mismo largo. Al disminuir el costo de extender un gap al mínimo (0.1) la alineacion quedo con un largo de 1907 nucleotidos.

## Parte 3: Diseño de partidores

### Pega en tu informe los partidores que el programa encontró

_R_: [Primers](https://drive.google.com/file/d/0B0rzqm380_roR214eGo4aW1rclU/view?usp=sharing)
