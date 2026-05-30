# Medical-Appointment-Management-System

**Sistema integral de gestión médica para administración de pacientes, citas, consultas, afiliaciones y recetas médicas.**

Plataforma diseñada para clínicas, consultorios y centros de salud que permite gestionar el registro de pacientes, programación de citas, historial clínico, consultas médicas, afiliaciones y control de usuarios desde un único sistema centralizado.

![Java](https://img.shields.io/badge/Java-100%25-ED8B00?style=flat-square\&logo=java\&logoColor=white)
![Swing](https://img.shields.io/badge/UI-Java_Swing-007396?style=flat-square)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![MVC](https://img.shields.io/badge/Architecture-MVC-success?style=flat-square)
![Desktop](https://img.shields.io/badge/Application-Desktop-blue?style=flat-square)

---

![imagen alt](https://github.com/DimasDaniel123/Andre-Zamiria-Sistema-De-Citas-Medicas/blob/eb05150044a90511b44ddb3e49494df521d779e8/src/Img/Login-Citas.png)

---

# ¿Qué es Medical Appointment Management System?

**Medical Appointment Management System (MAMS)** es una aplicación desarrollada para automatizar y optimizar la gestión de pacientes y servicios médicos.

Permite registrar pacientes, generar citas, administrar consultas médicas, emitir recetas, controlar afiliaciones y mantener un historial clínico completo para mejorar la atención y organización de los centros de salud.

---

![imagen alt](https://github.com/DimasDaniel123/Andre-Zamiria-Sistema-De-Citas-Medicas/blob/eb05150044a90511b44ddb3e49494df521d779e8/src/Img/menu-Citas.png)

---

# 🏥 Flujo Operativo

| Etapa | Descripción                  |
| ----- | ---------------------------- |
| 1     | Registro de usuario          |
| 2     | Inicio de sesión             |
| 3     | Registro de paciente         |
| 4     | Registro de afiliación       |
| 5     | Generación de cita           |
| 6     | Confirmación de cita         |
| 7     | Atención médica              |
| 8     | Registro de consulta         |
| 9     | Emisión de receta            |
| 10    | Almacenamiento del historial |

---

# 📊 Dashboard Principal

Centro de control para la gestión médica.

### Funcionalidades

* Total de pacientes registrados
* Citas programadas
* Citas atendidas
* Pacientes afiliados
* Consultas médicas realizadas
* Recetas emitidas
* Usuarios activos
* Estadísticas generales

### Estados de Citas

| Estado     | Color    |
| ---------- | -------- |
| Programada | Azul     |
| Confirmada | Verde    |
| Pendiente  | Amarillo |
| Atendida   | Gris     |
| Cancelada  | Rojo     |

---

# 👨‍⚕️ Gestión de Pacientes

Permite registrar y administrar toda la información de los pacientes.

### Información registrada

* DNI
* Nombres y Apellidos
* Fecha de nacimiento
* Sexo
* Dirección
* Teléfono
* Correo electrónico
* Tipo de afiliación

---

# 📅 Gestión de Citas Médicas

Módulo encargado de programar y controlar las citas.

### Funciones

* Generación de nueva cita
* Reprogramación de citas
* Cancelación de citas
* Consulta de agenda médica
* Control de asistencia
* Historial de citas

---

# 🩺 Consultas Médicas

Registro completo de la atención médica realizada.

### Incluye

* Motivo de consulta
* Diagnóstico
* Observaciones médicas
* Tratamiento
* Signos vitales
* Historial clínico

---

# 💊 Gestión de Recetas Médicas

Permite emitir y consultar recetas médicas.

### Características

* Registro de medicamentos
* Dosis recomendada
* Frecuencia de consumo
* Duración del tratamiento
* Observaciones médicas
* Historial de recetas

---

# 🧾 Gestión de Afiliados

Administración de pacientes afiliados a seguros o programas médicos.

### Funciones

* Registro de afiliación
* Actualización de datos
* Consulta de afiliados
* Estado de afiliación
* Historial de afiliaciones

---

# 👥 Gestión de Usuarios

Control de acceso al sistema.

### Roles

* Administrador
* Médico
* Recepcionista
* Asistente

### Funcionalidades

* Registro de usuarios
* Inicio de sesión
* Gestión de permisos
* Cambio de contraseña
* Auditoría de accesos

---

# 📖 Historial Clínico

Visualización completa del historial médico del paciente.

### Información disponible

* Datos personales
* Citas registradas
* Consultas realizadas
* Diagnósticos anteriores
* Recetas emitidas
* Afiliaciones registradas

---

# 🏗️ Arquitectura

El sistema utiliza arquitectura MVC.

| Capa       | Función             |
| ---------- | ------------------- |
| Model      | Gestión de datos    |
| View       | Interfaces gráficas |
| Controller | Lógica del sistema  |

---

# Estructura del Proyecto

```text
Medical-Appointment-Management-System/
│
├── src/
│   ├── controller/
│   ├── model/
│   ├── view/
│
├── database/
│
├── resources/
│
├── lib/
│
└── README.md
```

---

# Tecnologías Utilizadas

| Tecnología | Uso                  |
| ---------- | -------------------- |
| Java       | Desarrollo principal |
| Java Swing | Interfaz gráfica     |
| MySQL      | Base de datos        |
| JDBC       | Conexión BD          |
| MVC        | Arquitectura         |
| NetBeans   | IDE de desarrollo    |

---

# Distribución del Código

* Java → 100%

---

# 🚀 Funcionalidades Implementadas

* [x] Login de usuarios
* [x] Registro de usuarios
* [x] Registro de pacientes
* [x] Registro de afiliados
* [x] Generación de citas médicas
* [x] Control de citas
* [x] Gestión de consultas médicas
* [x] Gestión de recetas
* [x] Historial clínico completo
* [x] Administración de usuarios
* [x] Dashboard principal

---

# Beneficios

* Automatización del proceso de atención médica
* Organización eficiente de pacientes
* Gestión centralizada de citas
* Acceso rápido al historial clínico
* Mejor control administrativo
* Reducción de errores en registros
* Mayor productividad del personal médico
* Mejor experiencia para los pacientes
