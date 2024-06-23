#### [README](README.md)

<div align="center">
  <h1>Introducción a SQL y bases de datos relacionales</h1>
</div>

# Tablas o Entidades

- El elemento básico de una base de datos relacional es la tabla o entidad.
- Las tablas guardan datos de un tipo de entidad (sitios, personas, productos, etc.).


**Ejemplo de tabla de personas:**

| ID | Nombre  | Edad | Ciudad     |
|----|---------|------|------------|
| 1  | Juan    | 25   | Barcelona  |
| 2  | Maria   | 30   | Madrid     |
| 3  | Carlos  | 28   | Valencia   |
| 4  | Laura   | 32   | Sevilla    |

---

# Tablas, registros y campos

- **Tabla:** conjunto de registros.
- **Registro:** fila de la tabla.
- **Campo:** columna de la tabla.

### Tablas

- Las tablas son el elemento básico de una base de datos relacional.
- Cada tabla almacena datos de un tipo de entidad (personas, productos, etc.).

---

### Registros

- Un registro es una fila de la tabla.
- Cada registro almacena información de un elemento de la entidad (una persona, un producto, etc.).

---

### Campos

- Para definir un campo se debe especificar:
  - Nombre del campo.
  - Tipo de dato.
  - Formato de sus datos.
  - longitud (si es obligatorio).
- Un registro equivale a una fila de la tabla.

---

# Relaciones entre tablas

- Las tablas se relacionan entre sí mediante claves.
- Las claves son campos que identifican de forma única a cada registro.
- Las claves pueden ser:
  - **Clave primaria:** campo que identifica de forma única a cada registro.
  - **Clave foránea:** campo que enlaza dos tablas.

---

### Ejemplo de relación entre tablas

| Tabla Uno      |        | Tabla Dos      |
|----------------|--------|----------------|
| Clave primaria |<------>| Clave foránea  |
| Campo generíco |        | Campo generíco |

---

# Claves primarias y foráneas

- **Clave primaria:** campo que identifica de forma única a cada registro.
- **Clave foránea:** campo que enlaza dos tablas.

 ### Clave primaria

- La columna clave primaria identifica de forma única a cada registro/fila.
- No puede haber dos registros/filas con la misma clave primaria.

| StrudentID | CursoID | Grado |
|------------|---------|-------|
| Graff      | 001     | A     |
| Smith      | 002     | B-    |
| Brown      | 003     | C     |

La columna `StudentID` y `CursoID` componen la clave primaria.

---

### Clave foránea/Extranjera

- Se utiliza para relacionar dos tablas.
- Es un campo de la tabla que contiene los mismos valores que la clave primaria de otra tabla.

**Tabla del curso**

| CursoID | CursoNombre | ProfesorID |
|---------|-------------|------------|
| 001     | Matemáticas | 101        |
| 002     | Historia    | 102        |
| 003     | Ciencias    | 103        |

**Tabla del profesor**

| ProfesorID | ProfesorNombre |
|------------|----------------|
| 101        | Mr. Smith      |
| 102        | Ms. Brown      |
| 103        | Dr. Graff      |

**Tabla de los estudiantes**

| StudentID | CursoID | Grado |
|-----------|---------|-------|
| Graff     | 001     | A     |
| Smith     | 002     | B-    |
| Brown     | 003     | C     |


---

# Coclusión

- Las bases de datos relacionales permiten relacionar la información de diferentes tablas.
- Las claves primarias y foráneas son fundamentales para establecer relaciones entre tablas.

