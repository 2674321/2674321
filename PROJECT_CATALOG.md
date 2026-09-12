# Catálogo de Proyectos · 2674321

Catálogo maestro del ecosistema de proyectos de **Patricio Varela C. (CA2OPX)**.
Este repositorio es la **portada del perfil** y el índice público del ecosistema:
cada proyecto tiene un **número histórico estable** que también se usa en el
workspace local para nombrar su carpeta (`NN_NombreProyecto`).

> Resumen en [`README.md`](README.md) · Inventario detallado en este documento.

## Catálogo completo

| Nº | Nombre local | Repositorio | Inicio | Incorporado¹ | Tipo | Estado | Relación |
|---:|---|---|---|---|---|---|---|
| 01 | `01_CESFAM_SJ` | [cesfam-san-juan-padds](https://github.com/2674321/cesfam-san-juan-padds) | 2026-08-13 | ≈ 2026-08-13 | Git | En uso | — |
| 02 | `02_Base_Datos` | [base-datos-defensa-civil](https://github.com/2674321/base-datos-defensa-civil) | 2026-08-18 | ≈ 2026-08-18 | Git | En desarrollo | — |
| 03 | `03_Asistencia_Digital` | [asistencia-digital-bomberos](https://github.com/2674321/asistencia-digital-bomberos) | 2026-08-19 | ≈ 2026-08-19 | Git | Deprecado | — |
| 04 | `04_Carro_de_Paro` | [carro-de-paro](https://github.com/2674321/carro-de-paro) | 2026-08-19 | ≈ 2026-08-19 | Git | En uso | — |
| 05 | `05_Claves` | [guia-radiocomunicaciones-ca2opx](https://github.com/2674321/guia-radiocomunicaciones-ca2opx) | 2026-08-20 | ≈ 2026-08-20 | Git | Activo | — |
| 06 | `06_2674321` | [2674321](https://github.com/2674321/2674321) (este perfil) | 2026-08-20 | ≈ 2026-08-20 | Perfil | Activo | — |
| 07 | `07_seguimiento-baterias-pernostock-ltda` | [seguimiento-baterias-pernostock-ltda](https://github.com/2674321/seguimiento-baterias-pernostock-ltda) | 2026-08-20 | ≈ 2026-08-20 | Git | Histórico | origen de 15 |
| 08 | `08_pagina-web-aurea-salud` | [pagina-web-aurea-salud](https://github.com/2674321/pagina-web-aurea-salud) | 2026-08-20 | ≈ 2026-08-20 | Git | Experimental | — |
| 09 | `09_Sistema cotizaciones-servicitecnico-programacion` | [sistema-cotizaciones](https://github.com/2674321/sistema-cotizaciones) | 2026-08-21 | ≈ 2026-08-21 | Git | En migración | — |
| 10 | `10_Sistema-Gestion-Sectores-ECICEP` | [Sistema-Gestion-Sectores-ECICEP](https://github.com/2674321/Sistema-Gestion-Sectores-ECICEP) | 2026-08-21 | ≈ 2026-08-21 | Git | Activo | — |
| 11 | `11_sistema-de-guardias` | [sistema-de-guardias](https://github.com/2674321/sistema-de-guardias) | 2026-08-24 | ≈ 2026-08-24 | Git | En uso | — |
| 12 | `12_VantOps` | [vantops-chile](https://github.com/2674321/vantops-chile) | 2026-08-26 | ≈ 2026-08-26 | Git | En desarrollo | — |
| 13 | `13_github-repository-auditor` | [github-repository-auditor](https://github.com/2674321/github-repository-auditor) | 2026-08-27 | ≈ 2026-08-27 | Git | Estable | — |
| 14 | `14_generador-etiquetas-pernostock` | [generador-etiquetas-pernostock](https://github.com/2674321/generador-etiquetas-pernostock) | 2026-08-31 | ≈ 2026-08-31 | Git | Activo | — |
| 15 | `15_seguimiento-baterias-pernostock-ltda` | *Sin repositorio público (local)* | 2026-08-31 | ≈ 2026-08-31 | DEV | DEV local | derivado DEV de 07 |

¹ Proyectos incorporados antes de la convención de numeración (2026-09-12): la fecha de
incorporación se toma como la del primer commit. Los proyectos nuevos registrarán fecha de
inicio e incorporación por separado.

**Tipos**: `Git` = repositorio público en GitHub · `Perfil` = este repositorio ·
`DEV` = solo local, sin publicar.

## Descripciones

### En uso
| Nº | Proyecto | Descripción |
|---:|---|---|
| 11 | Sistema · Gestión de Guardias | Calendarización y gestión de guardias para la 1ª Compañía de Bomberos del CBC (Coquimbo): niveles Inicial/Operativo/Profesional con cupos por día, asistencia, baja protegida con código enviado al correo y panel de administración integrado sobre Google Sheets. |
| 09 | Sistema · Cotizaciones PDF | Generador de cotizaciones profesionales para servicios tecnológicos: JSON → plantilla HTML → PDF con WeasyPrint, QR de verificación + hash SHA-256 anti-alteraciones, desglose justificado de la inversión y numeración automática. |
| 01 | Sistema · Seguimiento Clínico PADI | Sistema de seguimiento clínico desarrollado a solicitud del Servicio PADI (Coquimbo): registro de pacientes con dependencia, cuidador principal, controles y patologías crónicas, alertas de vigencia y agenda. |
| 04 | Sistema · Control de Carro de Paro | Revisión de inventario de carros de paro (urgencia ambulatoria y móviles): medicamentos e insumos, revisiones periódicas, stock y vencimientos. |
| 10 | Sistema ECICEP | Sistema personal de registro y gestión clínica de pacientes: formulario web único de captura, identificación y deduplicación, modelo de estratificación por sectores (naranjo/amarillo/verde), panel de control, estadísticas REM (Excel/PDF), cola de calidad y backups — Google Sheets + Apps Script · **IA**: integración de la API de Gemini con análisis y calidad de datos, validación local de duplicados e integridad, corrección asistida y auditoría trazable · 🧪 [demo del formulario](https://2674321.github.io/Sistema-Gestion-Sectores-ECICEP/) |
| 05 | Manual · Guía de Radiocomunicaciones | Manual de campo imprimible (A4) con los códigos de radio usados en emergencias en Chile — Código Q (UIT), Claves R (CONAF) y alfabeto fonético OACI — en dos versiones: Claves 10 del Cuerpo de Bomberos de Coquimbo y Códigos 10 de Banda Ciudadana (CB). Incluye tarjetas con QR listas para imprimir · 🌐 [ver online](https://2674321.github.io/guia-radiocomunicaciones-ca2opx/) |

### En desarrollo
| Nº | Proyecto | Descripción |
|---:|---|---|
| 02 | Base de Datos · Defensa Civil | Sistema integral para la Defensa Civil de Chile, Sede La Serena: voluntarios con grados y especialidades, eventos, entregas de equipamiento e inventario, con dashboard y control de acceso. |
| 12 | VantOPS | PWA para operaciones con RPAS/drones (React + Vite + TypeScript): planeación y gestión de operaciones de drones. |
| 13 | Repository Health Auditor | CLI de auditoría de repositorios GitHub en Python (`repo-auditor`, Python ≥ 3.10), con pruebas y revisión de salud de repos. |
| 14 | Generador de Etiquetas | Generador de etiquetas para Pernostock (Ruby/GTK3); línea hermana de la aplicación de baterías. |

### Histórico / experimental / dev local
| Nº | Proyecto | Descripción |
|---:|---|---|
| 03 | Asistencia Digital · Bomberos | Propuesta de digitalización del registro de asistencia de voluntarios de la 1ª Compañía de Bomberos de Coquimbo. Descontinuada: exige el formato institucional exacto, pendiente de replicar digitalmente · ▶️ [demo](https://2674321.github.io/asistencia-digital-bomberos/) |
| 07 | Seguimiento de Baterías | Aplicación de escritorio en Ruby/GTK3 + SQLite desarrollada para Pernostock Ltda: registro, búsqueda, historial, estadísticas y copias de seguridad de baterías. |
| 08 | Aurea Salud · web | Prototipo experimental de plataforma de salud/telemedicina: landing informativa, login simulado y panel administrativo estático. Incompleto por diseño; conservado como referencia de aprendizaje. |
| 06 | Perfil de GitHub | El repositorio donde está este catálogo: sirve de portada e índice maestro del ecosistema. |
| 15 | Seguimiento de Baterías (DEV) | Derivación DEV local independiente de la línea del proyecto 07. Sin repositorio público. |

## Relaciones entre proyectos

### 07 → 15 · Seguimiento de Baterías

El proyecto **15** es una derivación **DEV local independiente** de la línea
histórica del proyecto **07**. Comparten la misma base de la aplicación pero son
entornos distintos: 07 es el histórico (público) y 15 es el espacio de trabajo
local de desarrollo (sin remoto). **No** son el mismo repositorio ni debe
asumirse que 15 tenga contraparte pública.

## Regla para nuevos proyectos

Cuando se incorpore un nuevo proyecto al ecosistema:

1. determinar si realmente es un proyecto;
2. verificar si ya existe;
3. verificar Git/GitHub;
4. asignar el siguiente número;
5. registrar la fecha de inicio;
6. registrar la fecha de incorporación;
7. agregarlo al catálogo;
8. no renumerar proyectos existentes.

Ejemplo:

| | |
|---|---|
| Actualmente | `15` = último número utilizado |
| Nuevo | `16_NuevoProyecto` |
| GitHub | `2674321/NuevoProyecto` |

## Convención

> Los números son identificadores históricos estables utilizados para organizar
> el ecosistema local de proyectos de `2674321`. No forman parte del nombre de
> los repositorios de GitHub y no se renumeran cuando se incorporan nuevos proyectos.

- El orden numérico no representa necesariamente la fecha absoluta de creación de cada proyecto.
- Los proyectos nuevos reciben el siguiente número disponible (el próximo es el **16**).
- Los números retirados no se reciclan.
- La numeración es **local y estable**: el nombre del repositorio en
  GitHub conserva su nombre original (p. ej. local `12_VantOps` ⇄ GitHub `VantOps`).

---

*Catálogo sincronizado con el workspace local `07_Proyectos` (estructura plana,
numeración estable 01–15). Actualizado el 2026-09-12.*