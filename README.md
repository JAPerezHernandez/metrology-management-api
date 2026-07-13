# 🧪 Metrology Management API

API REST desarrollada con **FastAPI** para la gestión de laboratorios de metrología. El sistema permitirá administrar técnicos, clientes, equipos, calibraciones y reportes de manera segura, escalable y siguiendo buenas prácticas de desarrollo de software.

## 📋 Descripción

Este proyecto tiene como objetivo simular un sistema utilizado por un laboratorio de metrología para administrar todo el proceso de calibración de equipos.

La API será desarrollada utilizando una arquitectura por capas (Layered Architecture), permitiendo un código limpio, mantenible y escalable.

---

## 🚀 Tecnologías

- Python 3.12
- FastAPI
- SQLAlchemy
- MySQL
- Pydantic
- JWT Authentication
- Alembic
- Git
- GitHub
- Docker *(Próximamente)*
- Pytest *(Próximamente)*

---

## 🏗 Arquitectura del proyecto

El proyecto seguirá una arquitectura por capas con separación de responsabilidades.

```
app/
│
├── api/
│   └── routers/
│
├── core/
│
├── database/
│
├── models/
│
├── repositories/
│
├── schemas/
│
├── services/
│
├── utils/
│
└── main.py
```

---

## ⚙ Funcionalidades planeadas

### Autenticación

- Inicio de sesión con JWT
- Cambio de contraseña
- Roles de usuario

### Técnicos

- Crear técnico
- Editar técnico
- Eliminar técnico
- Consultar técnicos

### Clientes

- Registro de clientes
- Actualización de información
- Consulta de clientes

### Equipos

- Registro de equipos
- Historial de calibraciones
- Estado del equipo

### Calibraciones

- Crear calibración
- Asignar técnico
- Registrar resultados
- Historial

### Reportes

- Generación de reportes
- Descarga en PDF
- Historial de reportes

---

## 📚 Objetivos de aprendizaje

Este proyecto forma parte de mi portafolio profesional como desarrollador Backend y tiene como finalidad aplicar conocimientos en:

- Desarrollo de APIs REST
- Arquitectura por capas
- Diseño de bases de datos relacionales
- Autenticación con JWT
- SQLAlchemy
- Buenas prácticas de desarrollo
- Git y GitHub
- Clean Code
- Principios SOLID

---

## 📈 Estado del proyecto

🚧 En desarrollo

Actualmente se encuentra en fase de construcción y mejora continua.

---

## 👨‍💻 Autor

**José Ángel Pérez Hernández**

Estudiante de Licenciatura en Desarrollo de Software.

Interesado en desarrollo Backend con Python, FastAPI, SQL y Cloud Computing.

---

## 📄 Licencia

Este proyecto es de uso educativo y forma parte de mi portafolio profesional.
