# 🚛 RutaPro — Plataforma CAP & Permiso C

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222?style=for-the-badge&logo=github)](https://copycap666.github.io/rutapro-cap-permiso-c/)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=for-the-badge)](LICENSE.md)
[![HTML5](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)]()

> **Plataforma interactiva de estudio para el CAP de Mercancías y Permiso C con repetición espaciada, gamificación y recursos de élite.**

🔗 **Link en vivo:** [https://copycap666.github.io/rutapro-cap-permiso-c/](https://copycap666.github.io/rutapro-cap-permiso-c/)

---

## 📋 Descripción

**RutaPro** es una aplicación web monolito (un solo archivo `index.html`) diseñada para preparar el examen del **Certificado de Aptitud Profesional (CAP) de Mercancías** y el **Permiso de conducción C/C1/C+E**. 

Toda la base de conocimiento está extraída de fuentes oficiales:
- 📕 **Manual III — Reglamentación sobre Vehículos Pesados (RVP 2024)** · DGT
- 📘 **TMVI03** — Formación Integral para Conductores Profesionales de Mercancías
- 📗 **TMVI21** — Cualificación Inicial Ordinaria CAP Mercancías (Marzo 2022)

---

## ⚡ Funcionalidades

| Pilar | Descripción |
|-------|-------------|
| 🧠 **Repetición Espaciada (SRS)** | Las preguntas falladas aparecen con más frecuencia. El algoritmo pondera tasa de error × días sin ver la pregunta. |
| 🏆 **Gamificación Dinámica** | 7 rangos (Novato → Rey del Asfalto 👑), sistema XP, racha de estudio diaria. |
| ⚠️ **Zona de Peligro** | Filtro especial con 16 preguntas críticas: Tacógrafo, Tiempos de Conducción, Masas y Dimensiones. |
| 💾 **Soberanía de Datos** | Exportar/Importar progreso en JSON. Tus datos son tuyos, siempre. |
| 🌐 **Recursos de Élite** | Enlaces verificados al Simulador MITMA, TodoTest, ExamenCAP, PracticaTest y DrivenYou. |
| 📊 **Dashboard con Chart.js** | Gráficos de rendimiento por categoría y desglose porcentual por tema. |

---

## 🚀 Cómo Usarlo

### Opción 1: GitHub Pages (recomendado)

1. **Haz Fork** de este repositorio o clónalo:
   ```bash
   git clone https://github.com/COPYCAP666/rutapro-cap-permiso-c.git
   ```
2. Sube el repositorio a tu cuenta de GitHub.
3. Ve a **Settings → Pages → Source** y selecciona la rama `main` y la carpeta `/ (root)`.
4. GitHub publicará tu sitio en `https://TU-USUARIO.github.io/rutapro-cap-permiso-c/`

### Opción 2: Abrir en local

Simplemente abre el archivo `index.html` en cualquier navegador moderno. **No requiere servidor, ni npm, ni build.**

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Opción 3: Cualquier hosting estático

Sube el archivo `index.html` a Netlify, Vercel, Cloudflare Pages, o cualquier hosting de archivos estáticos. Funciona sin configuración.

---

## 🎮 Modos de Estudio

| Modo | Preguntas | Descripción |
|------|-----------|-------------|
| **Test** | 20 aleatorias (SRS) | Simula un examen con selección ponderada por errores |
| **Repaso** | Solo fallos | Prioriza las preguntas que más has fallado |
| **Zona de Peligro** | 16 críticas | Tacógrafo · Tiempos de Conducción · Masas y Dimensiones |
| **Biblioteca** | — | Fichas de conceptos clave organizadas por tema |
| **Recursos de Élite** | — | Enlaces a simuladores oficiales y plataformas externas |

---

## 🏅 Sistema de Rangos

| Rango | XP Necesarios | Emoji |
|-------|---------------|-------|
| Novato | 0 | 🔰 |
| Aprendiz | 100 | 🚛 |
| Conductor | 300 | 🛣️ |
| Profesional | 600 | ⭐ |
| Veterano | 1.000 | 🏅 |
| Experto | 1.500 | 🎖️ |
| Rey del Asfalto | 2.500 | 👑 |

**XP:** +10 por acierto · +2 por fallo (por intentarlo) · +25 por completar un test.

---

## 💾 Exportar / Importar Progreso

Tu progreso se guarda en `localStorage`. Para no perderlo al cambiar de navegador:

1. Ve a la pestaña **Stats**
2. Pulsa **Exportar JSON** → se descarga un archivo `.json`
3. En el nuevo navegador, pulsa **Importar JSON** → selecciona el archivo

---

## 🛠 Stack Tecnológico

Todo en un solo archivo `index.html`, sin dependencias locales:

- **React 18** + **Babel** (CDN) — Componentes reactivos
- **Tailwind CSS** (CDN) — Diseño premium responsive
- **Chart.js 4** (CDN) — Gráficos de estadísticas
- **SVG Icons** (inline) — Iconos tipo Lucide sin dependencias externas
- **localStorage** — Persistencia de datos SRS y progreso

---

## 🏷 Tags

`cap-mercancias` · `permiso-c` · `permiso-c1` · `dgt` · `examen-camion` · `conduccion-profesional` · `repeticion-espaciada` · `srs` · `estudio-interactivo` · `transportes` · `tmvi03` · `tmvi21` · `rvp-2024` · `tacografo` · `tiempos-conduccion` · `github-pages` · `single-file` · `react` · `copycap666`

---

## 📄 Fuentes Oficiales Utilizadas

- Manual III RVP 2024 — Dirección General de Tráfico (DGT)
- Programa Formativo TMVI03 — SEPE / Ministerio de Trabajo (Mayo 2019)
- Programa Formativo TMVI21 — SEPE / Sistema Nacional de Empleo (Marzo 2022)
- Reglamento General de Vehículos — Anexo IX (Masas y Dimensiones)
- Reglamento (CE) 561/2006 — Tiempos de conducción y descanso
- Reglamento (UE) 165/2014 — Tacógrafo digital
- Real Decreto 284/2021 — Cualificación inicial y formación continua CAP

---

## 📜 Licencia

**© 2026 COPYCAP666 · Todos los derechos reservados.**

Este proyecto está protegido bajo copyright. No se permite copiar, modificar, distribuir ni utilizar con fines comerciales sin autorización expresa por escrito del autor. Consulta el archivo [LICENSE.md](LICENSE.md) para los términos completos.

---

<p align="center">
  <a href="https://github.com/COPYCAP666">COPYCAP666</a><br/>
  <em>RutaPro — Estudia, aprueba, conduce.</em>
</p>
