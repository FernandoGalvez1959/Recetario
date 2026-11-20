# Recetario

Recetario personal de Fer, organizado por apartados.

## Apartados

Air Fryer · Crockpot · Ensaladas · Hígado y limpieza · Helados y batidos ·
Tapas · Postres · Olla rápida · Olla ferroviaria

Se pueden reordenar, renombrar y crear apartados nuevos desde la propia app.
Dentro de cada uno se filtra por tipo de alimento y, donde tiene sentido, por
momento del día.

## Funciones

- Buscador por nombre o ingrediente
- Recetas propias, en uno o varios apartados
- Foto propia en cualquier receta, hecha con la cámara o de la galería
- Ajuste de grados y tiempos a la máquina de casa, por tandas
- Temporizador con aviso sonoro en cada tanda
- Favoritas
- Copia de seguridad en archivo, con las fotos dentro
- Funciona sin conexión y se puede instalar en el móvil
- Todo se guarda en el propio dispositivo

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La aplicación completa |
| `manifest.webmanifest` | Nombre, colores e icono al instalarla en el móvil |
| `sw.js` | Guarda la app para usarla sin conexión |
| `icono-192.png`, `icono-512.png` | Icono |

Las recetas propias, las favoritas, los ajustes y las fotos se guardan en el
propio móvil, no en GitHub. Descarga la copia de seguridad de vez en cuando.

## Actualizar la app

Sube el `index.html` nuevo y cambia el número de `VERSION` en `sw.js`.
La app detecta la versión nueva y se actualiza sola al abrirla con conexión.
