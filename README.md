Taller IA-Perú: Guía de Recursos y Prompts
Este es un sitio web estático desarrollado para el Taller de Inteligencia Artificial en Perú, liderado por el Ing. Pedro Céspedes Vargas. La plataforma sirve como un centro de recursos interactivo donde docentes y profesionales pueden acceder a herramientas de IA y aprender a redactar prompts efectivos.

🚀 Características Principal
Guía Visual de Prompts: Integración de recursos visuales externos para la enseñanza de ingeniería de prompts.

Directorio de Herramientas: Base de datos categorizada de más de 30 herramientas de IA (Generativas, Imágenes, Audio, Video, Investigación y Desarrollo).

Filtro de Cuentas: Indica qué tipo de cuenta se requiere para cada herramienta (Google, Institucional, MEP, etc.).

Biblioteca de Ejemplos: 8 ejemplos detallados de prompts complejos que incluyen fórmulas de rol, contexto y tareas específicas.

Diseño Responsive: Interfaz moderna y adaptable a dispositivos móviles utilizando CSS puro y variables de entorno (:root).

📂 Estructura del Proyecto
El proyecto está contenido en un único archivo index.html para facilitar su distribución y carga rápida:

HTML5: Estructura semántica para SEO y accesibilidad.

CSS3: Sistema de diseño basado en CSS Grid y Flexbox. Incluye efectos de desenfoque de fondo (backdrop-filter) y gradientes dinámicos.

JavaScript (Vanilla): Lógica para el renderizado dinámico de las tablas, gestión de eventos de filtrado (mostrar/ocultar herramientas) y validación de carga de imágenes externas (Dropbox).

🛠️ Tecnologías Utilizadas
Lenguajes: HTML, CSS, JavaScript.

Fuentes: Inter (vía sistema).

Iconografía/Logos: TeachUNITED.

Hosting recomendado: GitHub Pages, Vercel o Netlify.

📝 Ejemplos de Prompts Incluidos
El sitio destaca fórmulas pedagógicas para crear:

Cuentos con estilos literarios específicos.

Transcripciones de imagen a texto.

Cuestionarios basados en videos de YouTube.

Canciones infantiles educativas (Salsa).

Presentaciones sobre DUA (Diseño Universal para el Aprendizaje).

Código de juegos educativos (Snake en HTML/JS).

Sesiones de aprendizaje siguiendo el currículo peruano.

🔧 Personalización
Para agregar nuevas herramientas o ejemplos, simplemente localiza las constantes en la sección de <script>:

JavaScript
const allTools = [
  // Agrega aquí tu nueva herramienta
  { category: 'Categoría', name: 'Nombre', link: 'URL', account: 'Tipo', note: 'Descripción' }
];
👤 Autor
Ing. Pedro Céspedes Vargas Especialista en IA y Educación
