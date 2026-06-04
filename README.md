# 🏆 Prode Mundial 2026

App interactiva para pronosticar los resultados del FIFA World Cup 2026.

## ✨ Features

- **Fase de grupos** — 72 partidos, todos los grupos A–L
- **Bracket / Eliminatorias** — Octavos, Cuartos, Semifinales, 3er Puesto y Final
- **Tabla de posiciones** — puntuación automática por resultados exactos (+5) o ganador correcto (+3)
- **Multiusuario** — Florencia, Leonardo, German, Silvia (configurable)
- **Persistencia local** — los datos se guardan en `localStorage`

## 🚀 Cómo usar

### Opción 1 — Abrir directo en el browser
Abrí `index.html` en cualquier navegador moderno. No requiere servidor ni instalación.

### Opción 2 — GitHub Pages
1. Subí este repositorio a GitHub
2. Andá a **Settings → Pages**
3. En *Source* seleccioná `main` branch y carpeta `/ (root)`
4. Guardá — en unos segundos tenés la URL pública 🎉

## 📁 Estructura

```
prode-mundial-2026/
└── index.html      # Todo en un solo archivo (HTML + CSS + JS)
```

## ✏️ Personalizar participantes

En `index.html`, buscá la línea:
```js
const USUARIOS = ['Florencia','Leonardo','German','Silvia'];
```
y reemplazá con los nombres que quieras.

## 🎯 Sistema de puntos

| Resultado | Puntos |
|-----------|--------|
| Resultado exacto (ej: 2-1 real, 2-1 pred) | +5 |
| Ganador/empate correcto (ej: 2-1 real, 1-0 pred) | +3 |
| Error total | +0 |

## 📝 Notas

- En eliminatorias: ingresá el marcador en 90 min. Si hay empate, seleccioná quién avanza en penales.
- Los resultados "reales" para calcular puntos se pueden ingresar bajo el usuario administrador en el código (clave `'real'` en el state).

---
Made with ❤️ para el Mundial 2026 🌎⚽
