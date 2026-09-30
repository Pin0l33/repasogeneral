# repasogeneral

**Actividad 6 — Taller práctico de repaso y consolidación en C++**
Laboratorio de Programación (LPR) — 5° 3° A-B — 1° Cuatrimestre 2026
E.E.S.T. N° 20 Eduardo Ader — Vicente López

## Integrantes

| Integrante |
|---|---|
| Lucas Del Pino |

## Menú de retos

| Reto | Tema | Concepto clave |
|---|---|---|
| 1 | Suma recursiva | Pila de llamadas (stack) y caso base |
| 2 | Búsqueda secuencial | Arreglo contiguo, `break` y direcciones con `&` |
| 3 | Intercambio con punteros | Pasaje por dirección, desreferenciación y variable temporal |

## Estructura del repositorio

```
repasogeneral/
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   ├── CHANGELOG.md
│   └── InformeEEST1_LPR2026_ACT06_G03_Informe_v1.0.0.pdf
├── src/
│   └── main.cpp
└── capturas/
    ├── ejecucion_repasogeneral.png
    └── traza_memoria.png
```

## Compilar y ejecutar (PowerShell en VS Code)

```powershell
# 1. Compilar
g++ src/main.cpp -o src/repasogeneral.exe

# 2. Ejecutar
.\src\repasogeneral.exe
```

Si el equipo de la escuela no permite compilar, usar OnlineGDB con el contenido de `src/main.cpp` y adjuntar la captura en `capturas/`.

## Dual-Remote (GitHub + GitLab)

```powershell
git remote set-url origin https://github.com/tu-usuario/repasogeneral.git
git remote set-url --add --push origin https://github.com/tu-usuario/repasogeneral.git
git remote set-url --add --push origin https://gitlab.com/tu-usuario/repasogeneral.git
git remote -v
```

## Licencia

MIT — uso escolar. Ver [LICENSE](LICENSE).
