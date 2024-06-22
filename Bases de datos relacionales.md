#### [README](README.md)

# Introducción a SQL y bases de datos relacionales

### Tablas o Entidades

- El elemento básico de una base de datos relacional es la tabla o entidad.
- Las tablas guardan datos de un tipo de entidad (sitios, personas, productos, etc.).

**Ejemplo de tabla de personas:**

| ID | Nombre  | Edad | Ciudad     |
|----|---------|------|------------|
| 1  | Juan    | 25   | Barcelona  |
| 2  | Maria   | 30   | Madrid     |
| 3  | Carlos  | 28   | Valencia   |
| 4  | Laura   | 32   | Sevilla    |

# Tablas, registros y campos

- **Tabla:** conjunto de registros.
- **Registro:** fila de la tabla.
- **Campo:** columna de la tabla.



### Campos

- Para definir un campo se debe especificar:
  - Nombre del campo.
  - Tipo de dato.
  - Opciones adicionales (longitud, si es obligatorio, etc.).
  - Formato de sus datos.
- Un registro equivale a una fila de la tabla.

# Relaciones entre tablas

- Las tablas se relacionan entre sí mediante claves.
- Las claves son campos que identifican de forma única a cada registro.
- Las claves pueden ser:
  - **Clave primaria:** campo que identifica de forma única a cada registro.
  - **Clave foránea:** campo que enlaza dos tablas.

### Relación entre tablas

- Podemos crear dos tablas relacionadas en la misma línea utilizando los siguientes símbolos:

```markdown
| Tabla1 | Tabla2 |
|--------|--------|
| Campo1 | Campo3 |
| Campo2 | Campo4 |
```

- En este ejemplo, `Tabla1` y `Tabla2` representan los nombres de las tablas, mientras que `Campo1`, `Campo2`, `Campo3` y `Campo4` representan los nombres de los campos.

- La relación entre las tablas se establece mediante la correspondencia de los campos. Por ejemplo, si `Campo1` en `Tabla1` se relaciona con `Campo3` en `Tabla2`, significa que los registros de ambas tablas están relacionados entre sí.

- Esta forma de representar la relación entre tablas es útil cuando queremos mostrar de manera concisa la estructura y la conexión entre las tablas en un documento o archivo.
