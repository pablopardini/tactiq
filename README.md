# TACTIQ — Plataforma de Videoanálisis Táctico Deportivo

Aplicación web de videoanálisis táctico y planificación deportiva para hockey, fútbol y básquet.

## Archivos

| Archivo | Descripción |
|---|---|
| `Tactiq.html` | Aplicación principal (analista/admin) |
| `landing.html` | Landing page pública |
| `manifest.json` | PWA manifest |
| `sw.js` | Service Worker para PWA |
| `logo.svg` | Logo vectorial Tactiq |

## Deploy

Hospedado en Netlify: https://tactiq-analisis.netlify.app

## Firebase

- Proyecto: `tactiq-18453`
- Base de datos: `https://tactiq-18453-default-rtdb.firebaseio.com`

## Credenciales por defecto

- Admin: `admin / admin123`
- Clave maestra: `tactiq2026`

## Funcionalidades principales

- Registro de eventos tácticos con timestamp y coordenadas exactas
- Análisis contextual del marcador (ganando/empatando/perdiendo)
- Secuencias de juego
- Análisis de bochas paradas (CC, Jugadas de 25)
- Etiquetas personalizadas
- Heatmap de calor por punto exacto
- Informe PDF profesional con análisis por cuartos
- Módulo de planificación (sesiones, temporada, biblioteca)
- Objetivos de temporada con seguimiento de progreso
- Sesiones similares con sugerencias automáticas
- Sistema multi-usuario por club
- Sincronización Firebase en tiempo real
- PWA instalable
