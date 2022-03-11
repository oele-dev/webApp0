---
marp: true
theme: gaia
_class: lead
size: 4:3
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---
# **Bienvenidos**

Construye una WebApp desde 0

[oeleco](http://oeleco.github.io)

---
# **Primeros pasos**

* Instalación de la DB
* Introducción a SQL
* Introducción a HTML y CSS

---
# Instalación de la DB

Sistema gestor de base de datos:
* MySQL
* MariaDB
* PostgreSQL

---
<!--
_backgroundColor: black
_color: white
-->

### SGBD

Al igual que en un evento, la logistica como el SGBD es el encargado de garantizar la *seguridad*, *orden* e *integridad* de los participantes.

![bg](https://cdn.pixabay.com/photo/2016/11/22/19/15/audience-1850119_1280.jpg)

---
## Consola de administración
Acceder
`mysql -u root -p`

Inspeccionar bases de datos;
`show databases;`

Crear base de datos
`create database tests1;`

Seleccionar la base de datos
`use tests1;`

---
## Nuestra primera tabla

Crear tabla
```
create table test1_table (id integer,name varchar(50));
```

Inspeccionar tabla
`show columns from test1_table`

Consultar registros
`select * from test1_table;`

---
## Primeras acciones

Insertar registro
```
insert into (id,name)
    values (1,pepito);
```

Actualizar un registro de la tabla
```
update test1_table
set name = 'pepito perez' WHERE id = 1;
```

Eliminar registro
`delete from test1_table WHERE id = 2;`

---
<!--
_backgroundColor: black
_backgroundImage: ''
_color: white
-->
## **WHERE**

> Como regla universal nunca debe falta la sentencia WHERE en la actualización y eliminación de registros.
---
### **Acciones básicas**

## CRUD
* Create
* Read
* Update
* Delete

---
<!--
_backgroundColor: black
_color: black
-->
![bg](https://cdn.pixabay.com/photo/2019/11/25/18/22/food-4652720_1280.jpg)
<br>
# BREAD in the new CRUD
---

### **Acciones básicas**

## BREAD

* Browse
* Read
* Edit
* Add
* Delete

---

# **Gracias**

twitter.com/@oele_co

oeleco.github.io