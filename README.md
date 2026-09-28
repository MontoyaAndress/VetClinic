# 🐾 VetClinic — Sistema Web de Gestión para Clínica Veterinaria

> Aplicación web en PHP y MySQL para el registro de clientes y la gestión de citas veterinarias, con roles diferenciados de administrador y usuario.

---

## 📋 Descripción

VetClinic es un sistema de gestión pensado para una clínica veterinaria, que permite a los clientes registrarse, iniciar sesión y agendar citas para sus mascotas, mientras que el administrador cuenta con un panel propio para visualizar, editar y eliminar todas las citas registradas.

## ✨ Funcionalidades

- **Registro de usuarios** con datos completos (nombre, dirección, teléfono, cuenta bancaria, RFC).
- **Login con roles diferenciados**:
  - **Administrador** → panel con la totalidad de las citas registradas.
  - **Cliente** → panel con únicamente sus propias citas ("Mis citas").
- **Gestión de citas (CRUD)**:
  - Registro de nueva cita: tipo de animal, nombre de la mascota, edad, síntomas, fecha, hora, datos de contacto.
  - Edición y eliminación de citas (panel de administrador).
  - Visualización de historial de citas por cliente.
- **Sitio informativo** con secciones de servicios (`service.php`) y datos de contacto de la clínica.

## 🛠️ Stack tecnológico

| Categoría | Tecnología |
|---|---|
| Backend | PHP |
| Base de datos | MySQL (MySQLi) |
| Frontend | HTML, CSS, Bootstrap, MDB (Material Design Bootstrap) |
| Otros | jQuery |

## 🗂️ Estructura del proyecto

<img width="501" height="334" alt="image" src="https://github.com/user-attachments/assets/2c7b1eec-06b9-4f2d-aa0c-18cbd5d7c209" />

## 🗄️ Base de datos

Tablas principales:
- **`usuarios`** — clientes y administradores (código, nombre, apellidos, contacto, credenciales, rol).
- **`alumnos`** — registro de citas veterinarias (dueño, tipo de animal, nombre de mascota, edad, síntomas, fecha, hora, contacto).

## 🚀 Instalación local

1. Clona el repositorio.
2. Importa `escuela2.sql` en tu servidor MySQL local (ej. phpMyAdmin / XAMPP).
3. Ajusta las credenciales de conexión en `conexion.php` si es necesario.
4. Coloca el proyecto en el directorio de tu servidor local (ej. `htdocs` de XAMPP).
5. Accede desde el navegador a `indexLogin.php` para iniciar sesión o registrarte.

---
