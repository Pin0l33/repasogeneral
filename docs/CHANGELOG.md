# CHANGELOG

Registro de cambios del repositorio `repasogeneral` (Actividad 6, LPR 5° 3° A-B).
Formato basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y versionado [SemVer](https://semver.org/lang/es/).

## [1.0.0] - 2026-09-30 — Baseline Aprobado

### Agregado
- `src/main.cpp`: suite con los tres retos del taller (suma recursiva, búsqueda secuencial e intercambio con punteros).
- Verificación de celdas contiguas en el Reto 2: impresión de `&vectorDatos[i]` y distancia en bytes entre elementos consecutivos.
- `README.md` con integrantes, menú de retos y comandos de compilación.
- `.gitignore` (excluye `.exe`, `.vscode/` y `*.out`) y `LICENSE` (MIT, uso escolar).
- `docs/InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf`: informe en formato APA v7 con el cuestionario técnico de control.
- Configuración Dual-Remote: `git push` sube a GitHub (principal) y a GitLab (respaldo).

### Verificado
- Compilación sin errores ni advertencias con `g++ -Wall -Wextra`.
- Salida de los tres retos comprobada: suma 1..5 = 15, valor 18 hallado en el índice [6] e intercambio X=500 / Y=100.
