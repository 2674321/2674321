# Gobierno del portfolio · 2674321

Este documento define el estándar mínimo para los proyectos del ecosistema `2674321`.
No obliga a que todos los repositorios tengan la misma arquitectura: establece reglas comunes
de seguridad, trazabilidad y mantenimiento.

## 1. Clases de proyecto

| Clase | Uso | Regla principal |
|---|---|---|
| Producción / en uso | Sistemas usados por personas u organizaciones | cambios pequeños, revisables y con regresión |
| Desarrollo activo | Producto o sistema en construcción | issues/tareas, ramas y CI cuando sea viable |
| Estable / mantenimiento | Funcionalidad consolidada | evitar crecimiento innecesario; corregir y mantener |
| Histórico / deprecado | Conservación de portfolio | no modernizar por rutina; solo seguridad, documentación o roturas |
| Privado / cliente | Datos o lógica ligados a un cliente | repositorio privado y separación estricta de datos |

## 2. Política público / privado

Un repositorio puede ser público solo cuando su valor está en el **código y la documentación**,
no en datos operativos reales.

Deben permanecer fuera de repositorios públicos:

- bases, planillas, PDFs o exportaciones con información real;
- datos clínicos, personales, administrativos u operativos identificables;
- documentos internos institucionales;
- cotizaciones reales de clientes;
- credenciales, tokens, cookies, claves, secretos y archivos de servicio;
- configuraciones locales vinculadas a despliegues reales, como `.clasp.json` y `.clasprc.json`;
- respaldos y copias de trabajo.

Los ejemplos públicos deben usar datos sintéticos.

## 3. Flujo de cambios

Para cambios medianos o de riesgo:

```
necesidad → auditoría → rama → implementación → pruebas/CI → PR → revisión → merge
```

Los cambios pequeños puramente documentales pueden simplificarse, pero nunca deben saltarse
la revisión de datos sensibles.

## 4. Ramas

- Respetar la rama por defecto actual de cada proyecto.
- No migrar masivamente `master` a `main` sin revisar referencias, GitHub Pages, badges,
  enlaces raw, scripts y automatizaciones.
- Para trabajo nuevo usar nombres descriptivos, por ejemplo:
  `fix/...`, `feat/...`, `security/...`, `docs/...`, `refactor/...`.

## 5. Archivos mínimos según riesgo

### Repositorios públicos activos

Recomendados:

- `README.md`
- `LICENSE` cuando corresponda
- `.gitignore`
- `SECURITY.md`
- CI o validación automática cuando el stack lo permita
- documentación de instalación/operación si existe despliegue
- `CHANGELOG.md` para productos con releases

### Repositorios privados operativos

Además de lo anterior:

- política de respaldos;
- procedimiento de recuperación;
- separación de datos y código;
- datos reales fuera de fixtures y pruebas;
- trazabilidad de migraciones.

### Históricos

No se exige CI ni documentación extensa si no aportan valor. Deben conservar como mínimo una
descripción honesta del estado y no exponer secretos o datos reales.

## 6. Apps Script

En proyectos Google Apps Script:

- no versionar `.clasp.json` ni `.clasprc.json` del entorno real;
- versionar `appsscript.json` solo cuando forma parte de la aplicación;
- mantener IDs, hojas reales y datos operativos fuera del código siempre que sea posible;
- preferir configuración mediante PropertiesService o configuración local no versionada;
- demos y fixtures deben ser sintéticos.

## 7. Seguridad e historial Git

Borrar un archivo del último commit **no lo elimina del historial**.

Cuando se detecte una exposición:

1. retirar el archivo del árbol actual;
2. impedir su reingreso con `.gitignore` o validaciones;
3. evaluar si contiene datos que requieran purga histórica;
4. rotar credenciales si existieron secretos;
5. ejecutar la purga histórica de forma separada y verificable;
6. volver a comprobar clones, ramas y tags relevantes.

La reescritura de historial se considera una operación destructiva y debe planificarse aparte.

## 8. Numeración del ecosistema

- Los números locales son identificadores históricos estables.
- No se renumeran proyectos existentes.
- Los números retirados no se reciclan.
- El catálogo maestro vive en `PROJECT_CATALOG.md`.
- El siguiente identificador disponible, a fecha 2026-10-01, es **19**.

## 9. Prioridad técnica

Orden general de decisión:

**seguridad y privacidad → integridad de datos → pruebas/regresión → mantenibilidad → UX → nuevas funciones → estética.**

El branding común se considera una capa de presentación; no debe desplazar correcciones
funcionales o de seguridad.
