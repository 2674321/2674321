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

### En uso 🟢

| Proyecto | Descripción |
|----------|-------------|
| **[Sistema · Gestión de Guardias](https://github.com/2674321/sistema-de-guardias)** | Calendarización y gestión de guardias para la 1ª Compañía de Bomberos del CBC (Coquimbo): niveles Inicial/Operativo/Profesional con cupos por día, asistencia, baja protegida con código enviado al correo y panel de administración integrado sobre Google Sheets. |
| **[Sistema · Cotizaciones PDF](https://github.com/2674321/sistema-cotizaciones)** | Generador personal de cotizaciones profesionales para servicios tecnológicos: JSON → plantilla HTML → PDF con WeasyPrint, QR de verificación + hash SHA-256 anti-alteraciones, desglose justificado de la inversión y numeración automática. |
| **[Sistema · Seguimiento Clínico PADI](https://github.com/2674321/cesfam-san-juan-padds)** | Sistema de seguimiento clínico desarrollado a solicitud del Servicio PADI (Coquimbo): registro de pacientes con dependencia, cuidador principal, controles y patologías crónicas, alertas de vigencia y agenda. |
| **[Sistema · Control de Carro de Paro](https://github.com/2674321/carro-de-paro)** | Revisión de inventario de carros de paro (urgencia ambulatoria y móviles): medicamentos e insumos, revisiones periódicas, stock y vencimientos. |
| **[Sistema ECICEP](https://github.com/2674321/sistema-gestion-sectores-ecicep)** | Sistema personal de registro y gestión clínica de pacientes: formulario web único de captura, identificación y deduplicación, modelo de estratificación por sectores (naranjo/amarillo/verde), panel de control, estadísticas REM (Excel/PDF), cola de calidad y backups — Google Sheets + Apps Script · **[IA](https://github.com/2674321/Sistema-Gestion-Sectores-ECICEP/blob/master/docs/INFORME_IA_GEMINI.md)**: integración de la API de Gemini con análisis y calidad de datos, validación local de duplicados e integridad, corrección asistida y auditoría trazable · 🧪 [demo del formulario](https://2674321.github.io/Sistema-Gestion-Sectores-ECICEP/) |
| **[Manual · Guía de Radiocomunicaciones](https://github.com/2674321/guia-radiocomunicaciones-ca2opx)** | Manual de campo imprimible (A4) con los códigos de radio usados en emergencias en Chile — Código Q (UIT), Claves R (CONAF) y alfabeto fonético OACI — en dos versiones: Claves 10 del Cuerpo de Bomberos de Coquimbo y Códigos 10 de Banda Ciudadana (CB). Incluye tarjetas con QR listas para imprimir · 🌐 [ver online](https://2674321.github.io/guia-radiocomunicaciones-ca2opx/) |

### En desarrollo 🚧

| Proyecto | Descripción |
|----------|-------------|
| **[Sistema · Base de Datos Defensa Civil](https://github.com/2674321/base-datos-defensa-civil)** | Sistema integral para la Defensa Civil de Chile, Sede La Serena: voluntarios con grados y especialidades, eventos, entregas de equipamiento e inventario, con dashboard y control de acceso. |

### Formación / Proyectos antiguos

| Proyecto | Descripción |
|----------|-------------|
| **[App offline · Asistencia Digital Bomberos](https://github.com/2674321/asistencia-digital-bomberos)** | Propuesta de digitalización del registro de asistencia de voluntarios de la 1ª Compañía de Bomberos de Coquimbo. Descontinuada: exige el formato institucional exacto, pendiente de replicar digitalmente · ▶️ [demo](https://2674321.github.io/asistencia-digital-bomberos/) |
| **[Programa escritorio · Seguimiento de Baterías](https://github.com/2674321/seguimiento-baterias-pernostock-ltda)** | Aplicación de escritorio en Ruby/GTK3 + SQLite desarrollada para Pernostock Ltda: registro, búsqueda, historial, estadísticas y copias de seguridad de baterías. |
| **[Página web · Aurea Salud](https://github.com/2674321/pagina-web-aurea-salud)** | Prototipo experimental de plataforma de salud/telemedicina: landing informativa, login simulado y panel administrativo estático. Incompleto por diseño; conservado como referencia de aprendizaje. |

## 📮 Contacto

- 📻 **CA2OPX** · Coquimbo
- 🎓 ORCID: [0009-0002-1087-9445](https://orcid.org/0009-0002-1087-9445)
- 🇨🇱 Chile
