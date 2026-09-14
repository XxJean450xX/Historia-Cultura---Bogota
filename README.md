# 🏛️ Bogotá Memoria Viva — Historias Ocultas

Una aplicación web interactiva y _responsive_ diseñada para explorar la memoria histórica del Centro Internacional y zonas emblemáticas de Bogotá. A través de un plano cartográfico estilizado, los usuarios pueden recorrer los puntos clave de la ciudad, seguir rutas peatonales entre vías y desplegar visores enriquecidos con historias, datos poco conocidos y galerías fotográficas.

---

## 🚀 Características Principales

- **🗺️ Cartografía Interactiva y Personalizada:** Basada en **Leaflet.js** con mapas base de Esri World Street Map libres de tokens de API.
- **🔄 Vista Rotada (Perspectiva Oeste):** Mapa cargado e inclinado a `-90°` mediante el plugin `leaflet-rotate`, optimizando la navegación de la sabana de Bogotá.
- **📍 Marcadores Vektoriales Estilizados:** Pines en forma de gota de ubicación con animaciones de pulso en CSS puro y paleta cromática editorial.
- **🛣️ Ruta Peatonal Automática:** Trazado de rutas por vías reales mediante **OSRM (Open Source Routing Machine)** y _Leaflet Routing Machine_, simulando recorridos a pie por aceras y pasajes.
- **🖼️ Visor Modal con Carrusel Dinámico:** Tarjetas informativas desplegables con soporte para múltiples imágenes, controles de navegación y gestos táctiles (_swipe_) en móviles.
- **📱 Diseño 100% Responsive:** Adaptación fluida entre escritorio y dispositivos móviles (con experiencia tipo _bottom sheet_ en pantallas pequeñas).

---

## 🎨 Paleta de Colores (Estética Histórico-Editorial)

El proyecto utiliza variables CSS (`:root`) basadas en tonos vintage, pergamino y ladrillo representativos de la arquitectura tradicional bogotana:

| Variable            | Hex / Valor | Aplicación                                  |
| :------------------ | :---------- | :------------------------------------------ |
| `--papel`           | `#e7d9b9`   | Fondo general de la aplicación              |
| `--papel-tarjeta`   | `#f2e9d6`   | Contenedores de cartucho y tarjetas modales |
| `--tinta`           | `#241c15`   | Tipografía principal y contrastes           |
| `--ladrillo`        | `#b11b00`   | Marcadores (pines) y trazado de ruta        |
| `--ladrillo-oscuro` | `#6d2c20`   | Encabezados y títulos principales           |
| `--verde-cerro`     | `#45593a`   | Sección de datos curiosos y detalles        |
| `--laton`           | `#a9852e`   | Destacados y estados hover                  |

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Estructura semántica, animaciones personalizadas y layout mediante CSS Grid / Flexbox.
- **JavaScript (ES6+):** Manipulación del DOM, manejo de eventos táctiles/teclado y renderizado dinámico.
- **[Leaflet.js (v1.9.4)](https://leafletjs.com/):** Librería principal de mapas interactivos.
- **[leaflet-rotate](https://github.com/Rtblab/leaflet-rotate):** Plugin para control de rotación y _bearing_ del plano.
- **[Leaflet Routing Machine](https://www.mapbox.com/leaflet-routing-machine/):** Enrutamiento por vías urbanas peatonales con OSRM.
- **Google Fonts:** Tipografías _Fraunces_ (serif histórico) y _Work Sans_ (sans-serif de alta legibilidad).

---

## 📁 Estructura del Proyecto

```text
.
├── index.html              # Código fuente principal (HTML, CSS y JS unificados)
├── img/                    # (Opcional) Carpeta para imágenes locales de los lugares
└── README.md               # Documentación del proyecto
```
