# Diagrama de Clases

![Diagrama de Clases](Imagenes/Ejemplos.png)

Explicación de relación entre diagrama de clases...

## Relación Herencia

La herencia es una relación entre dos clases donde una clase hereda los atributos y métodos de otra clase. En el diagrama de clases, se representa mediante una línea sólida con una flecha apuntando hacia la clase base.
>Por ejemplo: autobuses, taxis y automóviles son automóviles, todos tienen nombres y todos pueden estar en la carretera

![Herencia](Imagenes/Herencia.png)

## Relación Implementación

La implementación es una relación entre una clase y una interfaz donde la clase implementa los métodos definidos en la interfaz. En el diagrama de clases, se representa mediante una línea punteada con una flecha apuntando hacia la interfaz.

>Por ejemplo: los automóviles y los barcos son vehículos, y el vehículo es solo un concepto abstracto de una herramienta móvil, y el barco y el vehículo realizan las funciones móviles específicas.

![Implementación](Imagenes/Implementación.png)

## Relacion Composición

La composición es una relación entre dos clases donde una clase contiene a la otra como parte de su estructura. En el diagrama de clases, se representa mediante una línea sólida con un rombo lleno en el extremo de la clase que contiene a la otra.

>Por ejemplo: una persona está compuesta por una cabeza y un cuerpo. Los dos son inseparables y coexisten.

![Composición](Imagenes/Compisición.png)

## Relación Agregación

La agregación es una relación entre dos clases donde una clase contiene a la otra como parte de su estructura, pero la clase contenida puede existir independientemente de la clase contenedora. En el diagrama de clases, se representa mediante una línea sólida con un rombo vacío en el extremo de la clase que contiene a la otra.

> Por ejemplo: los conductores de autobús y la ropa y los sombreros de trabajo son parte de la relación general, pero se pueden separar. La ropa de trabajo y los sombreros se pueden usar en otros conductores. Los conductores de autobuses también pueden usar otra ropa de trabajo y sombreros.

![Agregación](Imagenes/Agregación.png)

## Relación Asociación

La asociación es una relación entre dos clases donde una clase utiliza a la otra de alguna manera, pero no está directamente contenida en ella ni hereda de ella. En el diagrama de clases, se representa mediante una línea sólida sin ningún símbolo especial.

>Por ejemplo: coches y conductores, un coche corresponde a un conductor en particular y un conductor puede conducir varios coches.

![Asociación](Imagenes/Asociación.png)

### Relación  Dependencia

La dependencia es una relación entre dos clases donde una clase utiliza a la otra en algún punto, pero no está directamente relacionada con ella. En el diagrama de clases, se representa mediante una línea punteada sin ningún símbolo especial.

>Por ejemplo: El auto depende de la gasolina. Si no hay gasolina, el automóvil no podrá conducir.

![Dependencia](Imagenes/Dependencia.png)

# EJEMPLO

Se necesita un sistema de `Pedidos` sistematizado en el cual se puedan agregar los siguentes atributos:

```
+ Id
+ fecha de pedido
+ Estado de Pedido
    + Pendiente
    + En curso
    + Completado
+ Cliente (Contenga class Cliente)
+ Productos (Contenga class Productos)

* Agregar Productos
* Calcular el Total
```

Con ello tambien se necesita la siguiente informacion de los `Cliente`:

```
+ 
```

`@Nicolas Tello`
