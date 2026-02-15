# Tarea 1 Backend 2

** Nombre Completo:** Albany Anmabel Luciani Mujica

## 1. Instancia de Base de Datos

- **Enlace a la instancia:** (https://console.prisma.io/cmlk3zaui02h4w8efulaq9bbp/cmlk411ai02awx7edkk3l5is7/cmlk411ai02aux7ed675iykue/studio)

* _Cadena de Conexión:_
  postgresql://usuario:\*\*\*\*@db.prisma.io:5432/postgres?sslmode=require

(URL y usuario visibles, contraseña oculta por seguridad)

---

## 2. Conexión desde Spring Boot

![Log de Conexión Exitosa en Spring Boot](SprintBoot_Conexion.png)

---

## 3. Pruebas de la API (CRUD)

### [POST] Crear Registro

Captura de la solicitud (Request) y la respuesta (Response) en Postman/Insomnia:
![POST Request and Response](POST_CrearEstudiante2.png)
![POST Request and Response](POST_CrearEstudiante3.png)

### [GET] Obtener Todos (All)

![GET All Request and GET All Response](GET_TraerTodos.png)

### [GET] Obtener por ID

![GET by ID Request and GET by ID Response](GET_BuscarporID.png)

### [GET] Obtener por Email

![GET by Email Request and GET by Email Response](GET_BuscarporCorreo.png)

### [PUT] Actualizar Registro

![PUT Request and PUT Response](PUT_ActualizarDatos.png)

### [DELETE] Eliminar Registro

![DELETE Request and DELETE Response](DELETE_EliminarEstudiante.png)

---

## 4. Pruebas Internas del Proyecto

![Resultados de Pruebas Internas](TEST_PruebasFinales.png)

> _Estado final:_ Todas las pruebas pasaron exitosamente.

---

Este repositorio es un fork del proyecto original para la asignatura de Backend 2.---
