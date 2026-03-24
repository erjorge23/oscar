# AI Deployment Lab · Sesiones 5 & 6 · UNIE

**Taller activo de Diseño de Sistemas de Información** — 4 horas en 2 sesiones.

> De la decisión de negocio a la arquitectura de cómputo. Simula el trabajo real de consultoría en despliegue de IA.

---

## 📁 Estructura

```
/
├── index.html   ← Página principal: casos, instrucciones y rúbrica
└── lab.html     ← Taller interactivo (6 módulos, sin dependencias de servidor)
```

## 🚀 Publicar en GitHub Pages

1. Crear un repositorio en GitHub (puede ser privado)
2. Subir estos dos archivos a la rama `main`
3. Ir a **Settings → Pages → Source → Deploy from branch → main / (root)**
4. En 1–2 minutos la web estará disponible en `https://<usuario>.github.io/<repositorio>/`

No se necesita ningún build step, servidor ni dependencia de npm. Todo es HTML estático.

## 🗂 Contenido del taller

| Módulo | Sesión | Contenido |
|--------|--------|-----------|
| 1 · Brief del caso | S5 | Selección de caso + 3 decisiones críticas + supuestos |
| 2 · Mapa de decisiones | S5 | Tablero Decisión → Dato → KPI en 3 capas |
| 3 · Arquitectura | S5 | Selección de patrón de despliegue con radar de encaje |
| 4 · Economía del cómputo | S6 | Simulación de coste mensual con sliders en tiempo real |
| 5 · Riesgo & gobernanza | S6 | Selección y evaluación de riesgos regulatorios |
| 6 · Brief ejecutivo | S6 | Entregable auto-generado con score de completitud |

## 📋 Casos incluidos

- 🏥 **Salud** — Resumen clínico & codificación CIE-10 (RGPD · ENS · AI Act alto riesgo)
- 💻 **Tecnología** — Copiloto técnico para desarrolladores (SOC2 · ISO 27001)
- 🏦 **Banca** — Chatbot regulatorio & detección de fraude (DORA · PSD2 · MiFID II)
- 📦 **Retail** — Previsión de demanda & asistente operativo (RGPD · NIS2)

## ⚙️ Tecnología

- **index.html**: HTML + CSS puro, sin frameworks. Fuentes: IBM Plex (Google Fonts CDN).
- **lab.html**: React 18 precompilado con Babel CLI (sin Babel en el navegador). 
  Sin warnings de consola. Funciona offline tras la primera carga.

## 👤 Autor

José Tamames · UNIE Universidad · [jtamames@unie.es](mailto:jtamames@unie.es)  
ORCID: 0009-0007-8851-9833 · Método pedagógico LIJ
