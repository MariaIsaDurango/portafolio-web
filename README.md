# Portafolio — María Isabel Durango

Portafolio profesional personal. HTML5 + CSS3 + JavaScript vainilla, sin frameworks ni dependencias de build.

## Estructura

```
├── index.html          → Página principal (reclutador)
├── proyectos.html       → Proyectos personales y colaborativos
├── sobre-mi.html        → Sobre mí
├── css/style.css        → Estilos (un único archivo)
├── js/script.js         → Menú móvil + año dinámico del footer
└── assets/
    ├── img/
    ├── icons/
    └── documents/        → CV en PDF
```

## Cómo verlo en local

No requiere instalación. Sirve la carpeta con cualquier servidor estático, por ejemplo:

```
python3 -m http.server 8080
```

y abre `http://localhost:8080`.

## Despliegue

Preparado para alojarse en Hostinger, GitHub Pages, Vercel o Netlify — `index.html` está en la raíz, tal como requieren estos servicios.
