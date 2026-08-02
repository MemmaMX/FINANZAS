# 💰 Mis Finanzas — PWA Personal Finance App

App de organización financiera personal con plan de pago de deudas quincena por quincena. Diseñada como PWA optimizada para iPhone.

---

## 📱 Cómo abrirla en tu iPhone

### Opción 1 — GitHub Pages (recomendada)

1. En tu repositorio de GitHub, ve a **Settings** → **Pages**
2. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`
3. Haz clic en **Save**
4. Espera ~1 minuto y ve a la URL que aparece (ej: `https://memmamx.github.io/FINANZAS/`)
5. En Safari, abre esa URL
6. Toca el botón **Compartir** (el cuadrado con flechita arriba) → **Agregar a pantalla de inicio**
7. Dale un nombre (ej: "Finanzas") y toca **Agregar**

¡Listo! Ya tienes el ícono en tu pantalla de inicio como si fuera una app nativa. 🎉

### Opción 2 — Abrir directo desde GitHub

1. Ve a `https://github.com/MemmaMX/FINANZAS`
2. Abre el archivo `index.html`
3. Toca **Raw** y luego guarda o abre en Safari

---

## ✨ Funcionalidades

- 🏠 **Dashboard** — resumen de deudas, dinero disponible, alertas de pagos próximos
- 💳 **Deudas** — tarjetas y préstamos con barras de progreso, indicadores de urgencia
- 📅 **Plan** — quincenas Q1–Q9 con los cálculos de Gemini precargados; marca pagos como realizados y actualiza saldos automáticamente
- 🏦 **Cuentas** — BBVA y Santander débito con edición manual de saldos e historial de pagos

## 💾 Persistencia

Todos los cambios se guardan automáticamente en `localStorage` del navegador. Los datos se conservan aunque cierres la app o el navegador.

## 🎨 Diseño

- Dark mode elegante con acentos verdes/azules
- Optimizado para iPhone (safe areas, bottom navigation, PWA meta tags)
- Sin dependencias externas — un solo archivo `index.html`