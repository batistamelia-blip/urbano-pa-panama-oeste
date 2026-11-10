# Revisión técnica obligatoria antes de ejecutar en Google Earth Engine

El archivo `01_GEE_Procesamiento_Multitemporal_suministrado.js` conserva como referencia el script entregado en el complemento documental de Panamá Oeste (Grupo 9). **No representa resultados ya ejecutados ni validados.**

## Ajustes requeridos antes de correr el flujo en la jornada

1. **Incompatibilidad temporal de `2016` con `COPERNICUS/S2_SR_HARMONIZED`:**
   - El catálogo oficial de Earth Engine inicia `COPERNICUS/S2_SR_HARMONIZED` el **28 de marzo de 2017**.
   - Por tanto, el filtro `'2016-01-01'` a `'2016-05-01'` devuelve una colección vacía y falla al calcular diferencias si no se corrige.
   - **Acción:** Acordar con MIVIOT usar una línea base a partir de `2017`/`2018` en `S2_SR_HARMONIZED`, o emplear explícitamente `COPERNICUS/S2_HARMONIZED` (TOA, disponible antes de 2017) documentando la diferencia radiométrica, además de validar `coleccion.size().gt(0)`.
2. **Carga de los tres polígonos piloto (conversión previa):**
   - La ingesta de tablas de GEE admite **Shapefile** o **CSV** (no subida directa de `.kml`). Convertir los polígonos piloto revisados a Shapefile (`EPSG:4326`), comprobar topología sin autointersecciones y reemplazar `users/USUARIO/...` por los IDs reales del asset.
3. **Resolución nativa y cautela semántica:**
   - El índice NDBI utiliza la banda SWIR `B11` (20 m); mantener interpretación y exportación a **20 m**.
   - Las detecciones son **áreas candidatas de cambio**, nunca certificación jurídica de invasión o informalidad.
