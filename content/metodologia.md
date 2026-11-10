## Alcance técnico y metodológico declarado en el perfil

Los siguientes campos reproducen la información declarada por el equipo en el documento principal del perfil (identificado en el inventario documental como `S02`; consulta la lista completa de archivos al final de esta página). Representan la formulación técnica del perfil y se actualizan conforme avanza la validación del proyecto.

### Territorio y escala

**Ciudad, sector o territorio.** Caso de estudio Distritos de Arraiján y La Chorrera

**Escala principal de análisis.** Área metropolitana / conurbación

**Superficie aproximada.** 89.115 ha (≈ 891 km²), calculada a partir del polígono del formulario

**Centroide (lat, lon).** 8.94515, -79.75532

**¿Cuenta con archivos geoespaciales?.** Sí

**Archivo cargado.** No especificado

**Descripción de los archivos.** No especificado

### Instrumentos y productos

**Instrumento de planificación o gestión al que aportaría.** Plan de ordenamiento territorial / plan de desarrollo urbano

**Tipo de producto o entregable.** Mapa

Dashboard / tablero

**Descripción del producto.** Poder visualizar la ubicación de los asentamientos informales en Arraiján y La Chorrera a través de un tablero de control para la toma de decisiones.

**Avance mínimo esperado en la jornada presencial.** Flujo de identificación y delimitación automática de asentamientos informales.

### Datos

**Datos satelitales o productos geoespaciales útiles.** Sentinel-2 / óptico multiespectral

GHSL / huella urbana global

Huellas de edificaciones (Google/Microsoft Open Buildings)

OpenStreetMap (vías, edificaciones, equipamientos)

Datos de población y vivienda (censos, WorldPop)

**Datos locales, institucionales o de campo disponibles.** Contamos con información censal del 2023, propuesta de zonificación a través del PLOT de Arraiján-La Chorrera

**Datos que hacen falta.** Catastro

**Enlaces relacionados.** No especificado

### Método y herramientas

**Métodos o pasos previstos.** Selección de imágenes de Sentinel 2.

Calcular NDVI para la zona de estudio.

Calcular NDBI para la zona de estudio.

Identificación de posibles asentamientos informales. Con características simultáneamente

* Concentraciones de superficies construidas.

* Distribución irregular de las construcciones.

*  Poca vegetación entre las áreas construidas.

* Expansión reciente en los bordes urbanos.

**Flujo de trabajo preliminar.** Seleccionar imágenes+extracción de huella urbana+identificar áreas de crecimiento no planificadas, cruzar con información existente censal, generar capa, crear mapas, crear app web de visualización y consulta.

**Índices, algoritmos o herramientas.** Google Earth Engine + QGIS

### Operación y acompañamiento

**Frecuencia de actualización o análisis.** Anual

**Nivel(es) de acceso.** Uso institucional

**Componentes para usar o desplegar.** Google Earth Engine App

Dashboard / tablero

**Uso previsto por otras personas.** Técnicos y planificadores del MIVIOT y Municipios: Accederían diariamente o semanalmente a un Geoportal con alertas temáticas generadas por análisis satelital (detección de cambios). Usarían los mapas interactivos para evaluar solicitudes de zonificación, identificar nuevas construcciones en tiempo real y delimitar polígonos de intervención antes de aprobar planes de ordenamiento o proyectos de infraestructura.

**¿Requiere actualización periódica?.** No estoy seguro/a

**Actualización requerida.** No especificado

**Pregunta principal.** ¿Qué metodología (flujo de trabajo automático) podría implementarse para la detección y delimitación de posibles asentamientos informales y cómo extraer esos datos en formatos vectoriales?

**Áreas en las que necesita asesoría.** Metodología y análisis geoespacial

Validación de resultados

Producto esperado y visualización

Despliegue digital

## Referencias documentales del expediente

- `S01` — `0. Perfiles de Proyectos/Grupo 1_Panamá/2- Presentacion_soluciones_YC_AB.pptx`.

- `S02` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Ficha_01_Panama_Asentamientos_Arraijan_La_Chorrera.docx`.

- `S03` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Formato_hu_blanco_US-GIS-01.docx`.

- `S04` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Formato_hu_blanco_US-GIS-02.docx`.

- `S05` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Formato_hu_blanco_US-GIS-03.docx`.

- `S06` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Formato_hu_blanco_US-GIS-04.docx`.

- `S07` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Formato_hu_blanco_US-GIS-05.docx`.

- `S08` — `0. Perfiles de Proyectos/Grupo 1_Panamá/Sprint_Backlog_Marco_Scrum_ProyectoSIG_yc_ab.xlsx`.

- `S26` — `0. Perfiles de Proyectos/Grupo 9_Panamá/LEEME_PRIMERO.txt`.

- `S27` — `0. Perfiles de Proyectos/Grupo 9_Panamá/01_Documentos/Backlog_Scrum_Proyecto_Copernicus.xlsx`.

- `S28` — `0. Perfiles de Proyectos/Grupo 9_Panamá/01_Documentos/Ficha_Proyecto_Copernicus_Panama_Oeste.docx`.

- `S29` — `0. Perfiles de Proyectos/Grupo 9_Panamá/02_Codigos_Notepad/01_GEE_Procesamiento_Multitemporal.js`.

- `S30` — `0. Perfiles de Proyectos/Grupo 9_Panamá/02_Codigos_Notepad/02_Instalacion_y_ejecucion.txt`.

- `S31` — `0. Perfiles de Proyectos/Grupo 9_Panamá/02_Codigos_Notepad/03_Biblioteca_de_enlaces_y_comandos.txt`.

- `S32` — `0. Perfiles de Proyectos/Grupo 9_Panamá/02_Codigos_Notepad/04_QA_y_validacion.txt`.

- `S33` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Area de Proyecto 1.kml`.

- `S34` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Area de Proyecto 1.kmz`.

- `S35` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Crecimiento Informal.kml`.

- `S36` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Crecimiento Informal.kmz`.

- `S37` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Zona de Invasion .kml`.

- `S38` — `0. Perfiles de Proyectos/Grupo 9_Panamá/03_Datos_KML/Zona de Invasion .kmz`.

### Notas técnicas de implementación verificadas

El catálogo oficial sitúa el comienzo de `COPERNICUS/S2_SR_HARMONIZED` en 2017-03-28. El periodo 2016 de S29 debe revisarse antes de ejecutar; no basta ampliar la ventana dentro de 2016. Acordar otra línea base o una fuente compatible y documentar comparabilidad. Fuente: https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED .

La guía oficial de carga de tablas de Earth Engine admite Shapefile o CSV. Convertir los KML a un Shapefile con sus archivos auxiliares y verificar las geometrías antes de cargarlo. La instrucción original que sugiere KML directo se conserva únicamente como fuente. Fuente: https://developers.google.com/earth-engine/guides/table_upload .
