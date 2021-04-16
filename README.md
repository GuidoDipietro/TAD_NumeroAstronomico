# Trabajo Práctico de Sintaxis y Semántica de los Lenguajes | UTN FRBA

Tipo Abstracto de Dato Número Astronómico  
Octubre de 2020

#### Guido Dipietro y Magalí Irigaray  

<hr>

Consigna original, ver archivo _consigna-TAD.pdf_.

Código original (con _leaks_), ver anterior a [este commit](https://github.com/GuidoDipietro/TAD_NumeroAstronomico/commit/2a71c4b589210f74e2ac6ee19a7d0da4798733c9). (Se arreglaron múltiples _memleaks_ posterior a la entrega del TP, afeando el código bastante, y causando dudas existenciales al programador que, meses atrás, pensó que esas soluciones podrían ser buenas).

Se incluye un informe en PDF en la carpeta _informe_ detallando exactamente las precondiciones para cada función, así como definiciones precisas del funcionamiento de cada una, explicaciones en profundo detalle de su implementación en ANSI C, y justificación para cada una de las decisiones tomadas.

El código fuente de la biblioteca, así como otros archivos de prueba, se incluyen en la carpeta _src_.

## Compilar
Para compilar hacer doble click en el archivo "compilar.bat" o ingresar en consola el siguiente comando:  
```gcc -o principal principal.c astronum.c -g -I.```

Para Linux, se provee el Makefile.