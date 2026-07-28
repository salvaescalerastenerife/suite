# Plan de implantación segura

1. **Laboratorio aislado**: repositorio y proyecto Supabase nuevos. Las tres apps actuales siguen intactas.
2. **Modelo común**: instalación como ficha central; trabajos, partes, fotos e historial relacionados con ella.
3. **Compatibilidad visual**: conservar nombres, orden de campos y flujo de cada app actual.
4. **Migración de prueba**: cargar una copia de datos, nunca los originales vivos.
5. **Piloto**: Oliver y un técnico, con un conjunto pequeño de trabajos reales duplicados para comprobación.
6. **Trabajo paralelo**: comparar resultados durante varios días.
7. **Cambio definitivo**: solo después de pasar pruebas, restauración de copia y validación de usuarios.

## Reglas no negociables
- Las coordenadas KML y las corregidas manualmente permanecen bloqueadas.
- Cada cambio queda auditado.
- Un parte sin conexión muestra claramente “pendiente de sincronizar”.
- Nunca se borra de forma irreversible desde la interfaz normal.
- La app antigua permanece disponible durante el piloto.
