# Listas y ArrayList

## 1. Definición

Una lista es una estructura que permite almacenar varios elementos en una misma colección y acceder a ellos de manera ordenada. `ArrayList` es una implementación de listas de Java cuyo tamaño puede crecer o reducirse durante la ejecución.

## 2. Operaciones principales

- `add(elemento)`: agrega un elemento.
- `remove(indice)`: elimina el elemento ubicado en esa posición.
- `get(indice)`: obtiene el elemento de una posición.
- `size()`: devuelve la cantidad de elementos.

En Java, los índices comienzan en cero. Por eso, el primer elemento está en la posición `0`.

## 3. Ejemplo en Java

```java
import java.util.ArrayList;

public class Principal {
    public static void main(String[] args) {
        ArrayList<String> alumnos = new ArrayList<>();

        alumnos.add("Juan");
        alumnos.add("Facundo");
        alumnos.add("Lucía");

        System.out.println(alumnos.get(0)); // Juan
        System.out.println(alumnos.size()); // 3

        alumnos.remove(1); // elimina a Facundo
        System.out.println(alumnos);
    }
}
```

## 4. ¿Cuándo se utiliza?

Se utiliza cuando un programa necesita guardar una cantidad de elementos que puede cambiar, por ejemplo una lista de alumnos, productos o turnos.

## 5. Para recordar

`ArrayList` permite agregar, consultar y quitar elementos sin tener que definir de antemano una cantidad fija de posiciones.

## Tema relacionado

- [POO](../programacion-orientada-a-objetos/README.md)
