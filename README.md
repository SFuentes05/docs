# Sistema de Validación de Consumos Paso Rápido

Herramienta de validación de consumos de peajes exportados desde la aplicación oficial Paso Rápido del gobierno dominicano.

## Acerca del Sistema

Esta herramienta permite validar automáticamente los consumos de peajes exportados desde la aplicación Paso Rápido del gobierno dominicano, cruzándolos con datos de telemetría GPS de vehículos registrados en ERM Telematics.

## Características Principales

- **Importación de CSV**: Procesa archivos exportados desde la app oficial Paso Rápido
- **Integración ERM Telematics**: Conecta con datos de vehículos, proyectos, eventos y viajes
- **Validación GPS**: Verifica ubicación del vehículo contra telemetría ERM al momento del cobro
- **Detección de Anomalías**: Identifica duplicados, sobrecargos y tags inhabilitados
- **Tabla Puente**: Utiliza `tag_assignments` para vincular datos de ambos sistemas
- **Reportes de Validación**: Análisis detallados con exportación a Excel

## Estructura de la Documentación

- **Introducción**: Flujo de trabajo e integración de sistemas
- **Conceptos Básicos**: Terminología y entidades del sistema
- **Modelos de Datos**: Estructura de las tablas y relaciones
- **Sistema de Validación**: Funcionamiento interno de las validaciones
- **Guías de Usuario**: Instrucciones paso a paso para operadores
- **Flujos de Trabajo**: Procesos completos desde exportación hasta reportes

## Soporte Técnico

Para consultas técnicas o solicitudes de implementación:
- Email: sfuentes@solidarityagents.com
- Aplicación: [United Petroleum App](https://unitedpetroleum.app)
- Portal: [United Petroleum](https://unitedpetroleum.com.do)

---

*Módulo de validación desarrollado para integrar Paso Rápido (Gobierno Dominicano) con ERM Telematics* 