# Nosotras$ — App de Finanzas 💜🩷

App web progresiva (PWA) para llevar las finanzas entre dos personas.
Se instala en el celular como una app real, sin App Store ni Play Store.

---

## ¿Qué incluye?

- **Dashboard** con saldo total, deuda entre las dos, ahorro y tarjetas
- **Registro de gastos** con categoría, quién pagó y fecha
- **Cuenta de quién le debe a quién** automática
- **Tarjetas de crédito** con alertas de vencimiento
- **Calendario mensual** con gastos por día
- **Configuración** de nombres, saldos y meta de ahorro
- **Funciona offline** una vez instalada

---

## Cómo subir la app (Netlify — GRATIS, 5 minutos)

### Opción A: Drag & drop (la más fácil)

1. Entra a **https://app.netlify.com**
2. Crea cuenta gratis (puedes entrar con Google)
3. En el dashboard, busca el recuadro que dice **"drag and drop"**
4. Arrastra la **carpeta `nosotras-app`** completa ahí
5. Netlify te da una URL tipo `https://abc123.netlify.app`
6. ¡Listo! Comparte esa URL con tu pareja

### Opción B: GitHub (recomendado para actualizarla fácil)

1. Crea cuenta en **https://github.com**
2. Nuevo repositorio → sube los 5 archivos
3. En Netlify → "Import from Git" → conecta el repo
4. Cada vez que edites un archivo en GitHub, la app se actualiza sola

---

## Cómo instalarla en el celular

### Android (Chrome)
1. Abre la URL en Chrome
2. Aparece un banner en la parte inferior: **"Agregar a pantalla de inicio"**
3. Si no aparece: menú (⋮) → "Agregar a pantalla de inicio"

### iPhone (Safari)
1. Abre la URL en **Safari** (no Chrome)
2. Toca el botón compartir (□↑)
3. Desliza y toca **"Agregar a pantalla de inicio"**
4. Ponle el nombre "Nosotras$" → Agregar

---

## Para que las dos compartan los mismos datos

Los datos actualmente se guardan en el celular de cada una por separado
(localStorage). Para sincronización en tiempo real entre los dos celulares,
necesitarías agregar Firebase — dime y te ayudo a configurarlo, es gratis
para uso personal y toma como 20 minutos.

Por ahora, si quieren usar los mismos datos pueden:
- Que una persona lleve el registro en su celu
- O exportar/importar datos manualmente

---

## Archivos incluidos

```
nosotras-app/
├── index.html      ← toda la app
├── manifest.json   ← configuración PWA
├── sw.js           ← hace que funcione offline
├── icon-192.png    ← ícono del celular
└── icon-512.png    ← ícono grande
```

---

## Personalización rápida

Abre `index.html` y busca estas líneas para cambiar colores:
```css
--acc: #9c92e6;   /* morado principal */
--rose: #dd6ca2;  /* rosa */
```

---

Hecho con 💜 para Nar
