# Programación orientada a objetos (POO)

## 1. Definición

La programación orientada a objetos es una forma de organizar un programa mediante objetos. Cada objeto reúne datos (atributos) y acciones (métodos) relacionados con un elemento o concepto.

## 2. Clase y objeto

- **Clase:** es una plantilla o molde que define qué atributos y métodos tendrán sus objetos.
- **Objeto:** es una instancia concreta creada a partir de una clase, con sus propios valores.
- **Atributos:** representan las características o datos del objeto.
- **Métodos:** representan las acciones que el objeto puede realizar.

Por ejemplo, `Auto` puede ser una clase. Un auto rojo de marca Ford y otro azul de marca Toyota son objetos distintos creados a partir de esa clase.

## 3. Principios principales

- **Encapsulamiento:** protege los datos y controla el acceso a ellos mediante métodos.
- **Abstracción:** permite concentrarse en las características importantes y ocultar detalles innecesarios.
- **Herencia:** permite crear una clase nueva a partir de otra y reutilizar sus atributos y métodos.
- **Polimorfismo:** permite que objetos de distintas clases respondan de manera diferente a una misma operación.

## 4. Ejemplo práctico en Java

```java
class Auto {
    private String marca;
    private String modelo;

    public Auto(String marca, String modelo) {
        this.marca = marca;
        this.modelo = modelo;
    }

    public void encender() {
        System.out.println("El auto está encendido");
    }

    public String getMarca() {
        return marca;
    }
}

public class Principal {
    public static void main(String[] args) {
        Auto miAuto = new Auto("Ford", "Ka");
        miAuto.encender();
        System.out.println(miAuto.getMarca());
    }
}
```

En el ejemplo, `Auto` es la clase y `miAuto` es un objeto. `marca` y `modelo` son atributos; `encender()` y `getMarca()` son métodos. El constructor inicializa el objeto cuando se crea.

## 5. ¿Para qué se utiliza?

La POO ayuda a organizar programas grandes, reutilizar código, representar elementos del problema y facilitar el mantenimiento.

## 6. Para recordar

Una clase define la estructura; un objeto es una instancia de esa clase. Los atributos guardan información y los métodos realizan acciones.

## Temas relacionados

- [Diagrama de clases](../diagramas-de-clases/README.md)
- [Herencia](../herencia/README.md)
- [Listas y ArrayList](../listas-y-arraylist/README.md)
