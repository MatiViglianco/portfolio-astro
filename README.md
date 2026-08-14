# Portfolio — Backend & AI Integrations Engineer

Portfolio profesional de Matías Viglianco, orientado a backend con Python/Django, integraciones de IA y automatización empresarial. Presenta una selección breve de sistemas reales, resultados medibles y enlaces verificables.

**Puedes ver el sitio en vivo aquí:** [https://MatiViglianco.github.io/portfolio-astro/](https://MatiViglianco.github.io/portfolio-astro/)

---

### ✨ Características Principales

* **Diseño Moderno y Responsivo:** Totalmente adaptable a cualquier dispositivo, desde móviles hasta pantallas de escritorio.
* **Animaciones Dinámicas:** Implementación de animaciones de aparición al hacer scroll para una experiencia de usuario más atractiva.
* **Soporte Multi-idioma:** Funcionalidad para cambiar entre Español e Inglés, con traducciones gestionadas a través de un script personalizado.
* **Selección Curada:** Seis casos destacados con problema, decisiones de ingeniería, impacto y evidencia disponible.
* **Componentes Modulares:** Estructurado con componentes reutilizables de Astro para un mantenimiento y escalabilidad sencillos.
* **Optimización de Activos:** Uso de los componentes `<Image>` de Astro para optimizar el rendimiento y la carga de imágenes.
* **Despliegue Automatizado:** Configuración de GitHub Actions para un despliegue continuo en GitHub Pages.

### 🛠️ Tecnologías Utilizadas

* **Framework Principal:** [Astro](https://astro.build/)
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
* **Despliegue:** [GitHub Pages](https://pages.github.com/)
* **CI/CD:** [GitHub Actions](https://github.com/features/actions)

---

### 🚀 Estructura del Proyecto

El proyecto está organizado siguiendo las mejores prácticas de Astro:

```
.
├── public/              # Activos estáticos (imágenes, SVGs, PDFs para descarga)
├── src/
│   ├── assets/          # Imágenes y otros activos que serán optimizados por Astro
│   ├── components/      # Componentes reutilizables de Astro (.astro)
│   ├── layouts/         # Plantillas principales de la página
│   └── pages/           # Páginas y rutas del sitio
├── astro.config.mjs     # Archivo de configuración de Astro
├── package.json
└── README.md
```

* **`src/components`**: Contiene todos los componentes modulares que conforman las diferentes secciones del portafolio (Hero, Experience, Projects, etc.).
* **`src/layouts`**: Define la estructura HTML base, importando estilos globales y scripts.
* **`public`**: Almacena los archivos que necesitan ser accesibles directamente a través de una URL, como los CVs para descargar y los íconos.

---

### 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, en una terminal:

| Comando         | Acción                                           |
| :-------------- | :----------------------------------------------- |
| `npm install`   | Instala las dependencias del proyecto.           |
| `npm run dev`   | Inicia el servidor de desarrollo en `localhost:4321`. |
| `npm run build` | Compila el sitio para producción en la carpeta `./dist/`. |
| `npm run preview` | Previsualiza el sitio compilado localmente.      |

### 👀 Contacto

Si quieres saber más sobre mi trabajo o tienes alguna pregunta, no dudes en contactarme:

* **LinkedIn:** [Matías Agustín Viglianco](https://www.linkedin.com/in/mat%C3%ADas-agust%C3%ADn-viglianco/)
* **GitHub:** [@MatiViglianco](https://github.com/MatiViglianco)
