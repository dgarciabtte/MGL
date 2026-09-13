# Mi Gente Latino · Casa Behar

Sitio web promocional de **Mi Gente Latino**, obra de teatro multimedia producida por Casa Behar, y presentación de la productora.

## Estructura del proyecto

```
MGL/
├── index.html              # Landing page: banner + proyectos + contacto
├── quienes-somos.html      # Casa Behar y el equipo
├── mi-gente-latino.html    # Página de la obra: trailer, funciones, galería, feedback
├── contacto.html           # Formulario de contacto
├── css/
│   └── styles.css          # Estilos compartidos (una sola hoja para todo el sitio)
├── js/
│   └── script.js           # Menú móvil, modal de suscripción, formularios de prueba
└── images/
    ├── equipo/              # Fotos del equipo (Ricardo, Tatiana, Diana)
    ├── mi-gente-latino/      # Afiche oficial de la obra
    └── proyectos/            # Pósters de producciones anteriores
```

## Cómo verlo localmente

No requiere instalación. Basta con abrir `index.html` directamente en el navegador,
o levantar un servidor local desde esta carpeta:

```bash
python3 -m http.server 8000
```

y visitar `http://localhost:8000`.

## Estado actual

- Los formularios (feedback, suscripción, contacto) son solo de front-end por ahora:
  muestran un mensaje de confirmación pero no envían ni guardan datos a ningún servidor.
- La sección "Proyectos" del landing enlaza a `#` — la página de detalle por obra
  todavía no está construida.
- El rol y la biografía de Salomón Behar Jaramillo están pendientes de confirmar
  (actualmente con texto de prueba).

## Paleta de marca

| Color    | Hex       | Uso                                  |
|----------|-----------|---------------------------------------|
| Amarillo | `#FFCC00` | Botones, títulos sobre fondo morado   |
| Morado   | `#6838B8` | Fondos oscuros, texto sobre fondo claro |
| Magenta  | `#D92C64` | Acentos, badges                       |
| Blanco   | `#FFFFFF` | Fondos claros, texto sobre fondo morado |
| Negro    | `#000000` | Texto de cuerpo sobre fondo claro     |
