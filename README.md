# 🌸 Mis Gastos — PWA

App de registro de gastos personales. Funciona 100% offline, se instala en tu celular como app nativa, y los datos se guardan localmente con IndexedDB.

## 📲 Cómo subir a GitHub Pages (paso a paso)

### Paso 1 — Crear el repositorio
1. Abre [github.com](https://github.com) en tu celular o computadora
2. Toca el botón **"+"** → **"New repository"**
3. Nombre: `mis-gastos` (o el que quieras)
4. Marca **"Public"**
5. Toca **"Create repository"**

### Paso 2 — Subir los archivos
En la página del repo vacío:
1. Toca **"uploading an existing file"**
2. Sube estos archivos (en este orden):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - La carpeta `icons/` con `icon-192.png` e `icon-512.png`

> **Tip para subir la carpeta icons:** Arrastra toda la carpeta al área de upload, o sube los íconos individualmente con la ruta `icons/icon-192.png`

3. Toca **"Commit changes"**

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** (⚙️) del repositorio
2. En el menú izquierdo toca **"Pages"**
3. En **"Source"** selecciona **"Deploy from a branch"**
4. En **"Branch"** selecciona **"main"** → carpeta **"/ (root)"**
5. Toca **"Save"**

### Paso 4 — Tu URL
En 1–2 minutos tu app estará en:
```
https://TU_USUARIO.github.io/mis-gastos/
```

### Paso 5 — Instalar en el celular
- **Android (Chrome):** Abre la URL → toca los 3 puntos → "Agregar a pantalla de inicio"
- **iPhone (Safari):** Abre la URL → toca el ícono de compartir → "Agregar a pantalla de inicio"

¡Listo! La app queda instalada como app nativa y funciona sin internet. 🌸

---

## ✨ Funcionalidades

- ✅ 5 semanas por mes, de Junio a Diciembre 2025
- ✅ Contador de C$ 1,500 mensual que baja en tiempo real
- ✅ Se pone **rojo** cuando alcanzas C$ 250 en la semana actual
- ✅ Se pone **verde** en semanas pasadas (ya completadas)
- ✅ Categorías: Alimentos 🍎, Transporte 🚌, Servicios 💡, Entretenimiento 🎮, Otros 📦
- ✅ Exportar a CSV (para Excel/Google Sheets)
- ✅ Backup en JSON
- ✅ Compartir resumen por WhatsApp
- ✅ Ajustes para cambiar presupuesto mensual y semanal
- ✅ Funciona 100% offline
- ✅ Datos guardados en IndexedDB (no se pierden al cerrar)

## 🔧 Cambiar el presupuesto
Dentro de la app toca ⚙️ → ajusta los montos → Guardar.
