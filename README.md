# CLICK CASH - Versión modificada (1M por click)

Versión alterada del juego **CLICK CASH** para pruebas / auditoría de seguridad client-side.

## Cambios realizados

| Elemento              | Valor original     | Valor modificado      |
|-----------------------|--------------------|-----------------------|
| Puntos al iniciar     | 0                  | 0                     |
| Multiplicador         | 1                  | 1 (sin cambios)       |
| Costo de mejoras      | 1500               | 1500 (sin cambios)    |
| Puntos por click      | Según multiplicador| **+1.000.000 fijo**   |
| Sistema de ban        | Activo             | Desactivado           |
| Partidas antiguas     | Se cargan          | Se ignoran            |

## Cómo jugar

### Opción 1 - HTML directo
Abre el archivo `CLICK_CASH_1M_PER_CLICK.html` en tu navegador.

> En móviles puede fallar por el tamaño del archivo. Usa la opción 2.

### Opción 2 - Re-empaquetar (recomendado)
1. Entra a [https://packager.turbowarp.org/](https://packager.turbowarp.org/)
2. Sube el archivo `CLICK_CASH_1M_PER_CLICK.zip`
3. Pulsa **Package**
4. Descarga y abre el HTML generado

## Notas

- Esta versión usa claves de `localStorage` distintas, por lo que no carga partidas de la versión original.
- El progreso de esta versión sí se guarda normalmente.
- Es una modificación client-side. No afecta a ningún servidor de forma no autorizada más allá de lo que el cliente original ya permitía.

## Archivos incluidos

- `CLICK_CASH_1M_PER_CLICK.zip` → Proyecto TurboWarp modificado
- `CLICK_CASH_1M_PER_CLICK.html` → Versión ya empaquetada lista para abrir
- `README.md` → Este archivo
