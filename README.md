# Proyectos de Renzo Paull Castañeda

Selección de trabajo personal, profesional y académico. Estas fichas permiten conocer el propósito, las tecnologías y mi participación sin publicar código de productos privados.

## AudiVare

**Contexto:** proyecto personal; SaaS en producción.

**Problema:** organizar documentación contable de varias empresas y controlar quién puede acceder a sus documentos.

**Mi trabajo:** desarrollo de la aplicación web y su backend, con autenticación, permisos, gestión de documentos y almacenamiento de archivos.

**Funciones implementadas:**
- Acceso con Google y autorización por empresa.
- Registro y edición de facturas, con historial de cambios.
- Importación de registros de compras desde archivos CSV y Excel.
- Almacenamiento de documentos y acceso mediante enlaces firmados.
- Gestión de pagos y detracciones.

**Tecnologías:** TypeScript, NestJS, Fastify, Next.js, React, PostgreSQL, Drizzle y almacenamiento compatible con S3.

**Enfoque técnico:** separar el acceso por empresa, validar permisos en el backend y mantener trazabilidad de los documentos. La importación de archivos no implica conexión automática con SUNAT ni emisión de comprobantes electrónicos.

**Disponibilidad:** código privado. Esta ficha presenta el alcance del producto; no se incluye una demo pública.

## E.I.G.R. CONTRATISTAS S.R.L. — Sistema de procura de bienes

**Contexto:** sistema desarrollado para E.I.G.R. CONTRATISTAS S.R.L.

**Problema:** organizar los requerimientos de bienes y los procesos relacionados con cotizaciones y transacciones.

**Mi trabajo:** desarrollé el backend y la interfaz web del sistema.

**Componentes desarrollados:** servicios de autenticación y usuarios, requerimientos, cotizaciones y transacciones; gateway y descubrimiento de servicios; interfaz web.

**Tecnologías:** Java 17, Spring Boot, Spring Cloud, Eureka, OpenFeign, MySQL, React, TypeScript y Vite.

**Enfoque técnico:** distribuir responsabilidades entre servicios, centralizar el acceso mediante un gateway y conectar la interfaz con las APIs.

**Disponibilidad:** repositorios de backend y frontend privados. Se presenta únicamente una descripción general; no se incluyen datos, documentos ni pantallas internas de la empresa.

## Proyectos académicos con código público

### API de mantenimiento de vehículos

**Contexto:** proyecto académico grupal del curso Software III, Ingeniería de Sistemas.

**Mi participación:** desarrollé la API como parte del equipo. El historial del repositorio conserva la autoría de los integrantes.

**Funcionalidades:** gestión de clientes, vehículos, talleres, mecánicos, mantenimientos, órdenes de trabajo y pagos; componentes de autenticación JWT; exportación RDF y consultas SPARQL.

**Herramientas:** Java 25, Spring Boot 3.5.6, Spring Data JPA, Spring Security, Auth0 java-jwt 4.5.0, MySQL, Apache Jena 4.10.0, Fuseki, Maven y Postman.

**Arquitectura:** backend por capas con controladores REST, servicios, repositorios, entidades, DTOs y mapeadores.

**Código público:** [revisar la API, su estructura y documentación](https://github.com/Paull-Cas/api-mantenimiento-vehiculos). Versión de presentación con configuración por variables de entorno y ejemplos ficticios. Es una entrega académica para revisión y pruebas locales; la autorización completa de rutas está pendiente.

### Integración de usuarios y cursos

Proyecto Java y Spring Boot organizado en dos servicios: usuarios y cursos. Utiliza APIs REST, persistencia con JPA y comunicación entre servicios con OpenFeign.

[Consultar código y documentación](https://github.com/Paull-Cas/curso-integracion).

## Contacto

[Perfil de GitHub](https://github.com/Paull-Cas) · [LinkedIn](https://www.linkedin.com/in/renzo-paull-casta%C3%B1eda-cabanillas-0a4748269/)
