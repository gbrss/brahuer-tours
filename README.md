# Brahuers Tour - Landing Page

Landing page profesional para **Brahuer Tours**, empresa de turismo y transporte en Chile.

Construida con **Astro.js** + **Tailwind CSS** (integración oficial).

## Características

- Diseño premium en negro y dorado
- Responsive (móvil y desktop)
- Secciones: Hero, Servicios, Destinos, Nosotros, Contacto
- Formulario de contacto
- Bandera de Chile integrada
- Tipografía elegante (Playfair Display + Inter)

## Cómo ejecutar

```bash
# Instalar dependencias
npm install

# Modo desarrollo
npm run dev

# Build de producción
npm run build

# Preview del build
npm run preview
```

Abre `http://localhost:4321` en tu navegador.

**Importante:** Después de `npm install`, reinicia el servidor de desarrollo (`Ctrl+C` y luego `npm run dev`) para que Tailwind se aplique correctamente.

## Estructura

```
brahuers-tours/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## Tecnologías

- Astro 5
- @astrojs/tailwind
- Tailwind CSS 3
- Google Fonts

---

**Brahuer Tours** · *Tu destino, nuestra ruta*
