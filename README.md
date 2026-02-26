# Graficación  - Apuntes

## Índice

1.1 Historia y evolución de la graficación por computadora  
1.2 Áreas de aplicación  
1.3 Aspectos matemáticos de la graficación  
1.4 Modelos del color: RGB, CMY, HSV y HSL  
1.5 Representación y trazo de líneas y polígonos  
1.5.1 Formatos de imagen  
1.6 Procesamiento de mapas de bits  

---

# 1.1 Historia y evolución de la graficación por computadora

La graficación por computadora es una rama de la informática dedicada a la generación, manipulación y representación de imágenes digitales mediante algoritmos matemáticos y dispositivos electrónicos.

Sus orígenes se remontan a la década de 1950, cuando las computadoras comenzaron a utilizar pantallas tipo radar para mostrar información visual básica. En ese tiempo solo se podían representar líneas simples y puntos.

En 1963, Ivan Sutherland desarrolló Sketchpad, considerado el primer sistema interactivo de gráficos por computadora. Este sistema permitió dibujar figuras directamente en la pantalla usando un lápiz óptico, marcando el inicio del diseño asistido por computadora (CAD).

Durante los años 70 y 80, la graficación comenzó a expandirse en áreas como la investigación científica, los videojuegos y el diseño industrial. Con el avance del hardware y las tarjetas gráficas, fue posible desarrollar gráficos tridimensionales más complejos.

En la actualidad, la graficación por computadora es fundamental en campos como la animación digital, la realidad virtual, la simulación y la inteligencia artificial.

---

# 1.2 Áreas de aplicación

La graficación por computadora tiene una gran variedad de aplicaciones en distintos sectores.

En los videojuegos, permite crear escenarios, personajes y efectos visuales en tiempo real.

En el cine y la animación digital, se utiliza para generar efectos especiales y escenas tridimensionales que no podrían realizarse físicamente.

En la medicina, facilita la visualización de órganos mediante estudios como tomografías y resonancias magnéticas.

En arquitectura e ingeniería, permite modelar edificios y estructuras antes de su construcción, reduciendo errores y costos.

También es esencial en las interfaces gráficas de usuario, ya que todos los elementos visuales de un sistema operativo o aplicación son generados mediante técnicas de graficación.

---

# 1.3 Aspectos matemáticos de la graficación

La graficación por computadora se fundamenta en principios matemáticos.

Se utilizan vectores para representar posiciones y direcciones en el espacio.  
Las matrices permiten realizar transformaciones sobre los objetos.

Las transformaciones geométricas básicas son:

- Traslación: desplazar un objeto de una posición a otra.
- Rotación: girar un objeto respecto a un eje.
- Escalamiento: aumentar o disminuir el tamaño.
- Reflexión: generar una imagen espejo.

En gráficos tridimensionales también se emplean conceptos de álgebra lineal y geometría analítica para calcular perspectiva, iluminación y sombreado.

---

# 1.4 Modelos del color: RGB, CMY, HSV y HSL

Los modelos de color permiten representar colores en formato digital dependiendo del dispositivo o aplicación.

El modelo RGB (Rojo, Verde y Azul) es un modelo aditivo utilizado en pantallas. Los colores se forman combinando diferentes intensidades de estos tres colores básicos.

El modelo CMY (Cian, Magenta y Amarillo) es un modelo sustractivo utilizado principalmente en impresión.

El modelo HSV se basa en tres componentes:
- Matiz (Hue)
- Saturación
- Valor o brillo

Este modelo es más intuitivo porque se asemeja a la forma en que el ser humano percibe el color.

El modelo HSL es similar al HSV, pero utiliza luminosidad en lugar de valor para representar la intensidad de la luz.
![WhatsApp Image 2026-02-25 at 22 20 14](https://github.com/user-attachments/assets/e3d72ac0-f55a-472c-8fa2-265b22abdcc2)

![WhatsApp Image 2026-02-25 at 22 20 25](https://github.com/user-attachments/assets/0355883b-c993-4ee5-bc45-3a8efea010ad)

<img width="1536" height="1024" alt="ChatGPT Image 25 feb 2026, 10_45_57 p m" src="https://github.com/user-attachments/assets/9735095e-8f22-41c7-9d5d-cd221ef35f92" />



---

# 1.5 Representación y trazo de líneas y polígonos

En los sistemas digitales, las imágenes están formadas por píxeles. Para representar líneas rectas en una pantalla se utilizan algoritmos específicos.

El algoritmo DDA calcula puntos intermedios entre dos coordenadas para formar una línea.

El algoritmo de Bresenham es más eficiente, ya que utiliza operaciones enteras y reduce el uso de recursos computacionales.

Los polígonos están formados por múltiples segmentos de línea conectados. Son fundamentales en el modelado 2D y 3D, ya que cualquier objeto complejo puede dividirse en una combinación de polígonos.

---

# 1.5.1 Formatos de imagen

Los formatos de imagen determinan cómo se almacena la información visual.

JPG utiliza compresión con pérdida, lo que reduce el tamaño del archivo pero puede disminuir la calidad.

PNG utiliza compresión sin pérdida y permite transparencia.

GIF permite animaciones simples, aunque tiene una limitación en la cantidad de colores.

BMP no utiliza compresión, por lo que genera archivos de gran tamaño.

TIFF es utilizado en impresión profesional debido a su alta calidad.
![WhatsApp Image 2026-02-25 at 20 10 16](https://github.com/user-attachments/assets/97e08105-dce6-440e-89f3-cf1c64abdcb5)
![WhatsApp Image 2026-02-25 at 20 10 52](https://github.com/user-attachments/assets/f1d224fc-4797-4829-964a-07a31666c589)

---

# 1.6 Procesamiento de mapas de bits

Un mapa de bits es una imagen compuesta por una matriz de píxeles.

Cada píxel almacena información de color, y la calidad de la imagen depende de la resolución y la profundidad de color.

El procesamiento de mapas de bits incluye operaciones como:

- Ajuste de brillo y contraste
- Aplicación de filtros
- Detección de bordes
- Escalado y rotación
- Compresión

Este procesamiento es fundamental en áreas como la edición de imágenes, la visión por computadora y la inteligencia artificial.

# Referencias Bibliográficas

Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). *Computer Graphics: Principles and Practice* (2nd ed.). Addison-Wesley.

Hearn, D., & Baker, M. P. (2011). *Computer Graphics with OpenGL* (4th ed.). Pearson.

Angel, E., & Shreiner, D. (2015). *Interactive Computer Graphics: A Top-Down Approach with WebGL* (7th ed.). Addison-Wesley.

Rogers, D. F. (2001). *Procedural Elements for Computer Graphics* (2nd ed.). McGraw-Hill.

Gonzalez, R. C., & Woods, R. E. (2018). *Digital Image Processing* (4th ed.). Pearson.

Shirley, P., Marschner, S., & others. (2020). *Fundamentals of Computer Graphics* (4th ed.). A K Peters/CRC Press.
