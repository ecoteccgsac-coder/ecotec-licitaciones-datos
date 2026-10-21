# Datos de ECOTEC-Licitaciones

Procesos de contratación pública del Perú de los últimos 90 días, normalizados y clasificados
por tipo de objeto y especialidad. Los usa el buscador [ecotec.pe/licitaciones](https://ecotec.pe/licitaciones).

- `meta.json`: fecha de actualización, totales y catálogos.
- `obras.json`, `consultoria-obras.json`, `consultoria.json`, `servicios.json`, `bienes.json`: un arreglo de procesos por tipo.

Se actualiza a diario desde Cajamarca con el script `sync_licitaciones.py` del sitio.

**Fuente:** Portal de Contrataciones Abiertas del OECE (estándar OCDS),
https://contratacionesabiertas.oece.gob.pe, publicado bajo licencia
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Estos datos derivados se
publican bajo la misma licencia. No es un portal oficial del Estado.

Mantenido por ECOTEC Consulting Group S.A.C. · https://ecotec.pe
