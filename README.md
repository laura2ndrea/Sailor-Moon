# Landing Page (Sailor Moon) 

Este proyecto es una Landing Page dedicada a Sailor Moon, creada como parte de la evaluación de habilidades en CSS y HTML. La página contiene información sobre Sailor Moon, incluyendo su historia, personajes principales y otros detalles relevantes del universo de Sailor Moon.

## Información general 

### Semántica (HTML) 

- **home.html:** este documento representa una página de inicio dedicada a Sailor Moon. En el <head>, se especifican los metadatos, incluyendo el juego de caracteres, la configuración de visualización y los enlaces a los recursos como el icono y la hoja de estilos CSS. En el <body>, la estructura principal incluye un contenedor que abarca un encabezado (<header>) con el logo y la navegación, un <main> dividido en dos secciones: la izquierda con el título y la descripción, y la derecha con una imagen. Además, hay una sección de redes sociales con enlaces a Facebook, Instagram y YouTube.
  
- **historia.html:** este documento se centra en la historia de Sailor Moon. En el <head>, se definen los metadatos, incluyendo el juego de caracteres, la configuración de visualización, el icono de la página y la hoja de estilos CSS. El <body> contiene un contenedor principal con un encabezado (<header>) que incluye el título "HISTORIA" y un enlace a la página de inicio. El contenido principal está dividido en dos secciones: la izquierda y la derecha, cada una con varios contenedores que presentan imágenes y textos que describen eventos significativos en la historia de Sailor Moon desde su creación en 1991 hasta el estreno de "Sailor Moon Eternal" en 2021.
  
- **personajes.html**: este documento está diseñado para mostrar información sobre los personajes de Sailor Moon. En el <head>, se especifican los metadatos, incluyendo el juego de caracteres, la configuración de visualización, el icono de la página y la hoja de estilos CSS. En el <body>, se encuentra un contenedor principal que incluye un encabezado (<header>) con el título "PERSONAJES" y un enlace a la página de inicio. El contenido principal consiste en un contenedor de tarjetas, cada una representando a un personaje diferente con una imagen, un título y un enlace que dirige a más información sobre el personaje en el sitio fandom de Sailor Moon.
  
- **creadora.html**: este documento presenta información sobre Naoko Takeuchi, la creadora de Sailor Moon. En el <head>, se incluyen los metadatos esenciales como el juego de caracteres, la configuración de visualización, el icono de la página y la hoja de estilos CSS. En el <body>, hay un contenedor principal que alberga un encabezado (<header>) con el título "CREADORA" y un enlace a la página de inicio. El contenido está dividido en dos secciones: la izquierda muestra una imagen de Naoko Takeuchi y su nombre, mientras que la derecha contiene tres tarjetas que detallan su biografía, estilo y obra, con imágenes y descripciones en el frente y el reverso de cada tarjeta.
  
- **galería.html**: este documento muestra una galería de Sailor Moon. En el <head>, se definen los metadatos como el juego de caracteres, la configuración de visualización, el icono de la página y la hoja de estilos CSS. En el <body>, hay un contenedor principal que incluye un encabezado (<header>) con el título "GALERÍA" y un enlace a la página de inicio. La sección de la galería contiene varios elementos que muestran imágenes y un video relacionado con Sailor Moon, cada uno con su respectivo recurso gráfico.
  
### Apariencia (CSS) 
  (Pantalla error)
  ![error](/recursos/no-disponible.png)
  
- **home.css**: la clase .header establece un encabezado con un diseño flexbox que alinea los elementos a la derecha, incluyendo un logo que rota al pasar el cursor sobre él. El menú de navegación (nav) presenta enlaces con estilos interactivos, como cambios de tamaño al pasar el cursor y transiciones de color y fondo. El contenido principal (main) y sus contenedores (container-izquierdo y container-derecho) utilizan flexbox para centrar y distribuir elementos de manera uniforme. Los estilos de texto (titulo y descripcion) y botones (boton) están diseñados con transiciones suaves y efectos de sombra al interactuar. Además, la sección de redes sociales (redes) se posiciona fija en el lado derecho de la pantalla, con íconos que aumentan de tamaño al pasar el cursor. Se incluyen también media queries para ajustar el diseño en dispositivos con pantallas más pequeñas.

  (Diseño original)
  
   ![home](/imagenes-readme/home-can.png)
  
  (Página web)
  
  ![home](/imagenes-readme/home-pag.png)
  
- **personajes.css:** el encabezado (h1) tiene una fuente "Libre Franklin", un tamaño de fuente adaptable, y efectos de sombra que se intensifican al pasar el cursor. El contenedor secundario utiliza un diseño de cuadrícula (grid) para organizar elementos en filas y columnas. Las tarjetas tienen un diseño centrado, con esquinas redondeadas y sombras, y su imagen se agranda al pasar el cursor. La superposición en las tarjetas se expande para mostrar más contenido al pasar el cursor, incluyendo un título con la fuente "Petit" y un enlace estilizado. Un botón de inicio (#home) se posiciona en la esquina superior derecha y aumenta de tamaño al interactuar. La hoja de estilos también incluye ajustes para pantallas más pequeñas, reduciendo el tamaño de las tarjetas y el botón de inicio para mejorar la adaptabilidad y la experiencia del usuario.

  (Diseño original)
  
  ![personajes](/imagenes-readme/personajes-can.png)
  
  (Página web)
  
  ![personajes](/imagenes-readme/personajes-pag.png)
  
- **creadora.css:** los contenedores principales se estructuraron usando flexbox y grid, y las tarjetas tienen una animación de volteo en el hover, mostrando diferentes caras con contenido distinto. Además, hay estilos específicos para una imagen con transición de escala, y ajustes para dispositivos móviles mediante media queries, asegurando una presentación adecuada en diferentes tamaños de pantalla.
   
  (Diseño original)
  
  ![creadora](/imagenes-readme/creadora-can.png)
  
  (Página web)
  
  ![creadora](/imagenes-readme/creadora-pag.png)
  
- **galeria.css:** la clase .container-secundario organiza un diseño de cuadrícula para imágenes y videos, con transiciones de escala en hover y configuraciones específicas para ciertos elementos de la cuadrícula. Un icono con el identificador #home en la esquina superior derecha también se escala al pasar el cursor sobre él. Se incluyen reglas de medios para ajustar el tamaño y la posición del icono en pantallas más pequeñas.
   
  (Diseño original)
  
  ![galeria](/imagenes-readme/galeria-can.png)
  
  (Página web)
  
  ![galeria](/imagenes-readme/galeria-pag.png)
- **pantalla no-disponible:**
  
## Tecnologías 
- **HTML5:** utilizado para estructurar y organizar el contenido de la página web, asegurando que sea semánticamente correcta y accesible. 
- **CSS3:** utilizado para dar estilo y diseño a la página web. Con CSS3, se aplicaron estilos avanzados como transiciones, animaciones, y efectos de transformación. También se implementaron reglas de medios para asegurar que el diseño sea responsive y se adapte a diferentes tamaños de pantalla y dispositivos, proporcionando una experiencia de usuario consistente y atractiva.
