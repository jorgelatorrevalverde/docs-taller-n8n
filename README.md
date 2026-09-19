# Taller Esteval - Sistema de Automatización (ERP/CRM)

## Descripción del Proyecto
Este repositorio contiene la documentación pública y el resumen de la arquitectura del sistema de automatización desarrollado para la transformación digital del Taller Esteval. 

*Nota: Debido a que el sistema maneja datos de clientes y credenciales sensibles de bases de datos, el código fuente y los flujos completos se mantienen en un repositorio privado.*

## Arquitectura y Tecnologías
El ecosistema está construido integrando las siguientes herramientas:
* **n8n**: Orquestador principal (self-hosted) para conectar todas las APIs y automatizar los flujos de trabajo diarios.
* **Retell AI**: Integración de inteligencia artificial conversacional por voz para actuar como recepcionista virtual.
* **Trello API**: Sistema Kanban automatizado para el seguimiento en tiempo real del estado de las peritaciones y reparaciones.
* **SQL Server**: Conexión bidireccional con el ERP interno (`clickplus`) para la gestión de citas y vehículos.

## Estado actual
En desarrollo activo. Las automatizaciones actuales gestionan el enrutamiento de clientes ("Vía A" para citas estándar y "Vía B" para peritaciones) y la lectura/escritura en base de datos.
