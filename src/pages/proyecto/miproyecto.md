---
layout: "../../layouts/Layout.astro"
title: "Juego de atrapar al la mosca" 
description: "un juego de intentar atrapar a la mosca"
---
# Atrapa a la mosca

Este proyecto implementa un sencillo juego interactivo donde puedes atrapar a la mosca haciendo clic en las celdas de una tabla generada dinámicamente.

## Características

- **Generación dinámica de tablas**: Permite personalizar el número de filas, columnas y el tamaño de las celdas.
- **Movimiento aleatorio de la mosca**: La mosca cambia de posición de manera dinámica en el tablero.
- **Interacción sencilla**: Incluye eventos como `onclick` para intentar atrapar la mosca.

## Cómo funciona

1. **Establecer parámetros iniciales**:
   - Filas: Número de filas en la tabla.
   - Columnas: Número de columnas en la tabla.
   - Tamaño de celda: Dimensión en píxeles de cada celda.

2. **Interacción**:
   - Haz clic en cualquier celda para intentar atrapar la mosca.
   - La mosca se moverá a una celda aleatoria después de cada intento.
