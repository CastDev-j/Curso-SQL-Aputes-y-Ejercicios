#### [README](README.md)

<div align="center">
  <h1>¿Que es SQL?</h1>
</div>

**SQL** también conocido como `Structured Query Language` es un lenguaje de programación utilizado para gestionar y manipular bases de datos relacionales. SQL permite realizar consultas, actualizaciones, inserciones y eliminaciones de datos en una base de datos, así como definir y modificar la estructura de la base de datos.

* Algunos ejemplos de sistemas de gestión de bases de datos relacionales que utilizan SQL son:
    - [MySQL](https://www.mysql.com/)
    - [PostgreSQL](https://www.postgresql.org/)
    - [SQLite](https://www.sqlite.org/)
    - [Oracle](https://www.oracle.com/database/)
    - [SQL Server](https://www.microsoft.com/en-us/sql-server/)

En esta sección se presentan las cláusulas y funciones más comunes de SQL para realizar consultas y manipulación de datos en bases de datos relacionales.

---


# Cláusulas

___

<details>
<summary><strong>Consultas</strong></summary>
<br>
- **SELECT** - Recuperar datos de una tabla.
- **WHERE** - Filtrar registros.
- **ORDER BY** - Ordenar registros.
- **GROUP BY** - Agrupar registros.
- **HAVING** - Filtrar registros agrupados.
- **JOIN** - Unir tablas.
- **UNION** - Unir resultados de consultas.
- **INTERSECT** - Intersección de resultados.
- **EXCEPT** - Diferencia de resultados.
- **IN** - Filtrar por lista de valores.
- **BETWEEN** - Filtrar por rango de valores.
- **LIKE** - Filtrar por patrón.
- **IS NULL** - Filtrar registros nulos.
- **IS NOT NULL** - Filtrar registros no nulos.
- **EXISTS** - Filtrar registros que existen.
- **NOT** - Negar una condición.
- **ALL** - Comparar con todos los valores.
- **ANY** - Comparar con alguno de los valores.
- **AS** - Alias de columnas o tablas.
- **DISTINCT** - Filtrar registros duplicados.
</details>

___

<details>
<summary><strong>Agregación y funciones de resumen</strong></summary>
<br>
- **COUNT** - Contar registros.
- **SUM** - Sumar valores.
- **AVG** - Calcular promedio.
- **MIN** - Calcular mínimo.
- **MAX** - Calcular máximo.
</details>

___

<details>
<summary><strong>Manipulación de datos</strong></summary>
<br>
- **INSERT** - Insertar registros.
- **UPDATE** - Actualizar registros.
- **DELETE** - Eliminar registros.
- **TRUNCATE** - Vaciar tabla.
</details>

___

<details>
<summary><strong>Transacciones</strong></summary>
<br>
- **COMMIT** - Confirmar transacción.
- **ROLLBACK** - Deshacer transacción.
</details>

___

<details>
<summary><strong>Permisos y seguridad</strong></summary>
<br>
- **GRANT** - Conceder permisos.
- **REVOKE** - Revocar permisos.
</details>

___

<details>
<summary><strong>Creación y modificación de esquemas</strong></summary>
<br>
- **CREATE** - Crear tablas, vistas, índices, etc.
- **ALTER** - Modificar tablas, vistas, índices, etc.
- **DROP** - Eliminar tablas, vistas, índices, etc.
- **CREATE DATABASE** - Crear base de datos.
- **DROP DATABASE** - Eliminar base de datos.
- **USE** - Seleccionar base de datos.
</details>

___

<details>
<summary><strong>Información del esquema</strong></summary>
<br>
- **SHOW** - Mostrar información.
- **DESCRIBE** - Describir estructura.
</details>

___

<details>
<summary><strong>Copias de seguridad</strong></summary>
<br>
- **BACKUP** - Realizar copia de seguridad.
- **RESTORE** - Restaurar copia de seguridad.
</details>

___

<details>
<summary><strong>Índices y claves</strong></summary>
<br>
- **INDEX** - Crear índice.
- **PRIMARY KEY** - Definir clave primaria.
- **FOREIGN KEY** - Definir clave foránea.
- **UNIQUE** - Definir índice único.
</details>

___

<details>
<summary><strong>Restricciones y valores predeterminados</strong></summary>
<br>
- **CHECK** - Definir restricción de integridad.
- **DEFAULT** - Definir valor por defecto.
- **AUTO_INCREMENT** - Definir incremento automático.
- **CONSTRAINT** - Definir restricción.
</details>

___

<details>
<summary><strong>Funciones de fecha y hora</strong></summary>
<br>
- **SYSDATE** - Obtener fecha y hora actuales.
- **NOW** - Obtener fecha y hora actuales.
- **GETDATE** - Obtener fecha y hora actuales.
- **CURDATE** - Obtener fecha actual.
- **CURTIME** - Obtener hora actual.
- **DATE** - Obtener fecha.
- **TIME** - Obtener hora.
- **YEAR** - Obtener año.
- **MONTH** - Obtener mes.
- **DAY** - Obtener día.
- **HOUR** - Obtener hora.
- **MINUTE** - Obtener minuto.
- **SECOND** - Obtener segundo.
- **DATEDIFF** - Calcular diferencia de fechas.
- **DATEADD** - Sumar o restar fechas.
</details>

___

<details>
<summary><strong>Funciones numéricas</strong></summary>
<br>
- **ROUND** - Redondear valores.
- **TRUNC** - Truncar valores.
- **CEIL** - Redondear hacia arriba.
- **FLOOR** - Redondear hacia abajo.
- **RAND** - Generar número aleatorio.
- **ABS** - Valor absoluto.
- **MOD** - Resto de la división.
- **SQRT** - Raíz cuadrada.
- **POWER** - Potencia.
- **LOG** - Logaritmo natural.
- **EXP** - Exponencial.
- **SIN** - Seno.
- **COS** - Coseno.
- **TAN** - Tangente.
- **ASIN** - Arcoseno.
- **ACOS** - Arcocoseno.
- **ATAN** - Arcotangente.
</details>

___

<details>
<summary><strong>Funciones de cadena</strong></summary>
<br>
- **CONCAT** - Concatenar cadenas.
- **LENGTH** - Calcular longitud.
- **TRIM** - Eliminar espacios en blanco.
- **SUBSTRING** - Extraer subcadena.
- **REPLACE** - Reemplazar subcadena.
- **UPPER** - Convertir a mayúsculas.
- **LOWER** - Convertir a minúsculas.
- **LPAD** - Rellenar a la izquierda.
- **RPAD** - Rellenar a la derecha.
- **INSTR** - Encontrar posición.
- **TO_CHAR** - Convertir a cadena.
- **TO_NUMBER** - Convertir a número.
- **TO_DATE** - Convertir a fecha.
</details>

___

<details>
<summary><strong>Funciones de manejo de valores nulos</strong></summary>
<br>
- **NVL** - Reemplazar nulos.
- **DECODE** - Decodificar valores.
- **CASE** - Estructura condicional.
- **NULLIF** - Comparar nulos.
- **COALESCE** - Primer valor no nulo.
</details>

___

<details>
<summary><strong>Funciones de análisis y clasificación</strong></summary>
<br>
- **GREATEST** - Mayor valor.
- **LEAST** - Menor valor.
- **ROW_NUMBER** - Número de fila.
- **RANK** - Posición en rango.
- **DENSE_RANK** - Posición en rango denso.
- **NTILE** - Número de baldes.
- **LAG** - Valor anterior.
- **LEAD** - Valor siguiente.
- **FIRST_VALUE** - Primer valor.
- **LAST_VALUE** - Último valor.
- **PERCENT_RANK** - Rango porcentual.
- **CUME_DIST** - Distribución acumulativa.
- **PERCENTILE_CONT** - Percentil continuo.
- **PERCENTILE_DISC** - Percentil discreto.
- **LISTAGG** - Concatenar valores.
</details>

---

### [Ejemplos de SQL](./Ejemplos&SQL.md)

En esta sección se presentan ejemplos de consultas SQL para ilustrar el uso de las cláusulas y funciones mencionadas anteriormente.

# Conclusión

Esta sección fue hecha para ver las cláusulas y funciones de SQL.

Si no recuerdas alguna cláusula o función, puedes regresar a esta sección para recordarla.

---

# Recomendación

Practica con los ejemplos en la liga [Ejemplos de SQL](./Ejemplos&SQL.md) para mejorar tus habilidades en SQL.

#### [README](README.md)


