# PracWay — Sistema Integral de Gestión de Prácticas Profesionales (PPP)

> Plataforma web full stack desarrollada para la gestión completa del Programa de Prácticas Pre Profesionales en (PPP) de la Universidad Peruana Unión (UPEU).

---

# Descripción General

**PracWay** es un sistema web académico diseñado para automatizar, centralizar y optimizar el proceso completo de gestión de prácticas profesionales universitarias.

La plataforma permite administrar:

- Solicitudes PPP
- Estudiantes
- Empresas
- Supervisores académicos y empresariales
- Evaluaciones
- Horarios
- Requisitos documentales
- Reportes
- Auditoría
- Notificaciones
- Seguridad por roles
- Gestión documental cloud

El proyecto fue desarrollado bajo una arquitectura moderna full stack utilizando Angular + Spring Boot + Oracle Database + AWS S3.

---

# Arquitectura General

```text
Frontend (Angular 18)
        ↓
REST API (Spring Boot 3)
        ↓
Oracle Database
        ↓
AWS S3 (Documentos)
```

---

# Frontend

## Tecnologías Utilizadas

| Tecnología | Versión |
|---|---|
| Angular | 18.2.5 |
| TypeScript | 5.5.2 |
| PrimeNG | 17.18.12 |
| PrimeFlex | 3.3.1 |
| RxJS | 7.8 |
| STOMP.js | 7.1.1 |
| SockJS | 1.6.1 |
| Chart.js | 4.4.6 |
| jsPDF | 3.0.1 |
| xlsx | 0.18.5 |

---

# Backend

## Tecnologías Utilizadas

| Tecnología | Versión |
|---|---|
| Spring Boot | 3.3.4 |
| Java | 17 |
| Maven | 3.9+ |
| Spring Security | — |
| JWT | 0.12.3 |
| Hibernate / JPA | — |
| Oracle Database | — |
| AWS SDK S3 | 2.29.9 |
| Apache POI | 5.2.3 |

---

# Seguridad Implementada

- JWT Authentication
- Spring Security
- BCrypt Password Encoder
- Roles y permisos
- Protección de endpoints
- Blacklist de tokens
- Interceptor JWT personalizado

---

# Roles del Sistema

| Rol | Descripción |
|---|---|
| ADMIN | Acceso completo |
| COORDINADOR | Gestión del programa PPP |
| ESTUDIANTE | Solicitud y seguimiento de prácticas |
| SUPERVISOR | Evaluación y monitoreo |
| SECRETARIA | Gestión administrativa |
| DIRECTORAVCM | Control de horas VCM |

---

# Características Destacadas

- Arquitectura Full Stack moderna
- Angular + Spring Boot
- Oracle Database
- Seguridad JWT
- Roles y permisos
- AWS S3
- Reportes PDF/Excel
- WebSockets en tiempo real
- Auditoría completa
- Formularios reactivos
- Gestión documental
- Arquitectura escalable
- Sistema multirol

---

# Documentación y Evidencias del Proyecto

## 1. `EntregableOFFCompletoPPP.pdf`

Documento técnico principal del proyecto.

Contiene:
- Arquitectura completa del sistema
- Backend y Frontend
- Base de datos
- Seguridad
- Diagramas
- Flujo funcional
- Evidencias del sistema
- Implementación técnica
- Integraciones
- Resultados finales

---

## 2. `DIAGRAMA-BD-PPP.drawio`

Diagrama técnico completo de la arquitectura y modelo de base de datos del sistema.

Incluye:
- Relaciones entre entidades
- Modelo lógico
- Organización de tablas
- Diseño estructural de la base de datos
- Arquitectura relacional

---

## 3. Diccionario de Datos y Documentación de Base de Datos

Documentación avanzada de la base de datos Oracle.

Incluye:
- Scripts de creación de tablas
- Triggers
- Relaciones
- Llaves primarias y foráneas
- Procedimientos documentados
- Diccionario técnico completo

https://www.canva.com/design/DAGVwB2EX9M/SnQGGlWTu8ca3-MllryXFw/edit

---

## 4. Prototipos UI/UX — Figma

Diseño visual y experiencia de usuario del sistema PracWay.

Incluye:
- Wireframes
- Mockups
- Flujo de navegación
- Interfaces por roles
- Diseño UX/UI completo

https://www.figma.com/design/1kiXYdUVXE4oSAhKRSKCTR/P-I-2.0?node-id=92-1082&p=f&t=Lb15lclevAkCg9q3-0

---

## 5. Videos Funcionales del Sistema

Demostración final del sistema completamente operativo.

Incluye:
- Login y autenticación
- Gestión de estudiantes
- Gestión de empresas
- Solicitudes PPP
- Evaluaciones
- Roles y permisos
- Integración frontend/backend
- Flujo funcional completo

https://drive.google.com/drive/folders/1dN0a-rjC2PfmhcG4iVrxqC4QZv9aJeQY

---

## 6. `Caso Redactado PPP.pdf`

Documento formal de análisis y planteamiento del proyecto.

Incluye:
- Problemática
- Objetivos
- Justificación
- Alcance
- Requerimientos funcionales y no funcionales
- Análisis del sistema

---

## 7. `PPT-ProyectoPPP.pdf`

Presentación oficial utilizada para la exposición académica final.

Incluye:
- Resumen ejecutivo
- Arquitectura
- Tecnologías utilizadas
- Evidencias visuales
- Resultados
- Conclusiones

---

# Habilidades Técnicas Demostradas

## Frontend
- Angular
- TypeScript
- PrimeNG
- RxJS
- WebSockets
- JWT Authentication

## Backend
- Spring Boot
- Spring Security
- JPA/Hibernate
- REST APIs
- Arquitectura multicapa

## Base de Datos
- Oracle Database
- Modelado relacional
- Triggers
- Procedimientos
- Optimización SQL

## Cloud & DevOps
- AWS S3
- SMTP
- Maven
- Git/GitHub

---

# Equipo de Desarrollo

| Integrante | Correo |
|---|---|
| **Prantex Mixel H. Meza Salcedo** | mixolms@gmail.com |
| **Miguel Angel Godoy Fabián** | mgodoyfabian@gmail.com |
| **Axell M. Cardenas Portocarrero** | matiascard34@gmail.com |
| **Yesenia Ramirez Medina** | stefanyramirezmedina@gmail.com |
| **Juan Sebastián Espiritu Orejon** | sebastiandefray413@gmail.com |
| **Carlos Rafael Veli Capcha** | carlosveli777@gmail.com |


---

# Nota Importante

Este repositorio se encuentra en modo privado y el código fuente completo no puede ser publicado públicamente debido a restricciones académicas e institucionales.

Sin embargo, este repositorio contiene:
- Documentación técnica
- Arquitectura del sistema
- Diagramas
- Evidencias funcionales
- Videos demostrativos
- Prototipos
- Estructura del proyecto

---

# Contacto

## Carlos Rafael Veli Capcha

Estudiante de Ingeniería de Sistemas  
Backend Developer | Full Stack Developer | Infrastructure & Networks

Correo: carlosveli777@gmail.com

---

# Estado del Proyecto

- Proyecto Finalizado
- Sistema Funcional
- Backend + Frontend Integrados
- Base de Datos Operativa
- Documentación Completa
- Despliegue Académico Realizado