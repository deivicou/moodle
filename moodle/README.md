# Moodle Portátil 📦

Anotaciones y guía práctica para mantener un **Moodle local en un disco duro**, capaz de exportar/importar asignaturas y trasladarse entre diferentes centros educativos. El objetivo es disponer de una plataforma portátil que permita almacenar el contenido de las asignaturas de forma local y gestionarlo/importarlo donde sea necesario.

## Contenido

- [01 - Exportar e importar cursos entre Moodles](docs/01-exportar-importar-cursos.md)
- [02 - Repositorio de archivos vía sistema de archivos (FTP simulado)](docs/02-repositorio-sistema-archivos.md)
- [03 - Mover el directorio de instalación de Moodle](docs/03-mover-directorio-instalacion.md)
- [04 - Acceso, credenciales y notas varias](docs/04-acceso-y-credenciales.md)
- [05 - Versión online (hosting)](docs/05-version-online.md)

## Resumen rápido

| Concepto | Detalle |
|---|---|
| Versión Moodle IES Castelar | 4.1.4 |
| Versiones que funcionan en local (probadas) | 4.3.2+ |
| Versión online (probada) | 4.5.3+ |
| Compatibilidad | Importación de copias de seguridad de cursos individuales entre versiones |

> ⚠️ Sin rol de administrador en el Moodle original no es posible exportar una copia de seguridad completa del sitio; solo cursos individuales.

## Estructura del repositorio

```
moodle/
├── README.md
├── docs/
│   ├── 01-exportar-importar-cursos.md
│   ├── 02-repositorio-sistema-archivos.md
│   ├── 03-mover-directorio-instalacion.md
│   ├── 04-acceso-y-credenciales.md
│   └── 05-version-online.md
└── images/
    ├── 01-detalles-copia-seguridad.png
    ├── 02-config-copia-seguridad.png
    ├── 03-restaurar-curso-nuevo.png
    ├── 04-error-conexion.png
    ├── 05-version-moodle-local.png
    ├── 06-admin-sitio-restaurar.png
    ├── 07-selector-archivos.png
    ├── 08-config-repositorio.png
    └── 09-servicios-mysql.png
```
