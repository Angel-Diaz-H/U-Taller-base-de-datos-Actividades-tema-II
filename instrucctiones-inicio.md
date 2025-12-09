# ACTIVIDAD 1 (10 puntos)
Considerando la base datos INVENTARIOS, del Tema 1, que contiene las tablas:

``` SQL
PRODUCTO(
    NUMPROD character (3),
    NOMPROD character(30),
    PESO numeric (3),
    COLOR character (20),
    COSTO numeric (6),
    EXISTENCIAS numeric (4),
    PRIMARY KEY (NUMPROD)
);

PROVEEDOR (
    NUMPROV character (3),
    NOMPROV character(30),
    CIUDAD carácter (10),
    ESTATUS numeric (2),
    PRIMARY KEY (NUMPROV)
);

COMPRAS (
    NUMPROV character (3),
    NUMPROD character (3),
    CANTIDAD numeric (4),
    FECHA datetime
);
```

Consideraciones:
- NUMPROD ES LA LLAVE PRINCIPAL DE LA TABLA PRODUCTO
- NUMPROV ES LA LLAVE PRINCIPAL DE LA TABLA PROVEEDOR
- NUMPROV y NUMPROD SON LAS LLAVES SECUNDARIAS O HEREDADAS EN LA TABLA COMPRAS.

Ahora si ya estamos listos para empezar a realizar las consultas de actualización y
las de solo lectura.