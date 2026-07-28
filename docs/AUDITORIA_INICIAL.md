# Auditoría inicial de las tres aplicaciones

## Mapa
- 2.012 registros incrustados.
- Coordenadas base y correcciones guardadas localmente.
- Orígenes de coordenadas diferenciados y protección lógica del KML.

## Técnicos
- IndexedDB `postventaDB`, almacén `partes`.
- Formularios separados de instalación, reparación y mantenimiento.
- Historial local y configuración de técnicos.

## Gestión
- IndexedDB `gp_oliver_db`.
- Almacenes `imports`, `interventions` y `meta`.
- Importación PDF/CSV, informes, exportaciones y copias.

## Riesgo principal
Los tres sistemas usan identificadores y estructuras distintas. No deben fusionarse copiando archivos. La integración correcta requiere una capa de migración y una ficha única de instalación.
