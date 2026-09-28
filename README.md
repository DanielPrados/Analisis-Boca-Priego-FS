Análisis Boca Priego FS

Informes de Power BI para el análisis del Boca Priego FS y de su cantera.

## Informes disponibles

| Informe | Archivo | Descripción |
| --- | --- | --- |
| Análisis Boca | [`AnálisisBOCA.pbix`](https://github.com/DanielPrados/Analisis-Boca-Priego-FS/blob/main/An%C3%A1lisis/An%C3%A1lisisBOCA.pbix) | Informe principal del Boca Priego FS. |
| Análisis Boca Juvenil | [`Análisis Boca Juvenil.pbix`](https://github.com/DanielPrados/Analisis-Boca-Priego-FS/blob/main/An%C3%A1lisis/An%C3%A1lisis%20Boca%20Juvenil.pbix) | Informe dedicado al seguimiento del equipo juvenil. |

## Requisitos

- Power BI Desktop.
- Acceso a los archivos `.pbix` del repositorio.
- Las fuentes de datos originales, si el informe solicita actualizar o volver a cargar los datos.

## Cómo abrir los informes

1. Entra en la carpeta [`Análisis`](https://github.com/DanielPrados/Analisis-Boca-Priego-FS/tree/main/An%C3%A1lisis).
2. Descarga el informe que quieras consultar.
3. Ábrelo con Power BI Desktop.
4. Si Power BI solicita credenciales o rutas de origen, utiliza la configuración de las fuentes originales.

Los archivos `.pbix` son binarios. GitHub permite almacenarlos y descargarlos, pero no muestra sus páginas, visualizaciones ni filtros dentro del navegador.

## Estructura del repositorio

```text
.
├── Análisis/
│   ├── AnálisisBOCA.pbix
│   └── Análisis Boca Juvenil.pbix
└── README.md
```

## Capturas de los informes

Las capturas de las páginas de Power BI deben tomarse desde Power BI Desktop, porque GitHub no puede representar visualmente el contenido de un archivo `.pbix`.

Se recomienda añadirlas en una carpeta `docs/capturas/` con esta estructura:

```text
docs/
└── capturas/
    ├── analisis-boca-resumen.png
    ├── analisis-boca-rendimiento.png
    ├── analisis-boca-juvenil-resumen.png
    └── analisis-boca-juvenil-rendimiento.png
```

Cuando estén disponibles, pueden insertarse aquí con Markdown:

```md
![Resumen del análisis Boca](docs/capturas/analisis-boca-resumen.png)
![Rendimiento del análisis Boca](docs/capturas/analisis-boca-rendimiento.png)
![Resumen del análisis Boca Juvenil](docs/capturas/analisis-boca-juvenil-resumen.png)
![Rendimiento del análisis Boca Juvenil](docs/capturas/analisis-boca-juvenil-rendimiento.png)
```

## Repositorio

[DanielPrados/Analisis-Boca-Priego-FS](https://github.com/DanielPrados/Analisis-Boca-Priego-FS)
