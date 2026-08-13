# Mapa Rehab Kine Piso Pélvico

Mapa territorial de demanda — Lista de espera de Rehabilitación Kinésica de Piso Pélvico,
Servicio de Salud del Reloncaví.

## Archivos
- `mapa_rehab_pp.html` — el mapa (abrir vía Netlify, no funciona con doble clic local)
- `loslagos.geojson` — polígonos de las 30 comunas de la Región de Los Lagos

## Actualizar datos
Reemplazar el bloque `REAL_DATA_HISTORY` dentro de `mapa_rehab_pp.html` con la
exportación nueva desde Excel (hoja "Agregado_Comuna_Especialidad_V2" + tablas de
VALIDACIONES). Subir el archivo actualizado a este repositorio — Netlify republica solo.

**Nota de privacidad:** este repositorio no debe contener nunca el Excel completo
(RUT, nombre, diagnóstico). Solo datos agregados por comuna.
