## Evidencias documentales y planificación inicial

- Se recibieron cinco historias US-GIS-01 a US-GIS-05, un backlog inicial y un backlog complementario de cuatro sprints.
- S08 registra 17 tareas y 116 horas estimadas, todas No Iniciada. S27 registra 18 tareas y 104 horas, todas Por iniciar. Son registros de planificación suministrados.
- S28 y S26 declaran que G9 se elaboró a partir de la ficha, historias y backlog de Panamá; se incorpora como complemento de la misma iniciativa.

Historias originales: US-GIS-01 preparación de datos; US-GIS-02 procesamiento satelital; US-GIS-03 identificación de candidatos; US-GIS-04 validación; US-GIS-05 publicación. Los enunciados completos, prerrequisitos, dependencias, DoD y campos de validación se conservan en S03–S07.

Los dos backlogs expresan planes distintos. Conservar ambos como antecedentes y seleccionar con el equipo qué tareas se importan. No sumar automáticamente 116 y 104 horas ni importar dos veces una actividad equivalente.

### Tareas originales de S08

Fuente: `S08`. La clave de importación es propuesta; conserva la fila de origen. Prefijarla con `pa-panama-oeste:` al crear Issues. No sustituir por identificadores numéricos de GitHub hasta crearlas. Las horas vacías quedan sin estimar.

| Clave de importación | ID original | HU | Tarea | Prioridad | Rol | Horas estimadas | Estado declarado | Criterio original |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S08-r13 | TS-101.1 | US-GIS-01 | Investigar y filtrar imágenes Sentinel-2 con nubosidad igual o inferior al 20%, verificando fecha de adquisición, cobertura espacial y disponibilidad de las bandas requeridas. | Should | Líder Técnico SIG | 4 | No Iniciada | Se dispone de un inventario de imágenes Sentinel-2 seleccionadas que cumplen el umbral de nubosidad establecido, con fechas, cobertura y bandas identificadas. |
| S08-r14 | TS-101.2 | US-GIS-01 | Crear una tabla espacial en ArcGIS Pro con información por distrito de Panamá Oeste, verificando la correspondencia entre los registros y su ubicación geográfica. | Must | Líder Técnico SIG | 4 | No Iniciada | La tabla espacial está creada en ArcGIS Pro, contiene los campos requeridos y permite relacionar correctamente los registros con los distritos correspondientes. |
| S08-r15 | TS-101.3 | US-GIS-01 | Recopilar, organizar y revisar las capas de límites administrativos y otras capas territoriales de referencia correspondientes al área de estudio. | Must | No indicado | 4 | No Iniciada | Las capas territoriales están recopiladas, identificadas por fuente y fecha, verificadas espacialmente y organizadas en un sistema de coordenadas compatible con el proyecto. |
| S08-r16 | TS-102.1 | US-GIS-02 | Recortar y preparar las imágenes Sentinel-2, verificando la compatibilidad y resolución de las bandas. | Must | Líder Técnico SIG | 4 | No Iniciada | Imágenes recortadas, bandas identificadas y datos listos para procesamiento. |
| S08-r17 | TS-102.2 | US-GIS-02 | Generar composiciones en color natural y para análisis urbano. | Must | Líder Técnico SIG | 4 | No Iniciada | Composiciones generadas, exportadas y visualizadas correctamente en el SIG. |
| S08-r18 | TS-102.3 | US-GIS-02 | Desarrollar el cálculo de NDVI y NDBI y revisar la interpretación de los resultados. | Must | Líder Técnico SIG | 12 | No Iniciada | Ambos índices calculados, visualizados e interpretados; fórmulas, bandas y limitaciones documentadas. |
| S08-r19 | TS-103.1 | US-GIS-03 | Definir criterios preliminares de identificación mediante índices, imágenes y referencias territoriales. | Must | Líder Técnico SIG | 4 | No Iniciada | Criterios documentados y justificados para el área piloto. |
| S08-r20 | TS-103.2 | US-GIS-03 | Identificar y delimitar áreas candidatas mediante interpretación visual y análisis espacial, generando una capa de polígonos. | Must | Líder Técnico SIG | 12 | No Iniciada | Áreas candidatas delimitadas en polígonos con geometrías válidas y atributos básicos. |
| S08-r21 | TS-103.3 | US-GIS-03 | Contrastar las áreas candidatas con asentamientos conocidos y referencias territoriales disponibles. | Should | Líder Técnico SIG | 4 | No Iniciada | Coincidencias y diferencias registradas, sin asumir que las áreas identificadas son asentamientos informales. |
| S08-r22 | TS-104.1 | US-GIS-04 | Seleccionar una muestra de áreas candidatas y recopilar imágenes de mayor resolución y referencias institucionales. | Must | Líder Técnico SIG | 8 | No Iniciada | Muestra definida y fuentes de referencia identificadas y organizadas. |
| S08-r23 | TS-104.2 | US-GIS-04 | Comparar las áreas identificadas con las referencias disponibles y registrar coincidencias, errores y casos dudosos. | Must | Líder Técnico SIG | 8 | No Iniciada | Registro de validación con coincidencias, discrepancias y casos pendientes. |
| S08-r24 | TS-104.3 | US-GIS-04 | Ajustar los criterios de detección, actualizar las áreas candidatas y elaborar el mapa revisado y el listado de áreas para inspección adicional. | Must | Líder Técnico SIG | 10 | No Iniciada | Criterios revisados, polígonos actualizados, mapa final de validación y listado de áreas pendientes de inspección. |
| S08-r25 | TS-105.1 | US-GIS-05 | Organizar y exportar las capas finales para ArcGIS Pro y elaborar la cartografía temática. | Should | Líder Técnico SIG | 8 | No Iniciada | Capas exportadas con atributos y proyección consistentes; mapa con título, leyenda, escala y fuentes. |
| S08-r26 | TS-105.2 | US-GIS-05 | Documentar el procedimiento, las fuentes, los criterios de detección y las limitaciones del análisis. | Must | Líder Técnico SIG | 4 | No Iniciada | Documento técnico reproducible que describe el flujo de trabajo y las limitaciones. |
| S08-r27 | TS-105.3 | US-GIS-05 | Preparar la presentación técnica y las recomendaciones para ampliar el proyecto a otros distritos. | Should | Líder Técnico SIG | 4 | No Iniciada | Presentación que explica metodología, resultados, limitaciones y posibles pasos siguientes. |
| S08-r29 | TS-104.2 | US-GIS-04 | Desarrollo de interfaz en OpenLayers/Leaflet con filtros temporales | Must | Dev Frontend GIS | 16 | No Iniciada | Visor interactivo con control de capas, zoom y búsqueda funcional. |
| S08-r30 | TS-105.1 | US-GIS-05 | Documentación de flujo ETL de actualización y guía de metadatos | Should | Líder Técnico SIG | 6 | No Iniciada | Guía técnica y script de automatización en repositorio Git. |

