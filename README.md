# Configuración centralizada - Sistema Educativo

**Autor:** Andrés Felipe Villota Cabrera

Este repositorio contiene los archivos de configuración para los microservicios del sistema educativo que desarrollé con arquitectura basada en microservicios. La idea principal es tener un lugar central desde donde cada servicio pueda obtener su configuración al momento de iniciar, usando Spring Cloud Config.

---

## ¿Qué servicios se configuran desde aquí?

Hasta el momento, tengo configurados estos microservicios:

- `usuarios-servicio`
- `asignaturas-servicio`
- `matriculas-servicio`

Cada uno tiene su archivo independiente, donde se definen cosas como el puerto del servidor, los datos de conexión a la base de datos, el nombre del servicio, entre otros detalles.

---

## Estructura del repositorio

sistema-educativo-config/ ├── usuarios-servicio.properties ├── asignaturas-servicio.properties ├── matriculas-servicio.properties

