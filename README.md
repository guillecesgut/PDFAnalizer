# PDFAnalizer 📄

> Herramienta web para análisis forense de documentos PDF — sin servidores, sin backend, todo en el navegador.

![PDFAnalizer](https://img.shields.io/badge/version-1.0.0-E8372A?style=flat-square) ![HTML](https://img.shields.io/badge/HTML-single--file-FF6B5B?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-coral?style=flat-square)

---

## ¿Qué hace?

PDFAnalizer extrae y presenta metadata técnica de archivos PDF directamente en el navegador, sin necesidad de subir archivos a ningún servidor. Todo el procesamiento ocurre localmente.

### Datos extraídos por archivo

| Campo | Descripción |
|---|---|
| 📐 **Medida final** | Ancho × Alto en centímetros (desde MediaBox) |
| ⚙️ **Software creador** | Aplicación con la que fue generado el PDF |
| 🎨 **Perfil de color** | RGB o CMYK detectado automáticamente |
| 💾 **Peso del archivo** | Tamaño en KB |
| 📑 **Páginas** | Número de páginas del documento |
| 🗓️ **Fecha de creación** | Extraída del metadata interno |

---

## Características

- **Autenticación completa** — registro, ingreso y cierre de sesión
- **Modo invitado** — análisis rápido sin necesidad de cuenta
- **Drag & drop** — arrastra múltiples PDFs a la vez
- **Sin backend** — 100% client-side, privacidad garantizada
- **Un solo archivo** — fácil de desplegar en cualquier hosting estático

---

## Estructura del proyecto

```
PDFAnalizer/
└── index.html   ← toda la aplicación (HTML + CSS + JS)
```

---

## Uso local

```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/PDFAnalizer.git

# Abre el archivo en tu navegador
open index.html
```

No requiere instalación de dependencias ni servidor local.

---

## Despliegue en GitHub Pages

1. Ve a **Settings → Pages** en tu repositorio
2. En *Branch*, selecciona `main` y carpeta `/ (root)`
3. Guarda — en unos minutos estará disponible en:

```
https://TU_USUARIO.github.io/PDFAnalizer
```

---

## Tecnologías

- HTML5 / CSS3 / JavaScript vanilla
- Google Fonts (Playfair Display, DM Mono, Instrument Sans)
- Parsing binario de PDF sin librerías externas

---

## Licencia

MIT © 2025
