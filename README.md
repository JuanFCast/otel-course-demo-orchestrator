# otel-course-demo-orchestrator

Repositorio que orquesta los microservicios `FutureXCourseCatalog` y `FutureXCourseApp` usando Docker Compose y OpenTelemetry Collector para trazabilidad distribuida.

## Servicios

- 📘 [FutureXCourseCatalog](https://github.com/JuanFCast/part0-JaegerCourseCatalog)
- 📗 [FutureXCourseApp](https://github.com/JuanFCast/parte0-JaegerCourseApp)

## Requisitos

- Docker
- Docker Compose
- Git

## Instrucciones

1. Clonar los microservicios:

```bash
git clone https://github.com/JuanFCast/part0-JaegerCourseCatalog.git
git clone https://github.com/JuanFCast/parte0-JaegerCourseApp.git
````

2. Clonar este repositorio orquestador:

```bash
git clone https://github.com/JuanFCast/otel-course-demo-orchestrator.git
cd otel-course-demo-orchestrator
```

3. Ejecutar los servicios:

```bash
docker-compose up --build
```

## Observabilidad

Este entorno incluye:

* OpenTelemetry Collector
* Jaeger UI: `http://localhost:16686`

## Licencia

Este proyecto es solo para fines académicos.
