# Proyecto Docker - Procesador de Texto (Semana 14)

Este proyecto es una API desarrollada en Flask que procesa texto (cuenta palabras, frecuencia y genera resumen), containerizada con Docker y orquestada con Docker Compose.

## Arquitectura
- **Python 3.11-slim**: Imagen base ligera.
- **Flask**: Framework web para la API.
- **Docker Compose**: Para levantar el servicio fácilmente.

## Cómo ejecutar el proyecto

1. Construir y levantar el contenedor:
   ```bash
   docker compose up --build