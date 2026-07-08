# RQY1102_-MirandaProvosteChamblas-_ET

# El Mirador — Sistema de Gestión Residencial

Prototipo de un sistema de administración para el edificio **El Mirador**, desarrollado como proyecto académico de Ingeniería de Software. La aplicación centraliza la administración de un condominio (residentes, unidades, finanzas, comunicaciones y solicitudes), con foco en el módulo de **Gestión de Residentes**, el único implementado de forma funcional en esta etapa.

## Descripción

El sistema está pensado como una plataforma modular para la administración integral del edificio. El panel principal organiza siete módulos (Usuarios y Acceso, Residentes y Unidades, Financiamiento y Cobranza, Notificaciones, Solicitudes, Consultas y Reportes), de los cuales el resto queda proyectado para futuras iteraciones.

### Módulo de Gestión de Residentes

Cumple el requisito de permitir el **registro, actualización y desactivación** de residentes manteniendo **trazabilidad histórica**. Incluye:

- Registro de residentes con validación de datos (RUT con formato chileno `XX.XXX.XXX-X`, contacto, tipo propietario/arrendatario, unidad y contacto de emergencia).
- Actualización de datos con el RUT bloqueado para preservar la identidad del registro.
- Desactivación y reactivación con confirmación, conservando el historial completo.
- Reglas de unicidad para RUT, correo y teléfono.
- Búsqueda, filtros por estado y tarjetas de métricas (total, activos, inactivos).
- Login de administrador y control de acceso por sesión.

## Contenido del repositorio

- **Prototipo** — Interfaz navegable en Figma (ver enlace más abajo).
- **Documentación** — Documento de Arquitectura de Software (DAS), planilla de requisitos, registro de casos de prueba, evaluación heurística de Nielsen y control de versiones del prototipo.
- **Diagramas UML** — Casos de uso, clases, actividad, componentes y despliegue.
- **Capturas** — Pantallas del prototipo (login, panel, gestión y formularios).

## Prototipo

[Ver prototipo en Figma](https://www.figma.com/make/mbAGVxglhrdmM2cL9YYLXV/Aplicaci%C3%B3n-de-gesti%C3%B3n-de-residentes?preview-route=%2Flogin)

Credenciales de prueba: `admin@elmirador.com` / `admin123`

## Equipo

Provoste · Miranda · Chamblas

## Contexto

Proyecto desarrollado para el ramo de Ingeniería de Software, Duoc UC.
