# Proyecto: Leyes de la Gestalt - Mateo Amaya

Este proyecto es una página web que explora y demuestra las Leyes de la Gestalt aplicadas al diseño.

## 1. Leyes Representadas

La página web incluye secciones dedicadas a las siguientes ocho leyes de la Gestalt:

-   **Proximidad**: Los elementos cercanos se perciben como un grupo.
-   **Semejanza**: Los elementos similares se agrupan visualmente.
-   **Continuidad**: El ojo sigue patrones y líneas fluidas.
-   **Cierre**: El cerebro completa figuras incompletas.
-   **Figura–fondo**: Se distingue un objeto principal (figura) de su entorno (fondo).
-   **Simetría**: Las formas simétricas se perciben como una unidad.
-   **Experiencia**: La percepción se basa en experiencias previas.
-   **Pregnancia (Ley de la Simplicidad)**: La mente prefiere las formas más simples posibles.

## 2. Ejemplos Visuales

Cada ley se ilustra con una imagen y una descripción textual para facilitar su comprensión:

## 3. Efecto Parallax

El efecto parallax se ha implementado para crear una sensación de profundidad y dinamismo al hacer scroll.

-   **Secciones afectadas**: Se ha aplicado en las secciones de **Semejanza**, **Figura-fondo** y **Pregnancia**.
-   **Implementación**: Se logró mediante la propiedad CSS `background-attachment: fixed;`. Esto mantiene la imagen de fondo estática mientras el contenido de la sección se desplaza sobre ella. Para mejorar la experiencia en dispositivos móviles, el efecto se desactiva.

## 4. Accesibilidad

Se han tomado medidas para garantizar que la página sea algo más accesible a los usuarios:

-   **Contraste de color**: Se ha definido una paleta de colores tanto para el tema claro como para el oscuro que asegura un alto contraste entre el texto y el fondo.
-   **Jerarquía de títulos**: La estructura del contenido utiliza etiquetas HTML semánticas (`<h1>`, `<h2>`, `<p>`) de forma correcta. 
-   **Alternativas a imágenes**: Todas las imágenes de ejemplo (`<img>`) incluyen un atributo `alt` con un texto descriptivo. Esto proporciona contexto a los usuarios con discapacidad visual o en caso de que la imagen no se cargue.

## 5. Despliegue

-   **Plataforma**: El proyecto será desplegado en **Vercel**.
  
## 6. Tema Visual

El diseño de la página ha sido personalizado para ofrecer una experiencia visual coherente y agradable.

-   **Modo Oscuro**: Se ha implementado un interruptor para alternar entre un tema claro y uno oscuro. El tema seleccionado se guarda en el `localStorage` del navegador para que la preferencia del usuario persista en futuras visitas. El modo oscuro utiliza una paleta de colores con fondos oscuros y texto claro para reducir la fatiga visual en condiciones de poca luz.
