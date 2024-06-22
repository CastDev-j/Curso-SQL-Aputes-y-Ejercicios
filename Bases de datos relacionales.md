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

| Tabla Uno      |        | Tabla Dos      |
|----------------|--------|----------------|
| Clave primaria |<------>| Clave foránea  |
| Campo generíco |        | Campo generíco |

### Coclusión

- Las bases de datos relacionales permiten relacionar la información de diferentes tablas.
- Las claves primarias y foráneas son fundamentales para establecer relaciones entre tablas.

