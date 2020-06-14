## TIPOS DE DATOS ABSTRACTOS
### Ventajas:
 - Descomposición
 - Abstracción
 - Encapsulación
 
 
## INSTANCIAS
    - Mientras que la clase es un molde, a los objetos creados se les conoce como instancias.
    - Cuando se crea una instancia, se ejecuta el método __init__
    - Todos los métodos de una clase reciben implícitamente como primer parámetro self
    
    # Los atributos de clase nos permiten:
        - Representar datos
        - Procedimientos para interactuar con los mismos (métodos)
        - Mecanismos para esconder la representación interna.

    # Se accede a los atributos con la notación de punto.

    # Se puede tener atributos privados. Por convención comienzan con _

## DECOMPOSICIÓN

    - Partir un problema en problemas más pequeños.
    - Las clases permiten crear mayores abstracciones en forma de componentes.
    - Cada clase se encarga de una parte del problema y el programa se vuelve más fácil de mantener.

## ABSTRACCIÓN
    
    - Enfocarnos en la informacion relevante.
    - Separar la informacion centrar de los detalles secundarios.
    - Podemos utilizar variables y métodos (privados o públicos)


## ENCAPSULACION

    - Permite agrupar datos y su comportamiento.
    - Controla el acceso a dichos datos.
    - Previene modificaciones no autorizadas.

## HERENCIA

    - Permite modelar una jerarquía de clases.
    - Permite compartir comportamiento común en la jerarquía.
    - Al padre se le conoce como superclase y al hijo como subclase.

## POLIMORFISMO
    - La habilidad de tomar varias fomas.
    - En Python, nos permite cambiar el comportamiento de una superclase para adaptarlo a la subclase.


# Complejidad algorítmica

## Crecimiento asintótico

    - No importan variaciones pequeñas.
    - El enfoque se centra en lo que pasa conforme el tamaño del problema se acerca al infinito.
    - Mejor de los casos, promedio, peor de los casos.
     Big O.
     - Nada más importa el término de mayor tamaño.


# Algoritmos de búsqueda y ordenación

## Busqueda lineal

    - Busca en todos los elementos de manera secuencial.
    - Cuál es el pero caso?

## Búsqueda binaria

    - Divide y conquista.
    - El problema se divide en 2 en cada iteración.
    - Cual es el peor caso?

## Ordenamiento de burbuja

    - Compara elementos adyacentes y los intercambia si están en el orden incorrecto. Ente procedimiento se repite hasta que no se requieren más intercambios, lo que indeca que la lista se encuentra ordenada.

## Ordenamiento por mezcla

    - Es un algoritmo de divide y conquista. Primero divide una lista en partes iguales hasta que quedan sublistas de 1 o 0 elementos. Luego las recombina en forma ordenada.


# Por qué graficar?

    - Reconocimiento de patrones.
    - Predicción de una serie.
    - Simplifica la interpretacion y las conclusiones acerca de los datos

## Graficado Simple
    - Bokeh permite construir gráficas complejas de manera rápida y con comandos simples.

    - Permite exportar a varios formatos como html, notebooks, imágenes, etc.
    
    - Bokeh se puede utilizar en el servidor con Flask y Django.

# Introducción a la optimización

    - El concepto de optimización permite resolver muchos problemas de manera computacional.

    - Una función objetivo que debemos maximizar o minimizar.

    - Una serie de limites que debemos respetar.