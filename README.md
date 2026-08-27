# 📍 Cerca V1

**Todo lo que necesitás, cerca tuyo**

App de comercio de proximidad hiperlocal que conecta vecinos con pequeños comercios del barrio (almacenes, verdulerías, panaderías, kioscos, feriantes).

## 🚀 Inicio rápido

### Probar la app móvil (modo demo)
1. Abrí la carpeta `app/`
2. Abrí `index.html` en tu navegador
3. ¡Listo! Funciona sin configuración

### Subir a internet (Netlify)
1. Arrastrá la carpeta `app/` a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Te da una URL pública tipo `https://tu-app.netlify.app`
3. Compartila por WhatsApp

### Probar la landing page
1. Abrí la carpeta `landing/`
2. Abrí `index.html` en tu navegador

## 🔥 Configurar Firebase (opcional)

La app funciona en **modo demo** sin configuración. Para datos reales:

1. Creá proyecto en [console.firebase.google.com](https://console.firebase.google.com)
2. Habilitá Authentication (Google), Firestore y Storage
3. Copiá las credenciales en `app/index.html` (buscar `firebaseConfig`)
4. Publicá las reglas de `firebase/firestore.rules` y `firebase/storage.rules`

## 📂 Estructura del proyecto

```
cerca-v1/
├── app/                    # App móvil HTML/JS completa
│   └── index.html
├── landing/                # Landing page pública
│   └── index.html
├── firebase/               # Reglas de seguridad
│   ├── firestore.rules
│   └── storage.rules
└── README.md
```

## 🎯 Features incluidas

- 🗺️ Mapa interactivo con comercios georreferenciados
- 🔍 Búsqueda inteligente (comercios + productos)
- 🏷️ Filtros por categoría (9 categorías)
- ❤️ Sistema de favoritos con persistencia
- ⭐ Reseñas con calificación de estrellas
- 🌙 Modo oscuro
- 👨‍💼 Panel del comerciante
- ➕ CRUD completo de productos
- 💬 Integración WhatsApp directa
- 🔐 Firebase Auth (Google + anónimo)
- 🗄️ Firestore en tiempo real
- 📦 Firebase Storage para imágenes
- 📱 Diseño responsive

## 🎨 Branding

- **Nombre:** Cerca
- **Slogan:** "Todo cerca tuyo"
- **Color principal:** Verde mercado (#2E7D32)
- **Color secundario:** Amarillo cálido (#F9A825)
- **Tipografía:** Plus Jakarta Sans + Inter

## 🛠️ Stack tecnológico

- HTML5 + CSS3 + JavaScript
- Tailwind CSS
- Leaflet (mapas)
- Firebase SDK v10 (Auth, Firestore, Storage)
- Font Awesome (íconos)

## 📱 Próximos pasos

- [ ] Migración a Flutter nativo
- [ ] Notificaciones Push (FCM)
- [ ] Analytics
- [ ] Publicación en Google Play / App Store

---

**Versión:** 1.0.0  
**Fecha:** Agosto 2026  
**Estado:** MVP funcional
