Coquimbo, Chile 🇨🇱

**CA2OPX** · **Bomb. OP.** · **Operador RPAS** · **D.C V.M**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--1087--9445-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-1087-9445)

Desarrollo soluciones digitales para **salud pública, emergencias y gestión institucional**:
sistemas operativos de bomberos, Defensa Civil y atención
primaria de salud.

## Tecnologías

![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square)
![REST/API](https://img.shields.io/badge/REST_API-0D9488?style=flat-square)
![Data Quality](https://img.shields.io/badge/Data_Quality-2563EB?style=flat-square)
![Data Validation](https://img.shields.io/badge/Data_Validation-1E40AF?style=flat-square)
![Automation](https://img.shields.io/badge/Automation-7C3AED?style=flat-square)
![Audit Logging](https://img.shields.io/badge/Audit_Logging-334155?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

- **Google Apps Script + clasp**: sistemas de gestión sobre Google Workspace (Sheets como base de datos, UI web propia, PDFs, dashboards)
- **IA generativa (Gemini API)**: análisis y calidad de datos, detección de inconsistencias, duplicados, integridad, corrección asistida y auditoría dentro de sistemas funcionales
- **PWA offline-first**: aplicaciones de terreno que funcionan sin conexión
- **CI con GitHub Actions**: verificación automática de sintaxis y pruebas

## IA & Automatización

Estoy incorporando **IA generativa de forma práctica dentro de sistemas
funcionales**, como extensión de aplicaciones que ya operan en producción sobre
Google Workspace.

En el sistema **ECICEP** (`Google Apps Script + Google Sheets`) integro la
**API de Gemini** para tareas de análisis, validación y calidad de datos:

- **Análisis de calidad de datos**: detección de inconsistencias de formato,
  campos vacíos y patrones sobre la estructura de las hojas.
- **Validación local**: detección de duplicados y verificación de integridad de
  eventos ejecutadas en memoria, **sin enviar registros identificables a la API**.
- **Corrección asistida**: normalización de RUT, fechas, nombres, teléfonos y
  sexo reutilizando validadores deterministas, con registro trazable en `LOG_IA`.
- **Automatización y auditoría**: retry/backoff ante límites del proveedor,
  configuración por Script Properties y registro de cada modificación para
  revisión.
- **Privacidad por diseño**: API key fuera del código fuente y minimización de
  datos (estructura, estadísticas y patrones en lugar de datos personales).

Trabajo real en producción: la IA actúa como **asistencia técnica de validación
y calidad de datos**, no como autoridad clínica ni sustitución de criterio
profesional. Detalle técnico de esta integración en
[`docs/INFORME_IA_GEMINI.md`](https://github.com/2674321/Sistema-Gestion-Sectores-ECICEP/blob/master/docs/INFORME_IA_GEMINI.md).

## Visión

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/2674321/cesfam-san-juan-padds">
<img src="screenshots/padi-dashboard-01.png" width="100%" alt="PADI — Seguimiento Clínico"/>
</a>
<br><sub>PADI · Seguimiento Clínico</sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/2674321/carro-de-paro">
<img src="screenshots/carro-informe-mensual.png" width="100%" alt="Carro de Paro — Control de Inventario"/>
</a>
<br><sub>Carro de Paro · Inventario</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://github.com/2674321/sistema-de-guardias">
<img src="screenshots/guardias-calendario-bimestral-pc.png" width="100%" alt="Guardias — Calendarización"/>
</a>
<br><sub>Guardias · Calendarización</sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/2674321/sistema-cotizaciones">
<img src="screenshots/cotizaciones-demo-01.png" width="100%" alt="Cotizaciones — Generador PDF"/>
</a>
<br><sub>Cotizaciones · PDF</sub>
</td>
</tr>
</table>

## Proyectos

Catálogo maestro del ecosistema (`01–15`). Detalle por proyecto en
[`PROJECT_CATALOG.md`](PROJECT_CATALOG.md).

| Nº | Proyecto | Repositorio | Inicio | Tipo | Estado |
|---:|----------|-------------|--------|------|--------|
| 01 | Seguimiento Clínico PADI | [cesfam-san-juan-padds](https://github.com/2674321/cesfam-san-juan-padds) | 2026-08-13 | Git | En uso |
| 02 | Base de Datos · Defensa Civil | [base-datos-defensa-civil](https://github.com/2674321/base-datos-defensa-civil) | 2026-08-18 | Git | En desarrollo |
| 03 | Asistencia Digital · Bomberos | [asistencia-digital-bomberos](https://github.com/2674321/asistencia-digital-bomberos) | 2026-08-19 | Git | Deprecado |
| 04 | Control · Carro de Paro | [carro-de-paro](https://github.com/2674321/carro-de-paro) | 2026-08-19 | Git | En uso |
| 05 | Guía de Radiocomunicaciones | [guia-radiocomunicaciones-ca2opx](https://github.com/2674321/guia-radiocomunicaciones-ca2opx) | 2026-08-20 | Git | Activo |
| 06 | Perfil de GitHub | [2674321 (este perfil)](https://github.com/2674321/2674321) | 2026-08-20 | Perfil | Activo |
| 07 | Seguimiento de Baterías | [seguimiento-baterias-pernostock-ltda](https://github.com/2674321/seguimiento-baterias-pernostock-ltda) | 2026-08-20 | Git | Histórico |
| 08 | Aurea Salud · web | [pagina-web-aurea-salud](https://github.com/2674321/pagina-web-aurea-salud) | 2026-08-20 | Git | Experimental |
| 09 | Sistema de Cotizaciones | [sistema-cotizaciones](https://github.com/2674321/sistema-cotizaciones) | 2026-08-21 | Git | En migración |
| 10 | Sistema ECICEP | [Sistema-Gestion-Sectores-ECICEP](https://github.com/2674321/Sistema-Gestion-Sectores-ECICEP) | 2026-08-21 | Git | Activo |
| 11 | Sistema de Guardias | [sistema-de-guardias](https://github.com/2674321/sistema-de-guardias) | 2026-08-24 | Git | En uso |
| 12 | VantOPS | [vantops-chile](https://github.com/2674321/vantops-chile) | 2026-08-26 | Git | En desarrollo |
| 13 | Repository Health Auditor | [github-repository-auditor](https://github.com/2674321/github-repository-auditor) | 2026-08-27 | Git | Estable |
| 14 | Generador de Etiquetas | [generador-etiquetas-pernostock](https://github.com/2674321/generador-etiquetas-pernostock) | 2026-08-31 | Git | Activo |
| 15 | Seguimiento de Baterías (DEV) | *Solo local* | 2026-08-31 | DEV | DEV local |

**Tipo**: `Git` = repositorio público · `Perfil` = este repositorio · `DEV` = solo local (sin publicar).

## Relaciones entre proyectos

### 07 → 15 · Seguimiento de Baterías

El proyecto **15** es una derivación **DEV local independiente** de la línea
histórica del proyecto **07**. Es un entorno de trabajo local sin repositorio
público; **no** es un segundo repositorio de GitHub.

## Convención

> Los números son identificadores históricos estables utilizados para organizar
> el ecosistema local de proyectos de `2674321`. No forman parte del nombre de
> los repositorios de GitHub y no se renumeran cuando se incorporan nuevos proyectos.

- El orden numérico no representa necesariamente la fecha absoluta de creación de cada proyecto.
- Los proyectos nuevos reciben el siguiente número disponible (el próximo es el **16**).
- Los números retirados no se reciclan.

## 📮 Contacto

- 📻 **CA2OPX** · Coquimbo
- 🎓 ORCID: [0009-0002-1087-9445](https://orcid.org/0009-0002-1087-9445)
- 🇨🇱 Chile