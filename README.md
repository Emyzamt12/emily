GESTIÓN DE DISPOSITIVOS IOT
Descripción
Una interfaz web moderna, intuitiva y accesible diseñada para la gestión, control y monitoreo en tiempo real de dispositivos IoT (Internet de las Cosas). Este panel permite a los operadores supervisar variables ambientales críticas repartidas geográficamente a través de una experiencia visual limpia y adaptativa.

Características Principales
Dashboard Centralizado: Tarjetas de información analítica con métricas clave como el total de dispositivos activos, alertas críticas, promedio de temperatura y estado general de la red.
Monitoreo Geográfico: Integración visual de un mapa mundi para localizar geográficamente cada nodo o sensor IoT.
Panel Técnico de Ubicación: Vista detallada que se actualiza al seleccionar una región o dispositivo, mostrando coordenadas, datos climáticos específicos y telemetría de interés.
Control de Inventario (Tabla IoT): Listado avanzado de los dispositivos con filtros por estado (Activo, Inactivo, Mantenimiento), tipo de sensor y nivel de batería.
Analítica Visual: Gráficos resumidos e históricos de las mediciones ambientales tales como Humedad, Temperatura y CO2.
Diseño Totalmente Responsive: Optimizado para una visualización correcta en monitores de escritorio, tablets y dispositivos móviles.
Accesibilidad Web Avanzada: Desarrollado bajo los estándares WCAG 2.1 AA, garantizando el uso correcto de etiquetas semánticas, contrastes de color adecuados y compatibilidad con lectores de pantalla.

Tecnologías Utilizadas
Este proyecto se construyó utilizando tecnologías web estándar para garantizar la máxima velocidad de carga, ligereza y facilidad de despliegue sin dependencias complejas de servidor:
HTML5: Estructuración semántica y accesible de la interfaz.
CSS3: Estilos avanzados, variables globales para escalabilidad y maquetación responsiva mediante CSS Grid y Flexbox.
JavaScript (Vanilla JS): Lógica de control para la interactividad del dashboard, actualización de componentes y simulación o renderizado de datos.

Estructura del Proyecto
La arquitectura del código está organizada de forma limpia y modular:

Plaintext
gestión-dispositivos-iot/
│
├── index.html          # Estructura principal y maquetación semántica del Dashboard
├── styles.css          # Estilos globales, layouts, componentes y Media Queries
└── README.md           # Documentación del proyecto (este archivo)
Instalación y Despliegue
Al ser una aplicación basada en el lado del cliente (Client-Side), no requiere de servidores, bases de datos complejas o compiladores para su visualización local.

Paso 1: Clonar el repositorio
Bash
git clone https://github.com/tu-usuario/gestion-dispositivos-iot.git
Paso 2: Navegar a la carpeta del proyecto
Bash
cd gestion-dispositivos-iot
Paso 3: Ejecución
Abra el archivo index.html directamente en su navegador web preferido.

Alternativa recomendada: Si utiliza Visual Studio Code, puede hacer clic derecho sobre index.html y seleccionar la opción "Open with Live Server" para disfrutar de la recarga en vivo mientras edita el código.

Enfoque en Accesibilidad (A11y)
Este proyecto ha sido diseñado para garantizar que el software sea inclusivo. Se implementaron los siguientes criterios:
Navegación por Teclado: Uso correcto de focos visuales para permitir el control total de la interfaz mediante la tecla Tab.
Etiquetas ARIA: Atributos implementados en elementos interactivos y dinámicos para guiar correctamente a los lectores de pantalla.
Contraste Elevado: Combinación de colores que cumple con la regla de contraste mínimo exigida para textos y gráficos informativos.

Autor
Desarrollado por:

Emily Zambrano - Desarrolladora Principal - GitHub / LinkedIn

Licencia
Este proyecto está bajo la Licencia MIT. Para más detalles, consulte el archivo de licencia correspondiente en el repositorio.