### Tareas originales de S27

Fuente: `S27`. La clave de importación es propuesta; conserva la fila de origen. Prefijarla con `pa-panama-oeste:` al crear Issues. No sustituir por identificadores numéricos de GitHub hasta crearlas. Las horas vacías quedan sin estimar.

| Clave de importación | ID original | HU | Tarea | Prioridad | Rol | Horas estimadas | Estado declarado | Criterio original |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S27-r4 | TS-101.1 | US-GIS-01 | Validar geometrías de los tres KML/KMZ y documentar CRS | Must | Analista SIG | 4 | Por iniciar | 3/3 geometrías válidas; metadatos y CRS documentados |
| S27-r5 | TS-101.2 | US-GIS-01 | Cargar los tres polígonos como assets en GEE | Must | Líder Técnico SIG | 3 | Por iniciar | Assets accesibles y coincidentes con KML originales |
| S27-r6 | TS-101.3 | US-GIS-01 | Inventariar Sentinel-2, Sentinel-1, catastro, PLOT y capas auxiliares | Must | Analista de datos | 6 | Por iniciar | Matriz de datos con fuente, fechas, resolución, licencia y brechas |
| S27-r7 | TS-101.4 | US-GIS-01 | Definir periodos estacionales comparables 2016/2021/2024/2026 | Must | Especialista teledetección | 4 | Por iniciar | Ventana temporal y justificación documentadas |
| S27-r8 | TS-102.1 | US-GIS-02 | Filtrar y enmascarar Sentinel-2 con SCL | Must | Especialista teledetección | 6 | Por iniciar | Compuestos por área/periodo y conteo de escenas |
| S27-r9 | TS-102.2 | US-GIS-02 | Generar RGB y falso color para cada periodo | Must | Analista SIG | 4 | Por iniciar | RGB y falso color exportados y revisados |
| S27-r10 | TS-102.3 | US-GIS-02 | Calcular NDVI y NDBI respetando resolución nativa | Must | Especialista teledetección | 6 | Por iniciar | Índices documentados; NDBI interpretado a 20 m |
| S27-r11 | TS-102.4 | US-GIS-02 | Procesar Sentinel-1 VV/VH para periodos comparables | Should | Especialista radar | 8 | Por iniciar | Composites SAR con órbita y polarización consistentes |
| S27-r12 | TS-103.1 | US-GIS-03 | Calcular diferencias NDVI/NDBI/SAR entre periodos | Must | Especialista teledetección | 6 | Por iniciar | Raster de cambio por polígono y periodo |
| S27-r13 | TS-103.2 | US-GIS-03 | Definir y calibrar regla de candidatos con muestras | Must | Líder Técnico SIG | 8 | Por iniciar | Umbrales sustentados por muestras; limitaciones registradas |
| S27-r14 | TS-103.3 | US-GIS-03 | Generar polígonos candidatos y atributos | Must | Analista SIG | 6 | Por iniciar | GeoJSON/GeoPackage con geometrías válidas y área |
| S27-r15 | TS-103.4 | US-GIS-03 | Crear huella de calor de concentración de cambios | Should | Analista SIG | 4 | Por iniciar | Mapa de intensidad relativa, claramente no térmica |
| S27-r16 | TS-104.1 | US-GIS-04 | Seleccionar muestra estratificada de candidatos/no candidatos | Must | QA geoespacial | 5 | Por iniciar | Muestra representativa y trazable |
| S27-r17 | TS-104.2 | US-GIS-04 | Contrastar con ortofotos, catastro y campo | Must | Equipo institucional | 10 | Por iniciar | Registro de VP/FP/FN/VN y evidencias |
| S27-r18 | TS-104.3 | US-GIS-04 | Calcular precisión, exhaustividad y F1; ajustar umbrales | Must | QA geoespacial | 6 | Por iniciar | Métricas calculadas y limitaciones explicadas |
| S27-r19 | TS-105.1 | US-GIS-05 | Preparar mapas, GeoTIFF, GeoJSON y proyecto QGIS | Must | Analista SIG | 6 | Por iniciar | Capas, simbología, metadatos y mapas listos |
| S27-r20 | TS-105.2 | US-GIS-05 | Documentar pipeline, fuentes, parámetros y riesgos | Must | Líder Técnico SIG | 4 | Por iniciar | Manual reproducible y scripts versionados |
| S27-r21 | TS-105.3 | US-GIS-05 | Preparar visor/demostración y presentación ejecutiva | Should | Desarrollador visor / SIG | 8 | Por iniciar | Visor demostrable y aprobación del Product Owner |

## Especificación de módulos de aplicación

Estos componentes constituyen una propuesta de interfaz basada en el perfil. La primera versión entrega una página de proyecto completa y espacios de integración. Activar un mapa, indicador, descarga o simulador únicamente cuando exista el dato o servicio correspondiente.

- Selector de las tres áreas piloto y de los periodos aprobados.
- Comparador temporal de RGB y capas NDVI/NDBI; leyendas con resolución y fecha.
- Lista o mapa de candidatos con estado de revisión y enlace a evidencia, cuando existan datos publicados.
- Panel de cobertura de datos: escenas, nubes y periodos sin información, diferenciados de valores cero.
- Descarga de productos autorizados y manual reproducible; los insumos catastrales permanecen en servicios institucionales.

### Estados vacíos y navegación

Cuando no haya resultado disponible, mostrar «Resultado pendiente» y explicar qué insumo falta. Conservar los datos faltantes como `null`; no dibujar geometrías inventadas, rellenar indicadores con cero ni presentar gráficos de ejemplo como mediciones. El botón de fork/clonación apunta al repositorio canónico verificado, no al repositorio general del portal.
