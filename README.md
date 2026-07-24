# Database SQL Testing Project

## Descripción
Proyecto de práctica de QA Manual enfocado en pruebas de base de datos utilizando SQL y DBeaver.
El objetivo del proyecto fue validar la integridad, consistencia y correcta relación de los datos almacenados en una base de datos, realizando consultas SQL sobre las tablas de usuarios, productos y pedidos.
Se ejecutaron pruebas de validación de datos, filtros, conteos, ordenamiento y relaciones entre tablas mediante consultas JOIN.

---

## Base de Datos Probada
Base de datos utilizada:
MySQL
Herramienta de gestión:
DBeaver

---

## Modelo Evaluado
La base de datos contiene las siguientes entidades:

### Usuarios
Información almacenada:
- ID de usuario
- Nombre
- Email
- Estado


### Productos
Información almacenada:
- ID de producto
- Nombre del producto
- Precio
- Stock


### Pedidos
Información almacenada:
- ID de pedido
- Usuario relacionado
- Producto relacionado
- Cantidad solicitada

---

## Alcance de Pruebas
Las pruebas realizadas fueron:
- Consulta de todos los usuarios.
- Consulta de usuarios mediante ID.
- Consulta de usuarios mediante email.
- Consulta de todos los productos.
- Consulta de productos mediante ID.
- Validación de productos con stock disponible.
- Consulta de todos los pedidos.
- Consulta de pedidos mediante ID.
- Validación de cantidades solicitadas.
- Conteo total de usuarios.
- Conteo total de productos.
- Ordenamiento de productos por precio.
- Validación de relaciones entre tablas mediante JOIN.

---

## Tipos de Testing Aplicados
- Database Testing.
- Validación de datos.
- Pruebas funcionales sobre base de datos.
- Pruebas de integridad de datos.
- Validación de relaciones entre tablas.

---

## Documentación Realizada
Durante el proyecto se elaboró:
- Historia de Usuario.
- Requisitos funcionales.
- Test Scenarios.
- Test Cases.
- Evidencias de ejecución.
- Resultados de pruebas.

---

## Herramientas Utilizadas
- DBeaver.
- MySQL.
- Excel.
- GitHub.

---

## Resultado de Ejecución

Casos de prueba totales: **15**

### Resultados

- **PASS:** 15
- **FAIL:** 0
- **Bugs encontrados:** 0


## Conclusión
Se realizaron pruebas sobre la base de datos verificando correctamente el almacenamiento, consulta y relación de información entre usuarios, productos y pedidos.
Las consultas SQL permitieron validar la consistencia de los datos y comprobar el correcto funcionamiento de las relaciones entre tablas mediante JOIN.
