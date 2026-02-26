# Graficación por Computadora - Apuntes

##  Índice

1. [1.1 Historia y evolución de la graficación por computadora](#11-historia-y-evolución-de-la-graficación-por-computadora)
2. [1.2 Áreas de aplicación](#12-áreas-de-aplicación)
3. [1.3 Aspectos matemáticos de la graficación](#13-aspectos-matemáticos-de-la-graficación)
4. [1.4 Modelos del color: RGB, CMY, HSV y HSL](#14-modelos-del-color-rgb-cmy-hsv-y-hsl)
5. [1.5 Representación y trazo de líneas y polígonos](#15-representación-y-trazo-de-líneas-y-polígonos)
6. [1.5.1 Formatos de imagen](#151-formatos-de-imagen)
7. [1.6 Procesamiento de mapas de bits](#16-procesamiento-de-mapas-de-bits)

---

# 1.1 Historia y evolución de la graficación por computadora

La graficación por computadora es una rama de la informática dedicada a la generación, manipulación y representación de imágenes digitales mediante algoritmos matemáticos y dispositivos electrónicos.

## Evolución histórica

### Década de 1950
- Uso de tubos de rayos catódicos (CRT).
- Aplicaciones militares y científicas.
- Visualización básica de datos en radares.

### Década de 1960
- Desarrollo de Sketchpad (1963).
- Inicio del diseño asistido por computadora (CAD).
- Interacción mediante lápiz óptico.

### Década de 1970
- Primeros gráficos tridimensionales.
- Desarrollo de algoritmos de sombreado.
- Expansión académica.

### Década de 1980
- Popularización de computadoras personales.
- Aparición de videojuegos comerciales.
- Interfaces gráficas de usuario (GUI).

### Década de 1990
- Modelado y renderizado 3D avanzado.
- Industria cinematográfica digital.
- Simulación realista.

### Actualidad
- Realidad virtual (VR)
- Realidad aumentada (AR)
- Motores gráficos en tiempo real
- Inteligencia artificial aplicada a gráficos

---

# 1.2 Áreas de aplicación

La graficación por computadora tiene múltiples aplicaciones:

## Videojuegos
- Motores gráficos 2D y 3D.
- Simulación física.
- Animación en tiempo real.

## Cine y animación
- Efectos visuales (VFX).
- Renderizado fotorrealista.
- Captura de movimiento.

## Medicina
- Reconstrucción 3D de órganos.
- Diagnóstico por imagen.
- Simulación quirúrgica.

## Arquitectura e ingeniería
- Modelado estructural.
- Diseño industrial.
- Simulación de prototipos.

## Interfaces gráficas
- Sistemas operativos.
- Aplicaciones móviles.
- Software interactivo.

---

# 1.3 Aspectos matemáticos de la graficación

La base matemática de la graficación incluye:

- Geometría analítica
- Álgebra lineal
- Vectores
- Matrices
- Cálculo diferencial

## Vectores

Se utilizan para representar:
- Posición
- Dirección
- Velocidad
- Normales de superficie

## Matrices

Permiten realizar transformaciones como:

- Traslación
- Rotación
- Escalamiento
- Reflexión

En gráficos 3D se utilizan matrices de transformación homogéneas.

## Transformaciones geométricas

Las transformaciones permiten modificar objetos en el espacio sin alterar su estructura básica.

---


# 1.4 Modelos del color: RGB, CMY, HSV y HSL

Los modelos de color permiten representar colores digitalmente según el medio de visualización.

## RGB (Red, Green, Blue)

- Modelo aditivo.
- Utilizado en pantallas.
- Cada color se representa con valores entre 0 y 255.

Ejemplo:
RGB(255, 0, 0) = Rojo puro.

## CMY (Cian, Magenta, Yellow)

- Modelo sustractivo.
- Utilizado en impresión.
- Se basa en absorción de luz.

## HSV (Hue, Saturation, Value)

- Hue: Matiz (0° a 360°)
- Saturation: Intensidad del color
- Value: Brillo

Es más intuitivo para diseño gráfico.

## HSL (Hue, Saturation, Lightness)

Similar al HSV pero utiliza luminosidad en lugar de brillo.

---

# 1.5 Representación y trazo de líneas y polígonos

En gráficos digitales, los objetos se representan mediante líneas y polígonos.

## Algoritmo DDA

- Método incremental.
- Calcula puntos intermedios de una línea.

## Algoritmo de Bresenham

- Más eficiente.
- Usa únicamente operaciones enteras.
- Muy utilizado en sistemas gráficos.

## Polígonos

Un polígono está formado por múltiples segmentos de línea.

Se utilizan para:
- Modelado 2D
- Modelado 3D
- Renderizado de superficies

---

# 1.5.1 Formatos de imagen

Los formatos de imagen determinan cómo se almacenan los datos visuales.

## JPG
- Compresión con pérdida.
- Reduce tamaño del archivo.

## PNG
- Compresión sin pérdida.
- Soporta transparencia.

## GIF
- Permite animaciones simples.
- Limitado a 256 colores.

## BMP
- Sin compresión.
- Alta calidad pero gran tamaño.

## TIFF
- Alta calidad.
- Usado en impresión profesional.

---

# 1.6 Procesamiento de mapas de bits

Un mapa de bits está compuesto por una matriz de píxeles.

Cada píxel contiene información de color.

## Operaciones básicas

- Ajuste de brillo
- Contraste
- Filtros
- Detección de bordes
- Escalado
- Rotación
- Compresión

El procesamiento de mapas de bits es esencial en:

- Edición de imágenes
- Visión por computadora
- Reconocimiento de patrones
- Inteligencia artificial
